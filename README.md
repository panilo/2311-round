# Hi! 

This is a simple challenge to test your skills on 

1. Terraform 
2. AWS knowledge 
3. Python

What we care about is 

1. Simple solutions: this task is nothing complicated, we expect a simple and linear solution to the problem.
2. Code quality: code quality is a huuuge word, please apply the highest quality checks you've in mind for coding (comments, SAST/OSS, lint, etc...).
3. Test your code! We need a test suit to check if the code is doing what we expect it to do.
4. Write as much code as you can: we allow you to use existing libs for repetitive tasks, but would be nice to see how your code too :) don't overuse libraries! 
5. Draw: architecture diagrams, code diagrams; we like diagrams a lot! 


# Challange description 

You are asked to build a VPC with public and private subnets. In the private subnet, create an EC2 instance serving a Flask application of your coding; the Flask app has to be downloaded from an S3 bucket and installed onboard the EC2. 

No public network connection must reach the EC2 instance in the private subnet, therefore you need to proxy the connection somehow... this is your call :) 

Some requirements 

1. SSM must be enabled in both public and private subnets to access the EC2 instance
2. All the data has to be encrypted in transit
2. Test in your Python app must be present, even simple testing. Show us you can code in Python, without overcomplicating the challenge.

Please submit everything in a public repository and share the link with us, you can even fork this repo. 