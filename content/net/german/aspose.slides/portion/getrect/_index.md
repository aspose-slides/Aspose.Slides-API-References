---
title: GetRect
second_title: Aspose.Slides für .NET API-Referenz
description: Erhalten Sie die Koordinaten des Rechtecks, das die Portion umschließt. Das Rechteck umfasst alle Textzeilen in der Portion, einschließlich leerer Zeilen.
type: docs
weight: 70
url: /de/aspose.slides/portion/getrect/
---

## Portion.GetRect-Methode

Erhalten Sie die Koordinaten des Rechtecks, das die Portion umschließt. Das Rechteck umfasst alle Textzeilen in der Portion, einschließlich leerer Zeilen.

```csharp
public RectangleF GetRect()
```

### Beispiele

Beispiel:

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

### Siehe auch

* Klasse [Portion](../../portion)
* Namespace [Aspose.Slides](../../portion)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->