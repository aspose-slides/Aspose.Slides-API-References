---
title: Socket
second_title: Aspose.Slides for C++ API 参考
description: Socket 类实现了 Berkeley 套接字接口。
type: docs
weight: 53
url: /zh/system.net.sockets/socket/
---
## Socket 类

[Socket](./) 类实现了 Berkeley 套接字接口。

```cpp
class Socket : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | 为新创建的连接创建一个新的套接字。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步连接操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步连接操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步连接操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步连接操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步写入操作。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 发起异步发送操作。 |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 将套接字绑定到指定的本地端点。 |
| void [Close](./close/)() | 关闭套接字连接。 |
| void [Close](./close/)(int) | 在指定的超时时间内关闭套接字连接，以允许排队的数据发送。 |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 建立到指定远程端点的连接。 |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | 建立到指定远程端点的连接。 |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | 建立到指定远程端点的连接。 |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | 建立到指定远程端点的连接。 |
| void [Dispose](./dispose/)() override | 不执行任何操作。 |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的异步连接操作完成。 |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的异步接收操作完成。 |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | 等待指定的异步接收操作完成。 |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | 等待指定的异步发送操作完成。 |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | 等待指定的异步发送操作完成。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），也将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），也将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | 返回地址族。 |
| **int32_t** [get_Available](./get_available/)() | 获取从网络接收的字节数并可供读取。 |
| **bool** [get_Blocking](./get_blocking/)() | 获取指示套接字是否处于阻塞模式的值。 |
| **bool** [get_Connected](./get_connected/)() | 返回指示套接字是否已连接到远程主机的值。 |
| **bool** [get_DontFragment](./get_dontfragment/)() | 获取指示套接字是否允许 IP 数据报被分片的值。 |
| **bool** [get_DualMode](./get_dualmode/)() | 获取指示套接字是否处于双模式的值。 |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | 获取指示套接字是否允许广播数据包的值。 |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | 获取指示是否只有一个进程可以将套接字绑定到端口的值。 |
| **bool** [get_IsBound](./get_isbound/)() | 返回指示套接字是否绑定到特定本地端口的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | 获取指示套接字是否会延迟关闭以尝试发送所有未完成数据的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | 返回本地端点。 |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | 获取指示套接字是否接收传出的组播数据包的值。 |
| **bool** [get_NoDelay](./get_nodelay/)() | 获取指示套接字是否使用 Nagle 算法的值。 |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | 返回指示操作系统和网络适配器是否支持 IPv4 的值。 |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | 返回指示操作系统和网络适配器是否支持 IPv6 的值。 |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | 返回协议类型。 |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | 获取接收缓冲区大小。 |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | 获取 'Receive' 调用超时的时间间隔。 |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | 返回远程端点。 |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | 获取发送缓冲区大小。 |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | 获取 'Send' 调用超时的时间间隔。 |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | 返回套接字类型。 |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | 返回指示当前主机是否支持 IPv4 的值。 |
| **int16_t** [get_Ttl](./get_ttl/)() | 获取 TTL 值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 返回指向实现的指针。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | 返回对应于指定选项名称的值。 |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 获取对应于指定选项名称的值。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | 返回对应于指定选项名称的值。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 设置套接字的底层操作模式。 |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 设置套接字的底层操作模式。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Listen](./listen/)(**int32_t**) | 将套接字状态更改为 'listen'。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | 根据指定的轮询模式返回套接字状态。 |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 从套接字接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 从指定端点接收数据并写入指定的字节数组。 |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | 从指定端点接收数据并写入指定的字节数组。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值降低共享引用计数。 |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 向套接字发送指定的数据。 |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | 向套接字发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | 向指定端点发送指定的数据。 |
| void [set_Blocking](./set_blocking/)(**bool**) | 设置指示套接字是否处于阻塞模式的值。 |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | 设置连接超时。 |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | 设置指示套接字是否允许 IP 数据报分片的值。 |
| void [set_DualMode](./set_dualmode/)(**bool**) | 设置指示套接字是否处于双模式的值。 |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | 设置指示套接字是否允许广播数据包的值。 |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | 设置指示是否只有一个进程可以将套接字绑定到端口的值。 |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | 设置指示套接字是否会延迟关闭以尝试发送所有未完成数据的值。 |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | 设置指示套接字是否接收传出组播数据包的值。 |
| void [set_NoDelay](./set_nodelay/)(**bool**) | 设置指示套接字是否使用 Nagle 算法的值。 |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | 设置接收缓冲区大小。 |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | 设置 'Receive' 调用超时的时间间隔。 |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | 设置发送缓冲区大小。 |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | 设置 'Send' 调用超时的时间间隔。 |
| void [set_Ttl](./set_ttl/)(**int16_t**) | 设置 TTL 值。 |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | 设置指定的套接字选项为指定的值。 |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 设置指定的套接字选项为指定的值。 |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | 设置指定的套接字选项为指定的值。 |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 设置指定的套接字选项为指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | 禁用套接字的发送和接收操作。 |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | 构造一个新实例。 |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | 构造一个新实例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~Socket](./~socket/)() | 析构当前实例。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ImplPtr](./implptr/) | 套接字实现。 |

## 另见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::Net::Sockets](../)
* 库 [Aspose.Slides](../../)