#Prerequisites Software

```
1.Vagrant
2.Virtualbox 
3.Ansible
```

#Deployment Steps
```
1. Download or clone the gitHub Repository..

$git clone https://github.com/mmjyothi/TestSains/

2. Change Directory 

$cd TestSains

3. Deploy goApp 

$vagrant up

```
#Test

```
4. Test/Access Application with Browser

After the vagrant up is complete, you can access to application at the below url

http://10.0.15.11/
```

#Redeployment Steps


```
1. Git Repo directory

$cd TestSains

2. Destroy VMs
$ vagrant destroy -f

3. Create new Infra and Deploy goApp
$ vagrant up
```


