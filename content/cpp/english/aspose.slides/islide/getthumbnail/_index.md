---
title: GetThumbnail()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Thumbnail Bitmap object with custom scaling.
type: docs
weight: 105
url: /aspose.slides/islide/getthumbnail/
---
## ISlide::GetThumbnail(float, float) method


Returns a Thumbnail Bitmap object with custom scaling.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

Deprecated
:   Use [GetImage(float scaleX, float scaleY)](../getimage/) method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail() method


Returns a Thumbnail Image object (20% of real size).

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail()=0
```


### Return Value

Bitmap object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

Deprecated
:   Use GetImage method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail(System::Drawing::Size) method


Returns a Thumbnail Bitmap object with specified size.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(System::Drawing::Size imageSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap object.

Deprecated
:   Use GetImage(Size imageSize) method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail(System::SharedPtr\<Export::ITiffOptions\>) method


Returns a Thumbnail tiff bitmap object with specified parameters.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff options. |

### Return Value

Bitmap object.

Deprecated
:   Use GetImage(ITiffOptions options) method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>) method


Returns a Thumbnail Bitmap object.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImage(IRenderingOptions options) method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Returns a Thumbnail Bitmap object with custom scaling.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImage(IRenderingOptions options, float scaleX, float scaleY) method instead. The method will be removed after release of version 24.7.

## ISlide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap object with specified size.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::ISlide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use GetImage(IRenderingOptions options, Size imageSize) method instead. The method will be removed after release of version 24.7.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)