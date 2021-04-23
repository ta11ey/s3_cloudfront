# Demo - Aws, CI/CD

### Tech used
- s3
- cloudfront
- vim
- iam
- git

![](https://github.com/ta11ey/s3_cloudfront/raw/master/demo.gif)
### Steps


### What I learned
- initially i thought I'd be using codedeploy to run the CD but codepipeline is actually the tool for this project since I am not setting up any EC2 instances, but rather just replacing static files on an s3 Site.
- Really worked with the paradigm of least priveledge with the Iam Service role, and granting codepipeline app access only to the repo it was workign with rather than the whol account 
