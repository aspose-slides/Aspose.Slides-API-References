---
title: GetEntity()
second_title: Aspose.Slides for C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 14
url: /zh/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) 方法

将 URI 映射到包含实际资源的对象。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 指向对象的绝对 URI。 |

### 返回值

如果资源无法流式传输，则返回 [System::IO::Stream](../../../system.io/stream/) 对象或 null。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 类 [HtmlExternalResolver](../)
* 命名空间 [Aspose::Slides::Import](../../)
* 库 [Aspose.Slides](../../../)