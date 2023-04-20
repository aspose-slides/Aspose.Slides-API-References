---
title: GetThumbnail()
second_title: Aspose.Slides for C++ API Reference
description: Returns a Thumbnail Bitmap object with custom scaling.
type: docs
weight: 144
url: /cpp/aspose.slides/slide/getthumbnail/
---
## Slide::GetThumbnail(float, float) method


Returns a Thumbnail Bitmap object with custom scaling.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap object.
## Remarks



The following example shows how to generate thumbnails from PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Create a full scale image
System::SharedPtr<System::Drawing::Bitmap> bmp = slide->GetThumbnail(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", System::Drawing::Imaging::ImageFormat::get_Jpeg());
```
 The following example shows how to converting slides to bitmap and saving the images in PNG. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converts the first slide in the presentation to a Bitmap object
System::SharedPtr<System::Drawing::Bitmap> bmp = pres->get_Slides()->idx_get(0)->GetThumbnail();

// Saves the image in the PNG format
bmp->Save(u"Slide_0.png", System::Drawing::Imaging::ImageFormat::get_Png());
```
 The following example shows how to convert PowerPoint PPT/PPTX to JPG. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& slide : pres->get_Slides())
{
    // Create a full scale image
    System::SharedPtr<System::Drawing::Bitmap> bmp = slide->GetThumbnail(1.0f, 1.0f);
    // Save the image to disk in JPEG format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", slide->get_SlideNumber()),
              System::Drawing::Imaging::ImageFormat::get_Jpeg());
}
```
 The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Define dimensions
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Get scaled values of X and Y
auto size = pres->get_SlideSize()->get_Size();
float scaleX = (float)(1.0 / size.get_Width()) * desiredX;
float scaleY = (float)(1.0 / size.get_Height()) * desiredY;
for (auto&& slide : System::IterateOver(pres->get_Slides()))
{
    // Create a full scale image
    System::SharedPtr<System::Drawing::Bitmap> bmp = slide->GetThumbnail(scaleX, scaleY);
    // Save the image to disk in JPEG format
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", slide->get_SlideNumber()),
              System::Drawing::Imaging::ImageFormat::get_Jpeg());
}
```

## Slide::GetThumbnail() method


Returns a Thumbnail Image object (20% of real size).

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail() override
```

## Slide::GetThumbnail(System::Drawing::Size) method


Returns a Thumbnail Bitmap object with specified size.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap object.
## Remarks



The following example shows how to converting slides to images with custom sizes using C#. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converts the first slide in the presentation to a Bitmap with the specified size
System::Drawing::Size size(1820, 1040)
System::SharedPtr<System::Drawing::Bitmap> bmp = pres->get_Slides()->idx_get(0)->GetThumbnail(size);

// Saves the image in the JPEG format
bmp->Save(u"Slide_0.jpg", System::Drawing::Imaging::ImageFormat::get_Jpeg());
```

## Slide::GetThumbnail(System::SharedPtr\<Export::ITiffOptions\>) method


Returns a Thumbnail tiff bitmap object with specified parameters.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::ITiffOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff options. |

### Return Value

Bitmap object.

## Slide::GetThumbnail(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>) method


Returns a Thumbnail Bitmap object.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |

### Return Value

Bitmap objects.

Deprecated
:   Use Slide.GetThumbnail(IRenderingOptions) instead. The method will be removed after release of version 21.4.

## Slide::GetThumbnail(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, float, float) method


Returns a Thumbnail Bitmap object with custom scaling.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, float scaleX, float scaleY) override
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
:   Use Slide.GetThumbnail(IRenderingOptions, float, float) instead. The method will be removed after release of version 21.4.

## Slide::GetThumbnail(System::SharedPtr\<Export::INotesCommentsLayoutingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap object with specified size.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::INotesCommentsLayoutingOptions> notesCommentsLayouting, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [System::SharedPtr](../../../system/sharedptr/)\<[Export::INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)\> | Options for notes and comments layouting. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

Deprecated
:   Use Slide.GetThumbnail(IRenderingOptions) instead. The method will be removed after release of version 21.4.

## Slide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>) method


Returns a Thumbnail Bitmap object.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |

### Return Value

Bitmap objects.

## Slide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Returns a Thumbnail Bitmap object with custom scaling.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| scaleX | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | **float** | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.
## Remarks



The following example shows how to converting slides With notes and comments to Images using C#. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Creates the rendering options
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Sets the position of the notes on the page
options->get_NotesCommentsLayouting()->set_NotesPosition(NotesPositions::BottomTruncated);
// Sets the position of the comments on the page
options->get_NotesCommentsLayouting()->set_CommentsPosition(CommentsPositions::Right);
// Sets the width of the comment output area
options->get_NotesCommentsLayouting()->set_CommentsAreaWidth(500);
// Sets the color for the comments area
options->get_NotesCommentsLayouting()->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Converts the first slide of the presentation to a Bitmap object
System::SharedPtr<System::Drawing::Bitmap> bmp = pres->get_Slides()->idx_get(0)->GetThumbnail(options, 2.0f, 2.0f);
// Saves the image in the GIF format
bmp->Save(u"Slide_Notes_Comments_0.gif", System::Drawing::Imaging::ImageFormat::get_Gif());
```

## Slide::GetThumbnail(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Returns a Thumbnail Bitmap object with specified size.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Slide::GetThumbnail(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering options. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Size of the image to create. |

### Return Value

Bitmap objects.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [INotesCommentsLayoutingOptions](../../../aspose.slides.export/inotescommentslayoutingoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)