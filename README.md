# dubbo 管理后台

下列模块下载地址:[Apache Dubbo(incubating)](https://github.com/mlj007/incubator-dubbo-ops)

* dubbo-admin
* dubbo-monitor-simple
* dubbo-registry-simple


## NOTICE  
dubbo admin 是官网`develop`的分支，可下载直接使用


## How to use it

### dubbo admin

Dubbo admin is a spring boot application, you can start it with fat jar or in IDE directly.

### dubbo monitor and dubbo registry

You can get a release of dubbo monitor in two steps:

* Step 1:
```
git clone https://github.com/apache/incubator-dubbo-ops
```

* Step 2:
```
cd incubator-dubbo-ops && mvn package
```

Then you will find:

* dubbo-monitor-simple-2.0.0-assembly.tar.gz in incubator-dubbo-ops\dubbo-monitor-simple\target directory. Unzip it you will find the shell scripts for starting or stopping monitor.
* dubbo-registry-simple-2.0.0-assembly.tar.gz in incubator-dubbo-ops\dubbo-registry-simple\target directory. Unzip it you will find the shell scripts for starting or stopping registry.
