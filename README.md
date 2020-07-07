# management-master
本小区物业管理系统分成两种角色，分别是小区业主和小区物业管理员，小区业主登录系统后可以投诉、维修上报、查看账单、登录注册等；管理员登录系统后可以对用户进行管理，并且可以对车位、房屋、缴费、社区服务等进行管理。小区物业管理系统使用Java语言开发，使用IDEA的开发平台，通过Tomcat服务器发布项目，使用的架构为B/S架构。

#### 系统功能设计

##### 1、登录模块
小区物业管理系统面向两种角色：管理员、小区业主。两者都是经由一个登陆入口登陆系统，通过该登陆模块，用户输入账户密码且选择登陆角色后可以登录系统，根据用户的权限进行相应的管理操作。

##### 2、我的维修模块
我的维修模块面向业主的功能是维修信息提报，业主可以添加维修信息，并且可以查看相应的维修信息；管理员通过自己的社区服务的功能模块下的维修管理，可以查看业主所提交的维修信息，并且可以对维修信息进行维护、修改。

##### 3、用户系统模块
用户系统模块是面向管理员使用的模块，本模块的主要功能是用户管理，管理员可以通过本模块添加业主，添加的业主信息包括用户名、手机号、性别等；通过本模块管理员可以对用户的车位、房屋进行停用，并且可以管理房屋分配、车位分配、缴费管理等。管理员还可以修改业主信息，还可以删除业主信息。
##### 4、房屋系统模块
房屋系统模块是面向管理员使用的模块，本模块的主要功能是楼栋管理、单元管理、房屋管理三个子模块；楼栋管理包括对小区的楼栋进行添加、修改、删除等；单元管理是对小区内所有的单元信息进行管理的模块，管理员可以添加单元、修改单元信息、删除单元信息等；房屋管理是对小区内所有的房屋信息进行管理，包括添加房间名、房间面积、状态等信息。
##### 5、车位系统模块
车位系统模块主要的功能是对车位信息进行管理，管理员可以添加所有的车位信息，并且可以条件查询车位信息。管理员也可以对车位信息进行分配，并且可以修改车位信息、删除车位信息。
##### 6、缴费系统模块
缴费系统模块也是面向管理员使用的模块，主要功能包括缴费类型、缴费管理。缴费类型包括对于物业收费的类型，包括水费、电费、物业费等；缴费管理包括查看业主本月是否缴费，并且可也确认业主缴费。
##### 7、个人中心模块
个人中心模块是管理员及用户都有的模块，通过本模块无论是管理员还是用户都可以对个人信息进行管理，并且可以进行维护。

![](http://tiebapic.baidu.com/forum/w%3D580/sign=3fa880119cd4b31cf03c94b3b7d7276f/b0b91bdfa9ec8a131662ccb2e003918fa1ecc0fa.jpg)  
