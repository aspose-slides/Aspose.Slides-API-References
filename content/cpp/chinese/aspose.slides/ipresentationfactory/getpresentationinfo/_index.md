---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定文件中演示文稿的信息。
type: docs
weight: 14
url: /zh/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) 方法

获取指定文件中演示文稿的信息。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 文件。 |

### 返回值

[Presentation](../../presentation/) 信息

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 方法

获取指定流中演示文稿的信息。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 流。 |

### 返回值

[Presentation](../../presentation/) 信息。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPresentationInfo](../../ipresentationinfo/)
* 类 [String](../../../system/string/)
* 类 [IPresentationFactory](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)