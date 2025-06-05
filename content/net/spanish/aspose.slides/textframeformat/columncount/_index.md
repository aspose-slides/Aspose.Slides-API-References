---
title: ColumnCount
second_title: Referencia de API de Aspose.Sildes para .NET
description: Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Lectura/escritura Int32.
type: docs
weight: 50
url: /es/aspose.slides/textframeformat/columncount/
---

## Propiedad TextFrameFormat.ColumnCount

Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Lectura/escritura Int32.

```csharp
public int ColumnCount { get; set; }
```

### Ejemplos

El siguiente código de ejemplo muestra cómo agregar columnas en un marco de texto dentro de una presentación de PowerPoint.

```csharp
[C#]
string outPptxFileName = "ColumnsTest.pptx";
using (Presentation pres = new Presentation())
{
    IAutoShape shape1 = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
    TextFrameFormat format = (TextFrameFormat)shape1.TextFrame.TextFrameFormat;
    format.ColumnCount = 2;
    shape1.TextFrame.Text = "Todas estas columnas están obligadas a permanecer dentro de un solo contenedor de texto -- " +
                                "puedes agregar o eliminar texto - y el nuevo texto o el texto restante se ajusta " +
                                "automáticamente para permanecer dentro del contenedor. No puedes tener texto que se desborde de un contenedor " +
                                "a otro, sin embargo, porque las opciones de columnas de PowerPoint para texto son limitadas!";
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(2 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(double.NaN == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
    format.ColumnSpacing = 20;
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(2 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(20 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
    format.ColumnCount = 3;
    format.ColumnSpacing = 15;
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(3 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(15 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
}
```

### Véase también

* clase [TextFrameFormat](../../textframeformat)
* espacio de nombres [Aspose.Slides](../../textframeformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->