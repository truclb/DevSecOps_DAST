# DevSecOps_DAST
This is the repos about Jenkins file for DAST. I choose OWASP ZAP for DAST.
- Our CI/CD projects like: Pull -> Build -> Buid Image -> Deploy -> DAST.
- In this Repos - I store my jenkins pipeline code.
- Before running this Jenkins pipeline, you should export a context file from the ZAP GUI and save it in the workspace. This action will help with Authenticated Scanning, allowing ZAP to scan all URL links inside the login. I followed this Website to configure context: https://www.youtube.com/watch?v=BOlalxfdLbU

