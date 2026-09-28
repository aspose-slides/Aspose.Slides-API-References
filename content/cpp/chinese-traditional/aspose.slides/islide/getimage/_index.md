---
title: GetImage()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有自訂縮放的 Image 物件。
type: docs
weight: 105
url: /zh-hant/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) method

傳回具有自訂縮放的 Image 物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | **float** | 用於在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 用於在 y 軸方向上縮放此縮圖的值。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage() method

傳回一個縮圖 Image 物件（實際尺寸的 20%）。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) method

傳回具有指定尺寸的 Image 物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的圖像尺寸。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) method

傳回具有指定參數的縮圖 tiff 位圖物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 選項。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) method

傳回縮圖 Bitmap 物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering 選項。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

傳回具有自訂縮放的縮圖 Bitmap 物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering 選項。 |
| scaleX | **float** | 用於在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 用於在 y 軸方向上縮放此縮圖的值。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

傳回具有指定尺寸的縮圖 Bitmap 物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering 選項。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的圖像尺寸。 |

### 返回值

Image 物件 [IImage](../../iimage/)

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)