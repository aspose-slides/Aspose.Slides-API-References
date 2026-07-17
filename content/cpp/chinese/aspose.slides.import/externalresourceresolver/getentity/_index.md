---
title: GetEntity()
second_title: Aspose.Slides for C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 14
url: /zh/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) method

将 URI 映射到包含实际资源的对象。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 对象的绝对 URI。 |

### 返回值

[System::IO::Stream](../../../system.io/stream/) 对象，若资源无法流式传输则为 null。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 类 [ExternalResourceResolver](../)
* 命名空间 [Aspose::Slides::Import](../../)
* 库 [Aspose.Slides](../../../)