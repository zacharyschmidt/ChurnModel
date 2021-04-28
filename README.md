# ChurnModel
To get started in collab, run this command in a notebook cell:

`!git clone https://github.com/zacharyschmidt/ChurnModel.git`


If you want to use VSCode, run this command and then click on the ngrok link. 

source: 

https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2021-labs/blob/main/setup/readme.md#Colab

```
# Launch VSCode server
!curl -fsSL https://code-server.dev/install.sh | sh
!nohup code-server --port 9000 --auth none &

# Tunnel its IP using ngrok
!pip install pyngrok
from pyngrok import ngrok
# ngrok.set_auth_token("get from https://dashboard.ngrok.com/auth/your-authtoken, if you want to pay $10/month for a little bit better service")
url = ngrok.connect(9000)
print(url)
```

Then clone the repo from the VSCode interface. 
