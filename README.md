CoreCloud Static Website Deployment on AWS S3 

Overview
This project showcases a cost-effective, serverless deployment of the CoreCloud landing page. The static website, built with HTML/CSS, is hosted directly on Amazon S3 for high availability and scalability. The deployment confirms correct configuration of public access and asset serving.
Live URL: https://abrahamseed.s3.us-east-1.amazonaws.com/corecloud.html

Architecture & Technologies i used

 Category  | Component    Purpose                                                    
 --------- | -----------  ---------------------------------------------------------- 
 Hosting   | AWS S3        Static Website Hosting, Asset Storage (abrahamseed bucket) 
 Front end | HTML, CSS     Website structure and styling                              
 Tooling   | Git, Python   Version control and local build environment                


Key Implementation Steps
1) S3 Configuration: Created the abrahamseed bucket (US East N. Virginia), disabled Block Public Access, and applied a public read Bucket       Policy.

2) Deployment: Uploaded all assets, setting the Index Document to coreCloud.html.

3) Validation: Verified successful external access, correct image/CSS loading, and functional navigation to the registration page.
