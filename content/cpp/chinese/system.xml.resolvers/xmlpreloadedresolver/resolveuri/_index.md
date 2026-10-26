---
title: ResolveUri()
second_title: Aspose.Slides C++ API 参考
description: 从基础和相对 URI 解析出绝对 URI。
type: docs
weight: 40
url: /zh/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) 方法

从基础 URI 和相对 URI 解析出绝对 URI。

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用于解析相对 URI 的基础 URI。 |
| relativeUri | [String](../../../system/string/) | 要解析的 URI。该 URI 可以是绝对的或相对的。如果是绝对的，则此值会有效地替换 **baseUri** 的值。如果是相对的，则它会与 **baseUri** 组合形成绝对 URI。 |

### 返回值

表示绝对 URI 的 [Uri](../../../system/uri/)，如果相对 URI 无法解析则为 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [XmlPreloadedResolver](../)
* 命名空间 [System::Xml::Resolvers](../../)
* 库 [Aspose.Slides](../../../)