# cowsay.random
Script to run **cowsay** with a random .cow file from '/usr/share/cowsay/cows'.<br/>
It reads out your .cow files each time, so it should be ideal for custom files.

Uses <ins>fortune-mod</ins> to display the message, so either edit the cowsay message 
or see the fortune-mod package as a dependencie.


## Installation

If we assume you are running part of your software from your ~/.bin directory already:

`curl -O https://raw.githubusercontent.com/viper1446/cowsay.random/refs/heads/main/cowsay.random $HOME/.bin`<br/>
<br/>
<br/>
Making the script executable:
<br/>
`chmod +x $HOME/.bin/cowsay.random`
<br/>
<br/>
And now you should be able to run cowsay.random from your terminal.
