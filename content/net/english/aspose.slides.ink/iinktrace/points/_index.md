---
title: Points
second_title: Aspose.Sildes for .NET API Reference
description: Gets points for the IInkLine PointF Read-only.
type: docs
weight: 20
url: /aspose.slides.ink/iinktrace/points/
---

## IInkTrace.Points property

Gets points for the IInkLine PointF Read-only.

```csharp
public PointF[] Points { get; }
```

### Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
    PointF[] points = traces[0].Points;
}
```

### See Also

* interface [IInkTrace](../../iinktrace)
* namespace [Aspose.Slides.Ink](../../iinktrace)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
