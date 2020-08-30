# UnblockNeteaseMusic Magisk Module
 
  这是用于Magisk的UnblockNeteaseMusic
## 本模块已包含
* [UnblockNeteaseMusic](<https://github.com/AdguardTeam/AdGuardHome/releases/latest>)
* [magisk-module-installer](<https://github.com/topjohnwu/magisk-module-installer>)

## 安装

从release下载，然后在Magisk Manager中安装

## 使用

### 使用前

1.安装 `busybox` 2.确保你的设备有 `curl` 命令

### 服务控制

* 在Andoid termux下以 `su` 权限执行 `UnblockNeteaseMusic` 命令
* 可用参数
```
-help    帮助
check    检查运行状态
start | stop | restart    开启服务|关闭服务|重启服务
update    更新UnblockNeteaseMusic
```
* 例如: `UnblockNeteaseMusic start` 以启动服务

### 注意:服务默认开机自启

## 卸载

* Magisk Manager 中卸载
