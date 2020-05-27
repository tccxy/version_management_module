# zu2&zu2板卡部署系统说明

## 1) 将研发部门转入的启动卡分别如下图所示插入相应的卡槽
![视图](./zu2_zu2.jpg)
* 请注意启动卡的颜色
* 请两个注意拨码开关的位置 为 
  | 1|off
  |--|--
  | 2|on
  | 3|off
  | 4|on
* 将micro-usb的线一端插入图中画圈的插口中，推荐使用win10，在设备管理器中会有两个新的串口枚举出来
![视图](./设备管理器.png)

## 2)上电
* 使用secure_crt或者putty登录设备
![视图](./secure_crt.png)
* 进入emmc_tools目录，执行操作
![视图](./执行.png)
* 等待控制台输出success
![视图](./success.png)

## 3)断电，重新启动
* 将拨码开关的位置 切换为
  | 1|on
  |--|--
  | 2|off
  | 3|off
  | 4|on
