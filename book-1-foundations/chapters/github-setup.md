# Github Setup

### Create SSH key

SSH is a technology that allows you to create a very secure connection between your computer, and a computer located somewhere else in the world. It's an acronym for Secure SHell. When you create an SSH key on your computer, it actually creates two files

1. A public key file that you share with other people and computers. It is usually named `id_rsa.pub`.
1. A private key file that you never, ever, ever, ever, ever share with anyone. It is usually named `id_rsa`.

Step 1:  Follow the Github instructions for [MAC](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-mac) or [PC](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-windows) for creating a new SSH key, and providing your public key to Github, so that you can establish a secure connection between your computer and Github's computers.

Step 2: Add the SSH key to your [github account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

Step 3: Check your github key using your terminal.
```sh
ssh -T git@github.com
```

### Set up your author information
1.  Check to see who your computer thinks you are:
```sh
git config -l
```

2.  Set the correct username
```sh
git config --global user.name "Your Name"
```

3.  Set the correct email
```sh
git config --global user.email "you@example.com"
```

4.  Run the first command again to make sure you are now set correctly


