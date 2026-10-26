---
title: GetImages()
second_title: Aspose.Slides for C++ API 參考
description: 返回演示文稿所有投影片的縮圖 Image 物件。
type: docs
weight: 417
url: /zh-hant/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回演示文稿所有投影片的縮圖 Image 物件。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |

### 回傳值

Bitmap 物件。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) 方法

返回指定投影片的縮圖 Bitmap 物件。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，從 1 開始。 |

### 回傳值

Bitmap 物件。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回演示文稿所有投影片的縮圖 Image 物件，並使用自訂縮放比例。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 回傳值

Bitmap 物件。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) 方法

返回指定投影片的縮圖 Image 物件，並使用自訂縮放比例。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，從 1 開始。 |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 回傳值

Bitmap 物件。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回演示文稿所有投影片的縮圖 Image 物件，並使用指定的大小。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像大小。 |

### 回傳值

Bitmap 物件。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) 方法

返回指定投影片的縮圖 Image 物件，並使用指定的大小。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### 參數說明

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，從 1 開始。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像大小。 |

### 回傳值

Bitmap 物件。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)