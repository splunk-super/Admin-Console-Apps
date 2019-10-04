Admin-Console-Apps
To add an app:

Add a remote repository: 'git remote add CDT_aws_indexer_discovery git@${GITHOST}:Splunk/CDT_aws_indexer_discovery.git'
Add a subtree: 'git subtree add --prefix=CDT_aws_indexer_discovery CDT_aws_indexer_discovery master'
To update an app:

Perform a subtree pull: 'git subtree pull --prefix=CDT_aws_indexer_discovery --squash CDT_aws_indexer_discovery master'
