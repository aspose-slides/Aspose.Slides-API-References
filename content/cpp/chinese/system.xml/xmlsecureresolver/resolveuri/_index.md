---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 参考
description: 通过在底层 XmlResolver 上调用 ResolveUri，解析基 URI 和相对 URI 的绝对 URI。
type: docs
weight: 40
url: /zh/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

通过在底层 [XmlResolver](../../xmlresolver/) 上调用 **ResolveUri** 来解析基 URI 和相对 URI 的绝对 URI。

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于解析相对 URI 的基 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。该 URI 可以是绝对的或相对的。如果为绝对，则此值有效地替代 **baseUri** 的值。如果为相对，则它与 **baseUri** 组合生成一个绝对 URI。 |

### 返回值

如果相对 URI 无法解析，则返回绝对 URI 或 **nullptr**（通过在底层 [XmlResolver](../../xmlresolver/) 上调用 **ResolveUri** 返回）。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [XmlSecureResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)