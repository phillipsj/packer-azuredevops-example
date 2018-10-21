# packer-azuredevops-example
This is an example repo for demonstrating user Packer with AzureDevOps

This has the basic directory structure that I use when working with Packer, it doesn't have to be organized this way, but I have found it helpful.

I have a directory called *packer*, inside of that directory is a directory specific to what the image will be used to do. Then inside of that directory I have a directory to hold *scripts* and a directory to hold *files*.

Scripts folder holds scripts that will be executed using the provisioner. Files directory is for holding any files that will need to be uploaded or mounted depending on what builder you are using.