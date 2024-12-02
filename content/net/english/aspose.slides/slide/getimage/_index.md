---
title: GetImage
second_title: Aspose.Sildes for .NET API Reference
description: Returns a Thumbnail Image object with custom scaling.
type: docs
weight: 80
url: /aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

Returns a Thumbnail Image object with custom scaling.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | Single | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | Single | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

IImage object.

### Examples

The following example shows how to generate thumbnails from PowerPoint Presentation.

```csharp
[C#]
// Instantiate a Presentation class that represents the presentation file
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Access the first slide
    ISlide sld = pres.Slides[0];
    // Create a full scale image
    IImage bmp = sld.GetImage(1f, 1f);
    // Save the image to disk in JPEG format
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

The following example shows how to converting slides to bitmap and saving the images in PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converts the first slide in the presentation to a Bitmap object
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Saves the image in the PNG format
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

The following example shows how to convert PowerPoint PPT/PPTX to JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Create a full scale image
		IImage bmp = sld.GetImage(1f, 1f);
		// Save the image to disk in JPEG format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Define dimensions
	int desiredX = 1200;
	int desiredY = 800;
	// Get scaled values of X and Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Create a full scale image
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Save the image to disk in JPEG format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### See Also

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Returns a Thumbnail Image object (20% of real size).

```csharp
public IImage GetImage()
```

### See Also

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Returns a Thumbnail Image object with specified size.

```csharp
public IImage GetImage(Size imageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | Size | Size of the image to create. |

### Return Value

Image object.

### Examples

The following example shows how to converting slides to images with custom sizes using C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converts the first slide in the presentation to a Bitmap with the specified size
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Saves the image in the JPEG format
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### See Also

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Returns a Thumbnail tiff image object with specified parameters.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ITiffOptions | Tiff options. |

### Return Value

Image object.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when options.SlideLayoutOption is NotesCommentsLayoutingOptions and its property NotesPosition takes the value NotesPositions.BottomFull. |

### See Also

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Returns a Thumbnail Image object.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Rendering options. |

### Return Value

Image object.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |

### See Also

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Returns a Thumbnail Image object with custom scaling.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Rendering options. |
| scaleX | Single | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | Single | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap objects.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |

### Examples

The following example shows how to converting slides With notes and comments to Images using C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Create the rendering options
    IRenderingOptions options = new RenderingOptions();
    // Create notes and comments layouting options
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Sets the position of the notes on the page
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Sets the position of the comments on the page
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Sets the width of the comment output area
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Sets the color for the comments area
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Set layout options for rendering
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Converts the first slide of the presentation to a IImage object
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Saves the image in the GIF format
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### See Also

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Returns a Thumbnail Image object with specified size.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Rendering options. |
| imageSize | Size | Size of the image to create. |

### Return Value

Image object.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when options.SlideLayoutOption is NotesCommentsLayoutingOptions and its property NotesPosition takes the value NotesPositions.BottomFull. |

### See Also

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
