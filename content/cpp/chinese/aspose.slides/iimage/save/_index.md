---
title: Save()
second_title: Aspose.Slides C++ API 参考
description: 将图像保存到文件。
type: docs
weight: 40
url: /zh/aspose.slides/iimage/save/
---
## IImage::Save(System::String) 方法


将图像保存到文件。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 图像将被保存的文件路径。 |

## IImage::Save(System::String, ImageFormat) 方法


将图像以指定格式保存到文件。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 图像将被保存的文件路径。 |
| format | [ImageFormat](../../imageformat/) | 图像格式。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) 方法


将图像以指定格式保存到流。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 图像将被保存的流。 |
| format | [ImageFormat](../../imageformat/) | 图像格式。 |

## IImage::Save(System::String, ImageFormat, int32_t) 方法


将图像以指定格式和质量保存到文件。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 图像将被保存的文件路径。 |
| format | [ImageFormat](../../imageformat/) | 图像格式。 |
| quality | **int32_t** | 已保存图像的质量（0 到 100）。 

 此参数仅在 [ImageFormat::Jpeg](../../imageformat/) 中生效；对所有其他格式将被忽略。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) 方法


将图像以指定格式和质量保存到流。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 图像将被保存的流。 |
| format | [ImageFormat](../../imageformat/) | 图像格式。 |
| quality | **int32_t** | 已保存图像的质量（0 到 100）。 

 此参数仅在 [ImageFormat::Jpeg](../../imageformat/) 中生效；对所有其他格式将被忽略。 |

## 另请参见

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)