---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 参考
description: 从基 URI 和相对 URI 解析出绝对 URI。
type: docs
weight: 1
url: /zh/aspose.slides.import/htmlexternalresolver/resolveuri/
---
## HtmlExternalResolver::ResolveUri(System::String, System::String) 方法

从基 URI 和相对 URI 解析出绝对 URI。

```cpp
System::String Aspose::Slides::Import::HtmlExternalResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 链接对象的基 URI |
| relativeUri | [System::String](../../../system/string/) | 指向链接对象的相对 URI |

### 返回值

如果无法解析相对 URI，则返回绝对 URI 或 null。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [HtmlExternalResolver](../)
* 命名空间 [Aspose::Slides::Import](../../)
* 库 [Aspose.Slides](../../../)