---
title: AddTextFrame
second_title: Aspose.Sildes for .NET API Reference
description: Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text.
type: docs
weight: 60
url: /aspose.slides/autoshape/addtextframe/
---

## AutoShape.AddTextFrame method

Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text.

```csharp
public ITextFrame AddTextFrame(string text)
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | String | Default text for a new TextFrame. |

### Examples

The following sample code shows how to add watermark text in PowerPoint Presentation.

```csharp
[C#]
	using (var presentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
		ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
	}
```

The following example shows how to create Text Box on Slide.

```csharp
[C#]
// Instantiates Presentation
using (Presentation pres = new Presentation())
{
    // Gets the first slide in the presentation
    ISlide sld = pres.Slides[0];
    // Adds an AutoShape with type set as Rectangle
    IAutoShape ashp = sld.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
    // Adds TextFrame to the Rectangle
    ashp.AddTextFrame(" ");
    // Accesses the text frame
    ITextFrame txtFrame = ashp.TextFrame;
    // Creates the Paragraph object for text frame
    IParagraph para = txtFrame.Paragraphs[0];
    // Creates a Portion object for the paragraph
    IPortion portion = para.Portions[0];
    // Sets the text
    portion.Text = "Aspose TextBox";
    // Saves the presentation to disk
    pres.Save("TextBox_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

The following example shows how to add column in Text Box.

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
	// Gets the first slide in the presentation
	ISlide slide = presentation.Slides[0];
	// Add an AutoShape with type set as Rectangle
	IAutoShape aShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
	// Add TextFrame to the Rectangle
	aShape.AddTextFrame("All these columns are limited to be within a single text container -- " +
	"you can add or delete text and the new or remaining text automatically adjusts " +
	"itself to flow within the container. You cannot have text flow from one container " +
	"to other though -- we told you PowerPoint's column options for text are limited!");
	// Gets the text format of TextFrame
	ITextFrameFormat format = aShape.TextFrame.TextFrameFormat;
	// Specifies the number of columns in TextFrame
	format.ColumnCount = 3;
	// Specifies the spacing between columns
	format.ColumnSpacing = 10;
	// Saves the presentation
	presentation.Save("ColumnCount.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ITextFrame](../../itextframe)
* class [AutoShape](../../autoshape)
* namespace [Aspose.Slides](../../autoshape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
