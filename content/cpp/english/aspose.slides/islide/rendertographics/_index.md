---
title: RenderToGraphics()
second_title: Aspose.Slides for C++ API Reference
description: Renders certain slide to a Graphics object.
type: docs
weight: 118
url: /aspose.slides/islide/rendertographics/
---
## ISlide::RenderToGraphics(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, int32_t, int32_t) method


Renders certain slide to a Graphics object.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::SharedPtr<System::Drawing::Graphics> graphics, int32_t width, int32_t height)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| width | **int32_t** | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | **int32_t** | The maximum height (in pixels) that can be occupied by the rendered slide. |

Deprecated
:   Use ISlide.RenderToGraphics(IRenderingOptions, Graphics, int, int) instead. The method will be removed after release of version 21.4.

## ISlide::RenderToGraphics(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, float) method


Renders certain slide to a Graphics object.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::SharedPtr<System::Drawing::Graphics> graphics, float scale)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| scale | **float** | The scale for rendering the slide (1.0 is 100%). |

Deprecated
:   Use ISlide.RenderToGraphics(IRenderingOptions, Graphics, float) instead. The method will be removed after release of version 21.4.

## ISlide::RenderToGraphics(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>) method


Renders certain slide to a Graphics object.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::SharedPtr<System::Drawing::Graphics> graphics)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |

Deprecated
:   Use ISlide.RenderToGraphics(IRenderingOptions, Graphics) instead. The method will be removed after release of version 21.4.

## ISlide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>) method


Renders certain slide to a Graphics object.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |

## ISlide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, float, float) method


Renders certain slide to a Graphics object with custom scaling.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics, float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| scaleX | **float** | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | **float** | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

## ISlide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, System::Drawing::Size) method


Renders certain slide to a Graphics object using specified size.

```cpp
virtual void Aspose::Slides::ISlide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics, System::Drawing::Size renderingSize)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| renderingSize | [System::Drawing::Size](../../../system.drawing/size/) | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)
* Class [Graphics](../../../system.drawing/graphics/)
* Class [ISlide](../)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)