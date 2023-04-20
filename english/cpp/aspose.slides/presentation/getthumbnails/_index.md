---
title: GetThumbnails()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Thumbnail Bitmap objects for all slides of a presentation.
type: docs
weight: 443
url: /cpp/aspose.slides/presentation/getthumbnails/
---
## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>) method


Returns a Thumbnail Bitmap objects for all slides of a presentation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions) instead. The method will be removed after release of version 21.4.

## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions, int[]) instead. The method will be removed after release of version 21.4.

## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, float, float) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions, float, float) instead. The method will be removed after release of version 21.4.

## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions, int[], float, float) instead. The method will be removed after release of version 21.4.

## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions, Size) instead. The method will be removed after release of version 21.4.

## Presentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

```cpp
System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::Presentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use Presentation.GetThumbnails(IRenderingOptions, int[], Size) instead. The method will be removed after release of version 21.4.

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

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)