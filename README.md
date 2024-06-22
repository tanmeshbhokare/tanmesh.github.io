# About Me

Critical thinking DevOps Engineer with extensive understanding of high availability architecture and concepts.
Purpose driven professional who can be a strong team player plus work effectively independently.

# My work

[**Migrated Jenkins** from Windows 2012 server to Windows 2019 server.](https://tanmesh.hashnode.dev/migrate-jenkins-from-windows-2012-to-windows-server-2019)

[**Refactored** the Jenkins shared library from single file of 2.5k LOC to a structured file hierarchy using OOPS concepts and reducing redundancy](https://tanmesh.hashnode.dev/create-optimized-jenkins-shared-library)

Integrated jenkins build status with BitBucket SCM by writing a function in jenkins shared library which uses bitbucket APIs.

- Encountered a challenge with build status as bitbucket doesn't support unstable status.
- Wrote an Algorithm to handle this issue.

Further organised or modified jenkinsfile to looklike templates & all logics were transfered to shared library /vars 

Wrote confluence publish function after "publish to confluence" plugin was suspended by Jenkins.

Developed a python utility in python for managing the VM interactions on AWS and Vagrant (on-premises)

Introduced docker to our pipelines for containerizing dotnet based apps & uploading on docker hub.

Wrote an ansible script for updating agent.jar files on jenkins nodes.

Replaced openCover tool with dotCover on all C#, .Net pipelines as dotCover was better rated in our research.

Replaced a few Windows UI based integration tests from AWS EC2 to Vagrant on-prem VMs to save costs.

Researched SonarQube with other SAST tools and later had a discussion with upper management for buying atleast developer edition as it gives PR features.

Created a template for gitlab-CI, as it uses YAML. I was too restricted but identified few workarounds for reusbaility like anchors & alias, hidden stages, extends keyword and include in common file.

Enabled default merge checks on Bitbucket for repositories.

Added auto comment on PR via Jenkins shared library, using build info as a context for comment body and build status for approval on PR.
