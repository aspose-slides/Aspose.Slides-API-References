---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 参考
description: 根据基 URI 和相对 URI 解析出绝对 URI。
type: docs
weight: 66
url: /zh/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

根据基 URI 和相对 URI 解析出绝对 URI。

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 解析相对 URI 所使用的基 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。该 URI 可以是绝对的也可以是相对的。如果是绝对的，则此值实际替代 **baseUri** 的值。如果是相对的，则它与 **baseUri** 结合以生成绝对 URI。 |

### 返回值

绝对 URI，若相对 URI 无法解析则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [XmlUrlResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)