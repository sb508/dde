#手动设置ipv6地址

| 编号 | 步骤                   | 预期                                                         |
| ----| ---------------------- | ------------------------------------------------------------ |
| 1   |打开控制中心-网络-有线网路-有线连接-IPv6-方法。选择“手动”|  IPv6地址方法被选择为手动              |
| 2   |输入IP地址：2000:0000:0000:0000:0001:2345:6789:ABCD, 前缀输入"88",保存网络设置  | 保存成功，网络服务重启 |
| 3   |打开终端，通过命令ifconfig -a，查看IPv6地址是否已经被设置成手动需要的地址         | IPv6设置成功 |
