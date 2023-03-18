Assignment 1

1 . Create a Google Compute Engine 

2. Machine Type should be e2-micro

3 . Boot Disk image should be :-  Debian GNU/Linux 11 (bullseye)

4 . Add a startup script to install nginx , below script can be used 
    
    sudo apt-get update 
    
    sudo apt install nginx -y 
    
5 .  Network and subnet can be chosen by you based on what was created in previous session

6 . Take the image of the browser , where nginx page is loaded by clicking on external IP

7 .  Reserve the external IP so that IP is not changed when VM is restarted




![1-vmcreation-e2micro](https://user-images.githubusercontent.com/26878098/226101084-c0485324-ec88-497b-8511-4181289e4bdb.jpg)
![2-bootdisk](https://user-images.githubusercontent.com/26878098/226101085-3d932c03-8304-465f-863b-6f8fa6162160.jpg)
![3-subnet-reserve ip](https://user-images.githubusercontent.com/26878098/226101086-c9cde705-7bbd-4bb2-8326-cbb47ec6bc41.jpg)
![4-startup script](https://user-images.githubusercontent.com/26878098/226101080-f8c9546f-70c4-4ff4-a07c-37fede64f9e2.jpg)
![5-nginxpage](https://user-images.githubusercontent.com/26878098/226101083-bf556813-df90-4c03-9742-7d5f81ee413d.jpg)
