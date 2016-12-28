#Ota升级说明书

- 系统升级 （进入系统升级页面）
      - 无网络情况（系统显示当前版本，提示网络异常）
      - 有网络情况（显示发现新版本、新版本号及更新说明按钮、立即更新按钮）
         - 更新说明按钮（点击，进入更新说明详细说明）
         - 立即更新按钮（点击，进入下载新版本升级包）
            - 完成升级包下载（弹出对话框）
               - 对话框（提示新版本升级包已下载完成，需重启系统完成升级，用户可选择稍后重启或立即重启）
               - 稍后重启（点击，提示用户稍后稍后重启完成升级）
               - 立即重启（点击，重启系统完成升级）



```
实验室内网升级说明`
1） 设置-关于设备-系统升级配置- 输入： http://192.168.0.180/openthos/
2)  点OTA 应用-立即更新（有bug  896:20161221-今日OTA版本升级，上来就是99％，然后到100％空白，无重启按钮。再次升级才正常。 ）
```
＃功能
- 查看当前系统版本
- 查看当前版本是不是最新版本
- 检测是否有新版本
- ![]https://github.com/openthos/community-analysis/blob/master/pic/using-instractions-pic/tmp_15653-Screenshot_2016-12-28-10-18-50293635875.png
- 查看新版本的新功能
- ![]https://github.com/openthos/community-analysis/blob/master/pic/using-instractions-pic/tmp_15653-Screenshot_2016-12-28-10-18-57906777015.png
- 下载系统新版本
_ ![]https://github.com/openthos/community-analysis/blob/master/pic/using-instractions-pic/tmp_15653-Screenshot_2016-12-28-10-19-18-1462869611.png
- 断点续传功能
- 切换内外网下载功能
- ![]https://github.com/openthos/community-analysis/blob/master/pic/using-instractions-pic/tmp_15653-Screenshot_2016-12-28-10-35-131574476588.png
- ![]https://github.com/openthos/community-analysis/blob/master/pic/using-instractions-pic/tmp_15653-Screenshot_2016-12-28-10-38-31-1032758385.png
- 生成文件写入版本号，服务器收到完成升级
- 升级版本，使用新版本系统
