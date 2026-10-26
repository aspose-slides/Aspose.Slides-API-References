---
title: AddImage()
second_title: Aspose.Slides for C++ API 参考
description: 向演示文稿添加图像。
type: docs
weight: 14
url: /zh/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) 方法

向演示文稿添加图像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | 要添加的图像。 |

### 返回值

已添加的图像。

## 备注

此方法在插入演示文稿之前，将 WMF/EMF 元文件转换为光栅 PNG 图像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) 方法

从内存流添加图像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | 内存流。 |

### 返回值

已添加的图像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) 方法

从流向演示文稿添加图像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要添加图像的流。 |

### 返回值

已添加的图像。

## 备注

此方法可以将 WMF/EMF 元文件直接添加到演示文稿中，而无需将其转换为光栅 PNG 图像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法

从流创建并添加图像到演示文稿。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要添加图像文件的流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 将应用于该流的行为。 |

### 返回值

已添加 [IPPImage](../../ippimage/)。

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) 方法

从指定缓冲区向演示文稿添加图像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 缓冲区。 |

### 返回值

已添加的图像。

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) 方法

从另一个演示文稿中添加图像的副本。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 源图像。 |

### 返回值

已添加的图像。

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) 方法

从 SVG 对象向演示文稿添加图像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG 图像对象 [ISvgImage](../../isvgimage/) |

### 返回值

已添加的图像。

## 另请参阅

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)