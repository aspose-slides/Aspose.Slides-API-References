---
title: GetEntity()
second_title: Aspose.Slides for C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 14
url: /zh/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) 方法

将 URI 映射到包含实际资源的对象。

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 对象的绝对 URI。 |

### 返回值

一个 [System::IO::Stream](../../../system.io/stream/) 对象，如果资源无法流式传输则为 null。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 类 [IExternalResourceResolver](../)
* 命名空间 [Aspose::Slides::Import](../../)
* 库 [Aspose.Slides](../../../)