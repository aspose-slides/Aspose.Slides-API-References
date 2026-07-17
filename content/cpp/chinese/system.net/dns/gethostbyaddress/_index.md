---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 IP 地址字符串表示创建一个新的 IPHostEntry-class 实例。
type: docs
weight: 14
url: /zh/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) 方法

使用指定的 IP 地址的字符串表示创建一个新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP 地址的字符串表示。 |

### 返回值

新创建的 IPHostEntry-class 实例。

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) 方法

使用指定的 IP 地址创建一个新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 地址。 |

### 返回值

新创建的 IPHostEntry-class 实例。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPHostEntry](../../iphostentry/)
* 类 [String](../../../system/string/)
* 类 [Dns](../)
* 类 [IPAddress](../../ipaddress/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)