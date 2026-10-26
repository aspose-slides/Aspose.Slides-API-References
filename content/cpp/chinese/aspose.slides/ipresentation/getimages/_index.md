---
title: GetImages()
second_title: Aspose.Slides for C++ API 参考
description: 为演示文稿的所有幻灯片返回缩略图 Image 对象。
type: docs
weight: 417
url: /zh/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) 方法

返回用于演示文稿所有幻灯片的缩略图 Image 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |

### 返回值

Bitmap 对象。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) 方法

返回用于演示文稿指定幻灯片的缩略图 Bitmap 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含幻灯片位置的数组，起始值为 1。 |

### 返回值

Bitmap 对象。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 方法

返回用于演示文稿所有幻灯片的自定义缩放缩略图 Image 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| scaleX | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | **float** | 在 y 轴方向上缩放此缩略图的值。 |

### 返回值

Bitmap 对象。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) 方法

返回用于演示文稿指定幻灯片的自定义缩放缩略图 Image 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含幻灯片位置的数组，起始值为 1。 |
| scaleX | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | **float** | 在 y 轴方向上缩放此缩略图的值。 |

### 返回值

Bitmap 对象。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 方法

返回用于演示文稿所有幻灯片、具有指定尺寸的缩略图 Image 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像尺寸。 |

### 返回值

Bitmap 对象。

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) 方法

返回用于演示文稿指定幻灯片、具有指定尺寸的缩略图 Image 对象。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 包含幻灯片位置的数组，起始值为 1。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像尺寸。 |

### 返回值

Bitmap 对象。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 类 [IPresentation](../)
* 类 [Size](../../../system.drawing/size/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)