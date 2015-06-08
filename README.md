#####如果你没有 clone 代码库，就需要设置基础项目.  React Native 可以让我们使用 react-native-cli npm 包 CLI 快速开始一个项目。如果你还没有安装这个，可以快速运行命令：
```
npm install -g react-native-cli
```

#####检出该代码
```
git clone https://github.com/yangtao309/FaceMash.git
```

#####需要初始化node_modules
```
react-native init FaceMash
```

#####或者更新安装nodejs模块
```
cd FaceMash
npm install
```

#####接着就可以用xcode打开代码

#####还需要运行一个后台数据服务
#####安装studdy nodejs模块
```
npm install -g stubby
```

#####进入FaceMash目录
```
cd FaceMash
stubby -d rest/config.yaml
```

#####服务启动好后，可以用下面的地址在浏览器测试下，看是否返回正常的json数据
```
http://localhost:8882/rest/mash
```

#####一切ok后即可运行xcode制定到具体的iphone设备

#####效果如下图
