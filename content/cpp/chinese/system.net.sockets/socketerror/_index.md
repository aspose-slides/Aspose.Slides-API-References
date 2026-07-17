---
title: SocketError
second_title: Aspose.Slides for C++ API 参考
description: 枚举套接字错误类型。
type: docs
weight: 209
url: /zh/system.net.sockets/socketerror/
---
## SocketError 枚举

枚举套接字错误类型。

```cpp
enum class SocketError
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Success | 0 | 套接字操作成功完成。 |
| SocketError | -1 | 发生未指定的套接字错误。 |
| Interrupted | 10004 | 阻塞套接字调用被取消。 |
| AccessDenied | 10013 | 对套接字的访问被拒绝。 |
| Fault | 10014 | 检测到无效的指针地址。 |
| InvalidArgument | 10022 | 提供了无效的参数。 |
| TooManyOpenSockets | 10024 | 底层套接字提供程序中打开的套接字太多。 |
| WouldBlock | 10035 | 在非阻塞套接字上无法立即完成操作。 |
| InProgress | 10036 | 阻塞操作正在进行中。 |
| AlreadyInProgress | 10037 | 非阻塞套接字已有正在运行的操作。 |
| NotSocket | 10038 | 尝试在非套接字上调用套接字操作。 |
| DestinationAddressRequired | 10039 | 套接字操作中缺少必需的地址。 |
| MessageSize | 10040 | 数据报太长。 |
| ProtocolType | 10041 | 此套接字不支持该协议类型。 |
| ProtocolOption | 10042 | 使用了未知、无效或不受支持的选项或级别。 |
| ProtocolNotSupported | 10043 | 协议未实现或未配置。 |
| SocketNotSupported | 10044 | 地址族不支持指定的套接字。 |
| OperationNotSupported | 10045 | 协议族不支持地址族。 |
| ProtocolFamilyNotSupported | 10046 | 协议族未实现或未配置。 |
| AddressFamilyNotSupported | 10047 | 不支持指定的地址族。 |
| AddressAlreadyInUse | 10048 | 地址只能使用一次。 |
| AddressNotAvailable | 10049 | 在此上下文中所选的 IP 地址无效。 |
| NetworkDown | 10050 | 网络不可用。 |
| NetworkUnreachable | 10051 | 不存在到远程主机的路由。 |
| NetworkReset | 10052 | 应用程序尝试在已超时的连接上设置“Keep-Alive”。 |
| ConnectionAborted | 10053 | 连接已中止。 |
| ConnectionReset | 10054 | 连接被远程对等方重置。 |
| NoBufferSpaceAvailable | 10055 | 套接字操作没有可用的空闲缓冲区空间。 |
| IsConnected | 10056 | 套接字已连接。 |
| NotConnected | 10057 | 应用程序尝试发送或接收数据，但套接字未连接。 |
| Shutdown | 10058 | 由于套接字已关闭，发送或接收数据的请求被禁止。 |
| TimedOut | 10060 | 连接尝试超时，或已连接的主机未响应。 |
| ConnectionRefused | 10061 | 远程主机主动拒绝连接。 |
| HostDown | 10064 | 由于远程主机宕机，操作失败。 |
| HostUnreachable | 10065 | 不存在到指定主机的网络路由。 |
| ProcessLimit | 10067 | 使用底层套接字提供程序的进程太多。 |
| SystemNotReady | 10091 | 网络子系统不可用。 |
| VersionNotSupported | 10092 | 底层套接字提供程序的版本超出范围。 |
| NotInitialized | 10093 | 底层套接字提供程序未初始化。 |
| Disconnecting | 10101 | 正在进行优雅的关闭。 |
| TypeNotFound | 10109 | 未找到指定的类。 |
| HostNotFound | 11001 | 指定的主机未知。 |
| TryAgain | 11002 | 无法解析主机名。 |
| NoRecovery | 11003 | 错误不可恢复或请求的数据库无法定位。 |
| NoData | 11004 | 在名称服务器上未找到请求的名称或 IP 地址。 |

## 另请参见

* 命名空间 [System::Net::Sockets](../)
* 库 [Aspose.Slides](../../)