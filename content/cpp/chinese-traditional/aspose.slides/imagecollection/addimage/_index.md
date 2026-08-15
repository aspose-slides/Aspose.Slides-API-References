---
title: AddImage()
second_title: Aspose.Slides for C++ API 參考
description: 從另一個簡報中添加圖像的副本。
type: docs
weight: 53
url: /zh-hant/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) 方法

從另一個簡報中添加圖像的副本。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Source image. |

### 返回值

已添加圖像。

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) 方法

將圖像添加至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Image to add. |

### 返回值

已添加圖像。

## 備註

此方法會在插入簡報之前，將 WMF/EMF 中繪圖檔轉換為光柵 PNG 圖像。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) 方法

從串流將圖像添加至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Stream to add image from. |

### 返回值

已添加圖像。

## 備註

此方法可將 WMF/EMF 中繪圖檔直接添加至簡報，而無需轉換為光柵 PNG 圖像。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) 方法

從串流將圖像添加至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image from. |

### 返回值

已添加圖像。

## 備註

此方法可將 WMF/EMF 中繪圖檔直接添加至簡報，而無需轉換為光柵 PNG 圖像。

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法

從串流建立並添加圖像至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add image file from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### 返回值

已添加 [IPPImage](../../ippimage/)。

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) 方法

從指定緩衝區將圖像添加至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 緩衝區。 |

### 返回值

已添加圖像。

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) 方法

從 Svg 物件將圖像添加至簡報。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg 圖像物件 [ISvgImage](../../isvgimage/) |

### 返回值

已添加圖像。

## 另請參閱

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)