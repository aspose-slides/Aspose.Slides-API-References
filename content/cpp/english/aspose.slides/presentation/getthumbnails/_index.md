---
title: GetThumbnails()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Thumbnail Bitmap objects for all slides of a presentation.
type: docs
weight: 443
url: /aspose.slides/presentation/getthumbnails/
---
## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>) method


Returns a Thumbnail Bitmap objects for all slides of a presentation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options) method instead. The method will be removed after release of version 24.7.

## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options, int[] slides) method instead. The method will be removed after release of version 24.7.

## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options, float scaleX, float scaleY) method instead. The method will be removed after release of version 24.7.

## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) method instead. The method will be removed after release of version 24.7.

## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options, Size imageSize) method instead. The method will be removed after release of version 24.7.

## Presentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImages(IRenderingOptions options, int[] slides, Size imageSize) method instead. The method will be removed after release of version 24.7.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)