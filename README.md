## 运维相关管理系统
以下是收集的一些github上开源的运维管理系统，都各有特色

### 开源运维管理系统收集
 - [pythonzm/Ops](https://github.com/pythonzm/Ops) - 基于centos6+python3.6+django2+ansible2.4+celery4.2 运维管理系统，目前实现功能：用户和用户组管理、资产管理、集成ansible2.4、简易堡垒机(主机分配支持rdp以及vnc、用户分配、文件上传下载、配置禁用命令清单、操作录像回放功能)、CI/CD（支持git仓库和svn仓库）、数据库管理（一部分）、celery任务编排、知识库及文件共享
 - [leoiceo/OpenSA](https://github.com/leoiceo/OpenSA) - 资产管理、资产采集、灰度发布、反向代理、批量任务、任务编排、计划任务、日志审计、权限管理、角色管理、部门管理、运维自动化 http://opensa.imdst.com
 - [qunarcorp/open_dnsdb](https://github.com/qunarcorp/open_dnsdb) - OpenDnsdb 是去哪儿网OPS团队开源的基于Python语言的DNS管理系统
 - [liquanzhou/cedardeploy](https://github.com/liquanzhou/cedardeploy) - cedardeploy:发布系统基于python,flask,mysql,git,ssh-key,supervisor.支持多类型,上线,回滚,监控,报警
 - [cksgf/ServerManagement](https://github.com/cksgf/ServerManagement) - 服务器管理工具，目前有文件管理器、进程监控、计划任务、webSSH、多主机管理等，准备在自己服务器上用，后续会加入更多运维相关，本项目后端python+flask，前端使用layui+jquery，代码在线编辑使用codemirror，webSSH后端使用paramiko前端xterm
 - [open-cmdb/cmdb](https://github.com/open-cmdb/cmdb) - CMDB 配置管理系统 资产管理系统 http://cmdb.mmtweb.xyz
 - [smallmi/omms](https://github.com/smallmi/omms) - OMMS运维监控系统，功能介绍: 资产管理 应用管理 任务执行 权限管理等 http://www.smallmi.com
 - [getway/diting](https://github.com/getway/diting) - 运维面板，运维导航，统一账号平台，运维统一平台，LDAP管理平台
 - [hgz6536/opman-django](https://github.com/hgz6536/opman-django) - 自动化运维平台：CMDB、CI/CD、DevOps、资产管理、任务编排、持续交付、系统监控、运维管理、配置管理
 - [voilet/cmdb](https://github.com/voilet/cmdb) - cmdb saltstack
 - [wylok/opsweb](https://github.com/wylok/opsweb) - 运维综合管理平台（python3+flask+pycharts+scheduler+gunicorn),模块化结构设计,底层需要mysql、influxdb、elasticsearch、zabbix、k8s等数据源数据作为支撑。由于依赖数据源相关基础数据，仅限于代码交流学习。别忘了给个star^_^
 - [itimor/django-oms](https://github.com/itimor/django-oms) - 加强版运维系统，集成工单、发布、监控、管理dns、saltstack
 - [py2010/cmdb](https://github.com/py2010/cmdb) - django, webssh, websftp, docker 容器管理, web => xshell (从CMDB网页直接跳转到Xshell终端)
 - [opendevops-cn/opendevops](https://github.com/opendevops-cn/opendevops) - CODO是为用户提供企业多混合云、自动化运维、完全开源的云管理平台 http://www.opendevops.cn/
 - [dreamans/syncd](https://github.com/dreamans/syncd) - syncd是一款开源的代码部署工具，它具有简单、高效、易用等特点，可以提高团队的工作效率. https://rsy.me/syncd
 - [YoLoveLife/DevOps](https://github.com/YoLoveLife/DevOps) - 😃DevOps System - ❤️devEops❤️ - 开发自运维平台 - 运维体系解决方案，适用于多个应用环境的资产组织以及运维脚本的适配运行。
 - [welliamcao/VManagePlatform](https://github.com/welliamcao/VManagePlatform) - 一个KVM虚拟化管理平台
 - [sohutv/cachecloud](https://github.com/sohutv/cachecloud) - 搜狐视频(sohu tv)Redis私有云平台 http://cachecloud.github.io/
 - [meolu/walle-web](https://github.com/meolu/walle-web) - walle - 瓦力 Devops开源项目代码部署平台 https://walle-web.io
 - [luxiaok/SaltAdmin](https://github.com/luxiaok/SaltAdmin) - 基于SaltStack的自动化运维平台 http://github.com/luxiaok/SaltAdmin
 - [guohongze/adminset](https://github.com/guohongze/adminset) - 自动化运维平台：CMDB、CD、DevOps、资产管理、任务编排、持续交付、系统监控、运维管理、配置管理
 
 ### dns管理工具
 - [itimor/bindapi](https://github.com/itimor/bindapi) - binddns restfull api开发
 - [addonis1990/Bind9-with-mysql-based-configuration](https://github.com/addonis1990/Bind9-with-mysql-based-configuration) - Bind9-with-mysql-based-configuration
 - [1032231418/Bind-Web](https://github.com/1032231418/Bind-Web) - Bind-DLZ + Django + Mysql DNS管理平台
 
 ### 跳板机
 - [jumpserver/jumpserver](https://github.com/jumpserver/jumpserver) - Jumpserver是全球首款完全开源的堡垒机，是符合 4A 的专业运维审计系统。 http://www.jumpserver.org

### 数据库监控系统
 - [Georce/lepus](https://github.com/Georce/lepus) - 开源企业级数据库监控系统,MySQL/Oracle/MongoDB/Redis一站式性能监控，让数据库监控更简单
 - [gumengkai/dbmon](https://github.com/gumengkai/dbmon) - python+Django数据库监控平台(新版) Linux/Oracle/Mysql基础监控+性能监控 http://hr55ckuxxg.51http.tech/login
