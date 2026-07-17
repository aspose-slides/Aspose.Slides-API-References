---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 IPAddress 类的实例。
type: docs
weight: 222
url: /zh/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) method

尝试将传入的字符串转换为 [IPAddress](../) 类的实例。

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | 要解析的字符串。 |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | 解析后对象将被分配的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [IPAddress](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)