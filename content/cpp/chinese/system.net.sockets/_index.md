---
title: "System::Net::Sockets"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 729
url: /zh/system.net.sockets/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | 表示在套接字错误发生时抛出的异常。切勿手动创建此类的实例。请改用 SocketException 类。切勿将 SocketException 类的实例包装进 [System::SmartPtr](../system/smartptr/)。 |
| [IPPacketInformation](./ippacketinformation/) | 表示有关数据包的信息。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [LingerOption](./lingeroption/) | 指定在调用 Close() 或 Close() 方法后套接字是否保持连接。它还指定在数据持续发送时套接字保持连接的时间段。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [NetworkStream](./networkstream/) | 提供用于网络访问的数据底层流。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Socket](./socket/) | [Socket](./socket/) 类实现了 Berkeley sockets 接口。 |
| [TcpClient](./tcpclient/) | 表示 TCP 网络服务的客户端。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [TcpListener](./tcplistener/) | 表示 TCP 网络服务的监听器。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [UdpClient](./udpclient/) | 提供用户数据报协议 (UDP) 网络服务。该类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
## 函数

| 函数 | 描述 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [SocketType](./sockettype/) | 列举套接字类型。 |
| [AddressFamily](./addressfamily/) | 列举地址族。 |
| [IOControlCode](./iocontrolcode/) | 列举 [IO](../system.io/) 控制码。 |
| [ProtocolFamily](./protocolfamily/) | 列举协议族。 |
| [ProtocolType](./protocoltype/) | 列举协议类型。 |
| [SelectMode](./selectmode/) | 指定轮询套接字状态的模式。 |
| [SocketError](./socketerror/) | 列举套接字错误类型。 |
| [SocketFlags](./socketflags/) | 提供套接字消息的常量值。 |
| [SocketOptionLevel](./socketoptionlevel/) | 为 '[Socket](./socket/)' 类定义套接字选项级别。 |
| [SocketOptionName](./socketoptionname/) | 为 [Socket](./socket/) 类定义套接字选项名称。 |
| [SocketShutdown](./socketshutdown/) | 定义 [Socket.Shutdown](./socket/shutdown/) 方法使用的常量。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [SocketException](./socketexception/) |  |