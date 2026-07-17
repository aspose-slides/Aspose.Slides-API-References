---
title: GetImage()
second_title: Aspose.Slides for C++ API 参考
description: 返回具有自定义缩放的图像对象。
type: docs
weight: 105
url: /zh/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) 方法

返回具有自定义缩放的 Image 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | **float** | 用于在 x 轴方向缩放此 Thumbnail 的值。 |
| scaleY | **float** | 用于在 y 轴方向缩放此 Thumbnail 的值。 |

### 返回值

Image 对象 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() 方法

返回一个 Thumbnail Image 对象（实际大小的 20%）。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 返回值

Image 对象 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) 方法

返回具有指定大小的 Image 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像的大小。 |

### 返回值

Bitmap 对象。

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 方法

返回具有指定参数的 Thumbnail tiff Bitmap 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 选项。 |

### 返回值

Image 对象。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回一个 Thumbnail Bitmap 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |

### 返回值

Bitmap 对象。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回具有自定义缩放的 Thumbnail Bitmap 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| scaleX | **float** | 用于在 x 轴方向缩放此 Thumbnail 的值。 |
| scaleY | **float** | 用于在 y 轴方向缩放此 Thumbnail 的值。 |

### 返回值

Bitmap 对象。

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回具有指定大小的 Thumbnail Bitmap 对象。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像的大小。 |

### 返回值

Bitmap 对象。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [ISlide](../)
* 类 [Size](../../../system.drawing/size/)
* 类 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 类 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)