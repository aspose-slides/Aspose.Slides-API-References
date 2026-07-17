---
title: IsBypassed()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个指示是否不应对指定主机使用代理的值。
type: docs
weight: 40
url: /zh/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) 方法

返回一个指示是否不应对指定主机使用代理的值。

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 要检查的主机 URI。 |

### 返回值

如果必须不使用代理服务器则返回 true，否则返回 false。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [IWebProxy](../)
* 命名空间 [System::Net](../../)
* Library [Aspose.Slides](../../../)