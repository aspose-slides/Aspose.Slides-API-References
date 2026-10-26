---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的套接字地址创建 EndPoint 类的新实例。
type: docs
weight: 92
url: /zh/system.net/ipendpoint/create/
---
## IPEndPoint::Create(System::SharedPtr\<SocketAddress\>) 方法

使用指定的套接字地址创建 [EndPoint](../../endpoint/) 类的新实例。

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| socketAddress | [System::SharedPtr](../../../system/sharedptr/)\<[SocketAddress](../../socketaddress/)\> | 将用于初始化新实例的套接字地址。 |

### 返回值

新创建的 EndPoint 类实例。

## 参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [EndPoint](../../endpoint/)
* 类 [SocketAddress](../../socketaddress/)
* 类 [IPEndPoint](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)