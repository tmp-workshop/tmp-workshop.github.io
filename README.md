## Accessing the Eaton-lab *tmp-workshop* server

### First, get an invitation 
Click on [this link to a google spreadsheet](https://docs.google.com/spreadsheets/d/1Gp8OXWsquGESiadM0skCYvx-zoqneukLWFGmsdRvYGc/edit?usp=sharing) and add your GitHub ID to the first column. I will then send you an invite to join the `tmp-workshop` organization.   

### Change membership to public
Once I've finished sending the invite, go to or refresh the page at [https://github.com/tmp-workshop/](https://github.com/tmp-workshop), click on the tab that says `People`, find your username, and change the membership from `Private` to `Public` like in the screenshot below:  
 <img src="https://github.com/tmp-workshop/tmp-workshop.github.io/blob/master/screenshot-members.png" alt="People tab"> 

### Login to the server
You should now be able to login to the workshop server at: [https://jhub.eaton-lab.org](https://jhub.eaton-lab.org). 

### About the server
You are now logged into a `jupyterhub` instance running on the Eaton-lab server at Columbia University. While here, you will be contained within a Docker container, which limits the parts of the system that you have access to. But, you will have full read/write access to your little corner of the filesystem, including the ability to install software into your own local conda distribution. In addition, most software you would need is already installed for you. Once the workshop is over you will likely be removed from the *tmp-workshop* organization, thus the *tmp* in *tmp-workshop*. 

