---
title: RenderToGraphics()
second_title: Aspose.Slides for C++ API Reference
description: Renders certain slide to a Graphics object.
type: docs
weight: 170
url: /aspose.slides/slide/rendertographics/
---
## Slide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>) method


Renders certain slide to a Graphics object.

```cpp
void Aspose::Slides::Slide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |

Deprecated
:   The method will be removed after release of version 24.7.

## Slide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, float, float) method


Renders certain slide to a Graphics object with custom scaling.

```cpp
void Aspose::Slides::Slide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| scaleX | **float** | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | **float** | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

Deprecated
:   The method will be removed after release of version 24.7.

## Slide::RenderToGraphics(System::SharedPtr\<Export::IRenderingOptions\>, System::SharedPtr\<System::Drawing::Graphics\>, System::Drawing::Size) method


Renders certain slide to a Graphics object using specified size.

```cpp
void Aspose::Slides::Slide::RenderToGraphics(System::SharedPtr<Export::IRenderingOptions> options, System::SharedPtr<System::Drawing::Graphics> graphics, System::Drawing::Size renderingSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| graphics | [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::Graphics](../../../system.drawing/graphics/)\> | The object where to render to. |
| renderingSize | [System::Drawing::Size](../../../system.drawing/size/) | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |
## Remarks


Deprecated
:   The method will be removed after release of version 24.7.


The following example shows how to convert the first slide to the framed image with the RenderToGraphics method. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto slide = pres->get_Slides()->idx_get(0);

System::Drawing::Size slideSize(1820, 1040);
// Creates a Bitmap with the specified size (slide size + fields)
auto slideImage = System::MakeObject<System::Drawing::Bitmap>(slideSize.get_Width() + 50, slideSize.get_Height() + 50);

System::SharedPtr<System::Drawing::Graphics> graphics = System::Drawing::Graphics::FromImage(slideImage);

// Fills and translates Graphics to create a frame around the slide
graphics->Clear(System::Drawing::Color::get_Red());
graphics->TranslateTransform(25.0f, 25.0f);
// Renders the first slide to Graphics
slide->RenderToGraphics(System::MakeObject<RenderingOptions>(), graphics, slideSize);

// Saves the image in the JPEG format
slideImage->Save(u"FramedSlide_0.jpg", System::Drawing::Imaging::ImageFormat::get_Jpeg());
```
 The following example shows how to conversion process for a slide with notes using the RenderToGraphics. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationNotes.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Gets the presentation notes size
System::Drawing::Size notesSize = pres->get_NotesSize()->get_Size().ToSize();
// Creates the rendering options
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Sets the position of the notes
options->get_NotesCommentsLayouting()->set_NotesPosition(NotesPositions::BottomTruncated);
// Creates a Bitmap with the notes' size
System::SharedPtr<System::Drawing::Bitmap> slideImage = System::MakeObject<System::Drawing::Bitmap>(notesSize.get_Width(), notesSize.get_Height());

// Renders the first slide to Graphics
System::SharedPtr<System::Drawing::Graphics> graphics = System::Drawing::Graphics::FromImage(slideImage);

slide->RenderToGraphics(options, graphics, notesSize);

// Saves the image in PNG format
slideImage->Save(u"Slide_Notes_0.png", System::Drawing::Imaging::ImageFormat::get_Png());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Graphics](../../../system.drawing/graphics/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)