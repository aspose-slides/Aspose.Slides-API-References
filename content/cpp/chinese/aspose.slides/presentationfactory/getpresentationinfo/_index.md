---
title: GetPresentationInfo()
second_title: Aspose.Slides C++ API 参考
description: 从文件创建新的 PresentationInfo 对象并将演示绑定到它。
type: docs
weight: 27
url: /zh/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) 方法

从文件创建新的 [PresentationInfo](../../presentationinfo/) 对象并将演示绑定到它。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 文件。 |

### 返回值

[Presentation](../../presentation/) 信息绑定到演示。

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 方法

从流创建新的 [PresentationInfo](../../presentationinfo/) 对象并将演示绑定到它。获取指定流中演示的信息。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 流。 |

### 返回值

[Presentation](../../presentation/) 信息绑定到演示。

## 参考

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPresentationInfo](../../ipresentationinfo/)
* 类 [String](../../../system/string/)
* 类 [PresentationFactory](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)