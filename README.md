## random avatar

[![Build status](https://ci.appveyor.com/api/projects/status/0y937m1x8g1w6ic6/branch/master?svg=true)](https://ci.appveyor.com/project/chsword/random-avatar/branch/master)

## 说明，Description

您可以通过以下类似 URL 进行访问，You can use the following URL to access the image：

http://url/avatar/x

生成图片的代码片断，The following are pieces of code to generate images：

`var bytes = RandomAvatarBuilder.Build(100).SetPadding(5).ToBytes();`

`var image = RandomAvatarBuilder.Build(100).SetPadding(5).ToImage();`


## 示例，Example

非对称 dissymmetry

![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/1.png)
![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/3.png)
![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/4.png)

对称 symmetry

![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/5.png)
![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/6.png)
![](https://raw.githubusercontent.com/chsword/random-avatar/master/example/7.png)

### 其它特性 Other feature

如果需要固定生成的功能可以访问

url/face/seed

如

`url/face/chsword@126.com`

### Docker pull

[![Docker Stars](https://img.shields.io/docker/stars/chsword/random-avatar.svg)](https://hub.docker.com/r/chsword/random-avatar)
[![Docker Build Statu](https://img.shields.io/docker/build/chsword/random-avatar.svg)](https://hub.docker.com/r/chsword/random-avatar)

Use docker hub:
``` ps
docker pull chsword/random-avatar
```
Use Aliyun hub:
``` ps
docker pull registry.cn-hangzhou.aliyuncs.com/random-avatar/random-avatar
```
### 引用，Reference:

https://github.com/hackrslab/random-avatar
