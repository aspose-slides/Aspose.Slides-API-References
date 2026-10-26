---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，从基 URI 和相对 URI 解析出绝对 URI。
type: docs
weight: 27
url: /zh/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

当在派生类中重写时，从基 URI 和相对 URI 解析出绝对 URI。

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于解析相对 URI 的基 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。该 URI 可以是绝对的也可以是相对的。如果是绝对的，则此值实际上会替代 **baseUri** 的值；如果是相对的，则它会与 **baseUri** 组合生成绝对 URI。 |

### 返回值

绝对 URI，或如果相对 URI 无法解析则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [XmlResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)