---
title: AddImage()
second_title: Aspose.Slides for C++ API 參考文件
description: 將影像新增至簡報。
type: docs
weight: 14
url: /zh-hant/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) 方法

將影像新增至簡報。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | 要新增的影像。 |

### 返回值

已新增的影像。

## 備註


此方法會在插入至簡報之前，將 WMF/EMF 中繪圖檔轉換為光柵 PNG 影像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) 方法


從記憶體串流新增影像。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | 記憶體串流。 |

### 返回值

已新增的影像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) 方法


從串流將影像新增至簡報。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要從中新增影像的串流。 |

### 返回值

已新增的影像。

## 備註


此方法可將 WMF/EMF 中繪圖檔直接新增至簡報，而不轉換為光柵 PNG 影像。

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 方法


從串流建立並將影像新增至簡報。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要從中新增影像檔的串流。 |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 將套用於串流的行為。 |

### 返回值

已新增 [IPPImage](../../ippimage/)。

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) 方法


從指定緩衝區將影像新增至簡報。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 緩衝區。 |

### 返回值

已新增的影像。

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) 方法


從另一份簡報複製影像並新增。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 來源影像。 |

### 返回值

已新增的影像。

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) 方法


從 SVG 物件將影像新增至簡報。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```


### 參數說明

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG 影像物件 [ISvgImage](../../isvgimage/) |

### 返回值

已新增的影像。

## 另請參閱

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