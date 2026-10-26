---
title: RegisterPrefix()
second_title: Aspose.Slides C++ API 参考
description: 为指定的 URI 注册 WebRequest 派生类。
type: docs
weight: 92
url: /zh/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) 方法

为指定的 URI 注册 [WebRequest](../) 派生类。

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI 或 URI 前缀。 |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | 创建 [WebRequest](../) 类的新实例。 |

### 返回值

成功为指定的 URI 注册 [WebRequest](../) 派生类时返回 true，否则返回 false。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [IWebRequestCreate](../../iwebrequestcreate/)
* 类 [WebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)