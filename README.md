Copy print_bot_id.py and query_solver.py in  a directory.
Install pip-
    sudo apt-get update
    sudo apt-get install python-pip

Install virtualenv with pip –
    pip install virtualenv
Create a virtual environment in that directory – 
    In terminal go to that directory -
    Type “virtualenv query_solver”
    Type “source query_solver/bin/activate”
Install slackclient
    Type “pip install slackclient”
Now go to slack web API page and sign up to create your own slack team. You can also sign into an existing account where you have administrative rights.

After you have signed in go to Bot Users (https://save-animals.slack.com/apps/new/A0F7YS25R-bots) page.

Name your bot query_solver then click “Add bot integration” button.

The page will reload and you will see a newly-genrated access token. Copy that token.
Now in terminal in that directory type “export SLACK_BOT_TOKEN=’paste token that you have copied’
Now run print_bot_id.py
Your bot id will be generated . Copy it.
Now in terminal in that directory type “export BOT_ID=’bot id that you copied’
Now run query_solver.py
In slack create a new channel and invite query_solver or invite it to a existing channel.
Now start giving query_solver commands in your channel.
Note - If query is given in form “search ‘whatever the error is’ ”.It will work.
Ex - @query_solver search python


