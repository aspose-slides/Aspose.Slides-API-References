---
title: GetRect
second_title: Aspose.Sildes for .NET API Reference
description: Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion including empty ones.
type: docs
weight: 70
url: /aspose.slides/iportion/getrect/
---

## IPortion.GetRect method

Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones.

```csharp
public RectangleF GetRect()
```

### Return Value

Rectangle that bounds portion RectangleF

### Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation())

   ISlide slide = pres.Slides[0];
   IAutoShape shape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);

   shape.TextFrame.Paragraphs[0].Portions.Clear();
   var portion0 = new Portion("Some text");
   var portion1 = new Portion("GetRect text");

   shape.TextFrame.Paragraphs[0].Portions.Add(portion0);
   shape.TextFrame.Paragraphs[0].Portions.Add(portion1);

   RectangleF rect = shape.TextFrame.Paragraphs[0].Portions[1].GetRect();
   ...

```

### See Also

* interface [IPortion](../../iportion)
* namespace [Aspose.Slides](../../iportion)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
