---
title: GetThumbnails()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Thumbnail Bitmap objects for all slides of a presentation.
type: docs
weight: 404
url: /cpp/aspose.slides/ipresentation/getthumbnails/
---
## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>) method


Returns a Thumbnail Bitmap objects for all slides of a presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |

### Return Value

Bitmap objects.

Deprecated
:   Use IPresentation.GetThumbnails(IRenderingOptions) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |

### Return Value

Bitmap objects.

Deprecated
:   Use IPresentation.GetThumbnails(IRenderingOptions, int[]) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, float, float) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, float scaleX, float scaleY)=0
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
:   Use IPresentation.GetThumbnails(IRenderingOptions, float, float) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
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
:   Use IPresentation.GetThumbnails(IRenderingOptions, int[], float, float) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::Drawing::Size imageSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use IPresentation.GetThumbnails(IRenderingOptions, Size) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
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
:   Use IPresentation.GetThumbnails(IRenderingOptions, int[], Size) instead. The method will be removed after release of version 21.4.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>) method


Returns a Thumbnail Bitmap objects for all slides of a presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |

### Return Value

Bitmap objects.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |

### Return Value

Bitmap objects.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

## IPresentation::GetThumbnails(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

```cpp
virtual System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> Aspose::Slides::IPresentation::GetThumbnails(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)