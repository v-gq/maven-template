# maven-templates
maven archetpye template <br>

安装
=======
git到本地后进入文件夹 <br>
$ `mvn archetype:create-from-project`  <br>
$ `cd target/generated-sources/archetype/`  <br>
$ `mvn install` <br>

无用文件 <br>
其中 *.un~ 的文件是vim备份文件  <br>
到该项目根目录下执行： <br>
$ `rm -rf $(find . -type f -name "*.un~")` <br>
即可全部删除 <br>
[pom文件](https://github.com/v-gq/maven-templates/blob/master/pom.xml)

目录结构 
========
~~~~~~~~~~~~~~~
├── pom.xml
├── README.md
└── src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── gq
    │   │           └── Application.java
    │   └── resources
    │       └── application.yml
    └── test
        ├── java
        │   └── com
        │       └── gq
        │           └── TestApplicatonTest.java
        └── resources
            └── application.yml

