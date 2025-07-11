---
title: Alignment
second_title: Aspose.Sildes para .NET API Reference
description: Devuelve o establece la alineación de texto en un párrafo sin herencia. Lectura/escritura TextAlignmentaspose.slides/textalignment.
type: docs
weight: 20
url: /es/aspose.slides/paragraphformat/alignment/
---

## Propiedad ParagraphFormat.Alignment

Devuelve o establece la alineación de texto en un párrafo sin herencia. Lectura/escritura [`TextAlignment`](../../textalignment).

```csharp
public TextAlignment Alignment { get; set; }
```

### Ejemplos

El siguiente código de muestra muestra cómo alinear párrafos de texto en una presentación de PowerPoint.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo PPTX
using (Presentation pres = new Presentation("ParagraphsAlignment.pptx"))
{
    // Accediendo a la primera diapositiva
    ISlide slide = pres.Slides[0];
    // Accediendo al primer y segundo marcador de posición en la diapositiva y convirtiéndolo en AutoShape
    ITextFrame tf1 = ((IAutoShape)slide.Shapes[0]).TextFrame;
    ITextFrame tf2 = ((IAutoShape)slide.Shapes[1]).TextFrame;
    // Cambiar el texto en ambos marcadores de posición
    tf1.Text = "Alinear al Centro por Aspose";
    tf2.Text = "Alinear al Centro por Aspose";
    // Obtener el primer párrafo de los marcadores de posición
    IParagraph para1 = tf1.Paragraphs[0];
    IParagraph para2 = tf2.Paragraphs[0];
    // Alineando el párrafo de texto al centro
    para1.ParagraphFormat.Alignment = TextAlignment.Center;
    para2.ParagraphFormat.Alignment = TextAlignment.Center;
    // Guardar la presentación como un archivo PPTX
    pres.Save("Centeralign_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* enum [TextAlignment](../../textalignment)
* class [ParagraphFormat](../../paragraphformat)
* namespace [Aspose.Slides](../../paragraphformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->