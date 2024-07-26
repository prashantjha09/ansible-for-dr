ansible-vault create git_credentials.yml

This command will open the file in your default text editor where you can enter your sensitive information. For example, you might enter something like this:

git_username: your_username

git_password: your_password


ansible-playbook connect_ec2.yaml

ansible-playbook install-nginx.yaml

ansible-playbook clone.yml --ask-vault-pass
