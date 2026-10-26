---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 参考
description: 从基 URI 和相对 URI 解析出绝对 URI。
type: docs
weight: 1
url: /zh/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri(System::String, System::String) 方法

从基 URI 和相对 URI 解析出绝对 URI。

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 链接对象的基 URI |
| relativeUri | [System::String](../../../system/string/) | 链接对象的相对 URI。 |

### 返回值

绝对 URI，若无法解析相对 URI 则返回 null。

## 另见

* 类 [String](../../../system/string/)
* 类 [ExternalResourceResolver](../)
* 命名空间 [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)