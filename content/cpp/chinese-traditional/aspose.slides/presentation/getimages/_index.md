---
title: GetImages()
second_title: Aspose.Slides for C++ API 參考
description: 傳回簡報中所有投影片的 Image 物件。
type: docs
weight: 456
url: /zh-hant/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回一個 Image 物件，包含簡報的所有投影片。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |

### 返回值

Image 物件。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) 方法

返回指定投影片的縮圖 Image 物件。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，起始位置為 1。 |

### 返回值

Image 物件。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回所有投影片的縮圖 Image 物件，使用自訂縮放。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 返回值

Image 物件。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) 方法

返回指定投影片的縮圖 Image 物件，使用自訂縮放。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，起始位置為 1。 |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 返回值

Image 物件。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回所有投影片的縮圖 Image 物件，使用指定尺寸。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像尺寸。 |

### 返回值

Image 物件。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) 方法

返回指定投影片的縮圖 Image 物件，使用指定尺寸。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 選項。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含投影片位置的陣列，起始位置為 1。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像尺寸。 |

### 返回值

Image 物件。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImage](../../iimage/)
* 類別 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 類別 [Presentation](../)
* 類別 [Size](../../../system.drawing/size/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)