# NeteaseCheckIn

only for Netease check in  (including PC,mobilephone site)  

Thanks to [musicbox](https://github.com/darknessomi/musicbox)
 
[中文说明](https://github.com/zhangwk/NeteaseCheckIn/blob/master/README-zh.md)  
=========================

Requirements
------------
* Python  
* git


Installation
------------
```
git clone git@github.com:zhangwk/NeteaseCheckIn.git NeteaseCheckIn
```
Custom
--------

* Configure account
```python
   cd NeteaseCheckIn
   vim Netease.py
   
   ne.phone_login(
   12345678910,     =>Your phoneNumber
   'yourpassword'   =>Your password
   )
```
Discussing
----------
- [submit issue](https://github.com/zhangwk/NeteaseCheckIn/issues/new)
- email: zwk.wilson@foxmail.com

Next Plan
----------
* add mail-login function.
* collect 3-days check-in prize(5 points),and one-week check-in prize (10 points).

Plus
--------
* if you missing some library,install it.(google,baidu,whatever helps)

* it works fine on my CentOS ECS of aliyun,so enjoy it!

