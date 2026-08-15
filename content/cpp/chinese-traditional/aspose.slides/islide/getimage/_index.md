---
title: GetImage()
second_title: Aspose.Slides C++ API 參考
description: 傳回具有自訂縮放的影像物件。
type: docs
weight: 105
url: /zh-hant/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) 方法

返回具有自訂縮放的影像物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 返回值

影像物件 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() 方法

返回縮圖影像物件（實際大小的 20%）。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 返回值

影像物件 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) 方法

返回具有指定大小的影像物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像大小。 |

### 返回值

位圖物件。

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 方法

返回具有指定參數的縮圖 TIFF 位圖物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 選項。 |

### 返回值

影像物件。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回縮圖位圖物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |

### 返回值

位圖物件。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回具有自訂縮放的縮圖位圖物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| scaleX | **float** | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | **float** | 在 y 軸方向上縮放此縮圖的值。 |

### 返回值

位圖物件。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回具有指定大小的縮圖位圖物件。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要建立的影像大小。 |

### 返回值

位圖物件。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IImage](../../iimage/)
* 類別 [ISlide](../)
* 類別 [Size](../../../system.drawing/size/)
* 類別 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 類別 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)