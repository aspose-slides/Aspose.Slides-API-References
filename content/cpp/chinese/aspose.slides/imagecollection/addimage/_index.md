---
title: AddImage()
second_title: Aspose.Slides C++ API 参考
description: 从另一个演示文稿添加图像的副本。
type: docs
weight: 53
url: /zh/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) 方法


Adds a copy of an image from an another presentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 源图像。 |

### 返回值

已添加的图像。

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) 方法


Add an image to a presentation.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | 要添加的图像。 |

### 返回值

已添加的图像。

## 备注


此方法在插入到演示文稿之前，会将 WMF/EMF 元文件转换为栅格 PNG 图像。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) 方法


Add an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | 用于添加图像的流。 |

### 返回值

已添加的图像。

## 备注


此方法可以在不将 WMF/EMF 元文件转换为栅格 PNG 图像的情况下，将其添加到演示文稿中。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) 方法


Add an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用于添加图像的流。 |

### 返回值

已添加的图像。

## 备注


此方法可以在不将 WMF/EMF 元文件转换为栅格 PNG 图像的情况下，将其添加到演示文稿中。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法


Creates and adds an image to a presentation from stream.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 用于添加图像文件的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于流的行为。 |

### 返回值

已添加 [IPPImage](../../ippimage/)。

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) 方法


Adds an image to a presentation from specified buffer.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 缓冲区。 |

### 返回值

已添加的图像。

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) 方法


Add an image to a presentation from Svg object.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg 图像对象 [ISvgImage](../../isvgimage/) |

### 返回值

已添加的图像。

## 另请参阅

* 枚举 [LoadingStreamBehavior](../../loadingstreambehavior/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IPPImage](../../ippimage/)
* 类 [ImageCollection](../)
* 类 [IImage](../../iimage/)
* 类 [MemoryStream](../../../system.io/memorystream/)
* 类 [Stream](../../../system.io/stream/)
* 类 [ISvgImage](../../isvgimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)