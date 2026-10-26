---
title: GetImages()
second_title: Aspose.Slides C++ API 参考
description: 返回演示文稿所有幻灯片的 Image 对象。
type: docs
weight: 456
url: /zh/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

返回 Image 对象，表示演示文稿的所有幻灯片。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |

### 返回值

Image 对象。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

返回 Thumbnail Image 对象，针对演示文稿中指定的幻灯片。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 幻灯片位置数组，起始索引为 1。 |

### 返回值

Image 对象。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

返回 Thumbnail Image 对象，针对演示文稿中所有幻灯片，并使用自定义缩放。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |
| scaleX | **float** | 在 x 轴方向上缩放此 Thumbnail 的比例值。 |
| scaleY | **float** | 在 y 轴方向上缩放此 Thumbnail 的比例值。 |

### 返回值

Image 对象。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

返回 Thumbnail Image 对象，针对演示文稿中指定的幻灯片，并使用自定义缩放。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 幻灯片位置数组，起始索引为 1。 |
| scaleX | **float** | 在 x 轴方向上缩放此 Thumbnail 的比例值。 |
| scaleY | **float** | 在 y 轴方向上缩放此 Thumbnail 的比例值。 |

### 返回值

Image 对象。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

返回 Thumbnail Image 对象，针对演示文稿中所有幻灯片，并使用指定尺寸。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像大小。 |

### 返回值

Image 对象。

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

返回 Thumbnail Image 对象，针对演示文稿中指定的幻灯片，并使用指定尺寸。

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 选项。 |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 幻灯片位置数组，起始索引为 1。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 要创建的图像大小。 |

### 返回值

Image 对象。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IImage](../../iimage/)
* 类 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 类 [Presentation](../)
* 类 [Size](../../../system.drawing/size/)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)