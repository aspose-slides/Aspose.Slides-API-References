---  
title: Points
second_title: Aspose.Slides für .NET API Referenz  
description: Holt Punkte für das IInkLine PointF Nur-lesbar.
type: docs
weight: 20  
url: /de/aspose.slides.ink/inktrace/points/
---  

## InkTrace.Points-Eigenschaft  

Holt Punkte für das IInkLine PointF Nur-lesbar.  

```csharp  
public PointF[] Points { get; }  
```  

### Beispiele  

Beispiel:  

```csharp  
[C#]  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
    IInk ink = (IInk)pres.Slides[0].Shapes[0];  
    IInkTrace[] traces = ink.Traces;  
    PointF[] points = traces[0].Points;  
}  
```  

### Siehe auch  

* class [InkTrace](../../inktrace)  
* namespace [Aspose.Slides.Ink](../../inktrace)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  