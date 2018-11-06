# pyopereto
#### Opereto official Python client and CLI tool

#### Installation
```
pip install pyopereto
```
OR
```
python setup.py install
```


#### Using the command line tool
Create a file named opereto.yaml in your home directory containing Opereto access credential:
 
~/opereto.yaml
```
opereto_host: https://your_opereto_service_url
opereto_user: your_opereto_username
opereto_password: your_opereto_password
```

From the command line console, please type:
```
/>opereto -h
```


#### Using the client

```
from pyopereto.client import OperetoClient

my_client = OperetoClient(opereto_host='https://OPERETO_SERVER_URL', opereto_user='OPERETO_USERNAME', opereto_password='OPERETO_PASSWORD')
```


#### Learn more

* [Opereto REST API](https://operetoapi.docs.apiary.io/#)
* [Opereto Documentation](http://docs.opereto.com/docs)

