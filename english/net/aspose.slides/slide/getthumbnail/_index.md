---
title: GetThumbnail
second_title: Aspose.Sildes for .NET API Reference
description: Returns a Thumbnail Bitmap object with custom scaling.
type: docs
weight: 90
url: /net/aspose.slides/slide/getthumbnail/
---
## GetThumbnail(float, float) {#getthumbnail_8}

Returns a Thumbnail Bitmap object with custom scaling.

```csharp
public Bitmap GetThumbnail(float scaleX, float scaleY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | Single | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | Single | The value by which to scale this Thumbnail in the y-axis direction. |

### Return Value

Bitmap object.

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
    Bitmap bmp = sld.GetThumbnail(1f, 1f);

    // Save the image to disk in JPEG format
    bmp.Save("Thumbnail_out.jpg", System.Drawing.Imaging.ImageFormat.Jpeg);

}
```

The following example shows how to converting slides to bitmap and saving the images in PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converts the first slide in the presentation to a Bitmap object
    using (Bitmap bmp = pres.Slides[0].GetThumbnail())
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
		Bitmap bmp = sld.GetThumbnail(1f, 1f);

		// Save the image to disk in JPEG format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
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
		Bitmap bmp = sld.GetThumbnail(ScaleX, ScaleY);

		// Save the image to disk in JPEG format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
	}
}
```

### See Also

* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail() {#getthumbnail}

Returns a Thumbnail Image object (20% of real size).

```csharp
public Bitmap GetThumbnail()
```

### See Also

* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail(Size) {#getthumbnail_9}

Returns a Thumbnail Bitmap object with specified size.

```csharp
public Bitmap GetThumbnail(Size imageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | Size | Size of the image to create. |

### Return Value

Bitmap object.

### Examples

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Now the second section contains a copy of the first slide.
}
```

The following example shows how to converting slides to images with custom sizes using C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converts the first slide in the presentation to a Bitmap with the specified size
    using (Bitmap bmp = pres.Slides[0].GetThumbnail(new Size(1820, 1040)))
    {
        // Saves the image in the JPEG format
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### See Also

* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail(ITiffOptions) {#getthumbnail_7}

Returns a Thumbnail tiff bitmap object with specified parameters.

```csharp
public Bitmap GetThumbnail(ITiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ITiffOptions | Tiff options. |

### Return Value

Bitmap object.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |

### Examples

The following example shows how to clone at end within a Presentation using C#.

```csharp
// Instantiate Presentation class that represents a presentation file
using (Presentation pres = new Presentation("CloneWithinSamePresentationToEnd.pptx"))
{

    // Clone the desired slide to the end of the collection of slides in the same presentation
    ISlideCollection slds = pres.Slides;

    slds.AddClone(pres.Slides[0]);

    // Write the modified presentation to disk
    pres.Save("Aspose_CloneWithinSamePresentationToEnd_out.pptx", SaveFormat.Pptx);

}
```

The following example shows how to clone at end in another Presentation using C#.

```csharp
// Instantiate Presentation class to load the source presentation file
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instantiate Presentation class for destination PPTX (where slide is to be cloned)
    using (Presentation destPres = new Presentation())
    {
        // Clone the desired slide from the source presentation to the end of the collection of slides in destination presentation
        ISlideCollection slds = destPres.Slides;

        slds.AddClone(srcPres.Slides[0]);

        // Write the destination presentation to disk
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

The following example shows how to converting slides With notes and comments to Images using C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Creates the rendering options
    IRenderingOptions options = new RenderingOptions();
                
    // Sets the position of the notes on the page
    options.NotesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
                
    // Sets the position of the comments on the page 
    options.NotesCommentsLayouting.CommentsPosition = CommentsPositions.Right;

    // Sets the width of the comment output area
    options.NotesCommentsLayouting.CommentsAreaWidth = 500;
                
    // Sets the color for the comments area
    options.NotesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
                
    // Converts the first slide of the presentation to a Bitmap object
    Bitmap bmp = pres.Slides[0].GetThumbnail(options, 2f, 2f);

    // Saves the image in the GIF format
    bmp.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### See Also

* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail(IRenderingOptions) {#getthumbnail_4}

Returns a Thumbnail Bitmap object.

```csharp
public Bitmap GetThumbnail(IRenderingOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Rendering options. |

### Return Value

Bitmap objects.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |

### See Also

* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail(IRenderingOptions, float, float) {#getthumbnail_5}

Returns a Thumbnail Bitmap object with custom scaling.

```csharp
public Bitmap GetThumbnail(IRenderingOptions options, float scaleX, float scaleY)
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

### See Also

* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetThumbnail(IRenderingOptions, Size) {#getthumbnail_6}

Returns a Thumbnail Bitmap object with specified size.

```csharp
public Bitmap GetThumbnail(IRenderingOptions options, Size imageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Rendering options. |
| imageSize | Size | Size of the image to create. |

### Return Value

Bitmap objects.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |

### See Also

* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
