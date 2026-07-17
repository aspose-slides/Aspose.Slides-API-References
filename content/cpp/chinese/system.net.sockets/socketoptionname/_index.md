---
title: SocketOptionName
second_title: Aspose.Slides for C++ API 参考
description: 为 Socket 类定义套接字选项名称。
type: docs
weight: 248
url: /zh/system.net.sockets/socketoptionname/
---
## SocketOptionName 枚举

为 [Socket](../socket/) 类定义套接字选项名称。

```cpp
enum class SocketOptionName
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Debug | 1 | 记录调试信息。 |
| AcceptConnection | 2 | 指示套接字是否正在监听传入连接。 |
| ReuseAddress | 4 | 指示套接字是否可以绑定到已在使用的地址。 |
| KeepAlive | 8 | 为套接字连接启用“保持活动”数据包。 |
| DontRoute | 16 | 指示数据包是否直接发送到接口地址。 |
| Broadcast | 32 | 指示套接字是否可以发送广播消息。 |
| UseLoopback | 64 | 在可能的情况下绕过硬件。 |
| Linger | 128 | 系统将在关闭尝试时阻塞进程，直至能够传输数据。 |
| OutOfBandInline | 256 | 在正常数据流中接收带外数据。 |
| DontLinger | n/a | 指示套接字将在不延迟的情况下关闭。 |
| ExclusiveAddressUse | n/a | 套接字将专用绑定的地址。 |
| SendBuffer | 4097 | 指定发送缓冲区大小。 |
| ReceiveBuffer | 4098 | 指定接收缓冲区大小。 |
| SendLowWater | 4099 | 指定发送操作的最小数据量。 |
| ReceiveLowWater | 4100 | 指定接收操作的最小数据量。 |
| SendTimeout | 4101 | 指定同步发送操作的超时时间。 |
| ReceiveTimeout | 4102 | 指定同步接收操作的超时时间。 |
| Error | 4103 | 返回错误状态并清除。 |
| Type | 4104 | 返回套接字类型。 |
| ReuseUnicastPort | 12295 | 指示系统是否应为出站连接推迟临时端口分配。 |
| MaxConnections | 2147483647 | 此选项不受支持。它用于指定监听的最大队列长度。 |
| IPOptions | 1 | 指定必须插入到出站数据报的 IP 选项。 |
| HeaderIncluded | 2 | 标头包含在出站数据报中。 |
| TypeOfService | 3 | 更改 IP 头部服务字段的类型。 |
| IpTimeToLive | 4 | IP 生存时间。 |
| MulticastInterface | 9 | 设置出站多播数据包的接口。 |
| MulticastTimeToLive | 10 | IP 多播生存时间。 |
| MulticastLoopback | 11 | IP 多播回环。 |
| AddMembership | 12 | 添加 IP 组成员资格。 |
| DropMembership | 13 | 删除 IP 组成员资格。 |
| DontFragment | 14 | 不要对 IP 数据报进行分片。 |
| AddSourceMembership | 15 | 加入 IP 组/源。 |
| DropSourceMembership | 16 | 删除 IP 组/源。 |
| BlockSource | 17 | 阻止 IP 组/源。 |
| UnblockSource | 18 | 解除阻止 IP 组/源。 |
| PacketInformation | 19 | 接收 IPv4 的数据包信息。 |
| HopLimit | 21 | 提供包含数据包跳数的整数。 |
| IPProtectionLevel | 23 | 启用对 IPv6 套接字的指定范围限制。 |
| IPv6Only | 27 | 套接字仅限发送和接收 IPv6 数据包。 |
| NoDelay | 1 | 禁用 Nagle 算法以合并发送的数据包。 |
| BsdUrgent | 2 | 使用 RFC-1222 中定义的紧急数据。 |
| Expedited | 2 | 使用 RFC-1222 中定义的加速数据。 |
| NoChecksum | 1 | 发送校验和为零的 UDP 数据报。 |
| ChecksumCoverage | 20 | 设置或获取 UDP 校验和覆盖范围。 |
| UpdateAcceptContext | 28683 | 使用监听套接字的相同属性更新客户端套接字。 |
| UpdateConnectContext | 28688 | 使用监听套接字的相同属性更新客户端套接字。 |

## 另见

* 命名空间 [System::Net::Sockets](../)
* 库 [Aspose.Slides](../../)