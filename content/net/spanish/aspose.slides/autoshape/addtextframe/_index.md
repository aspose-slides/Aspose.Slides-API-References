---
title: AddTextFrame
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega un nuevo TextFrame a una forma. Si la forma ya tiene TextFrame, simplemente cambia su texto.
type: docs
weight: 60
url: /es/aspose.slides/autoshape/addtextframe/
---

## Método AutoShape.AddTextFrame

Agrega un nuevo TextFrame a una forma. Si la forma ya tiene TextFrame, simplemente cambia su texto.

```csharp
public ITextFrame AddTextFrame(string text)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | String | Texto predeterminado para un nuevo TextFrame. |

### Ejemplos

El siguiente código de ejemplo muestra cómo agregar texto de marca de agua en una presentación de PowerPoint.

```csharp
[C#]
	using (var presentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
		ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
	}
```

El siguiente ejemplo muestra cómo crear un cuadro de texto en una diapositiva.

```csharp
[C#]
// Instancia la Presentación
using (Presentation pres = new Presentation())
{
    // Obtiene la primera diapositiva en la presentación
    ISlide sld = pres.Slides[0];
    // Agrega un AutoShape con tipo establecido como Rectángulo
    IAutoShape ashp = sld.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
    // Agrega TextFrame al Rectángulo
    ashp.AddTextFrame(" ");
    // Accede al marco de texto
    ITextFrame txtFrame = ashp.TextFrame;
    // Crea el objeto Paragraph para el marco de texto
    IParagraph para = txtFrame.Paragraphs[0];
    // Crea un objeto Portion para el párrafo
    IPortion portion = para.Portions[0];
    // Establece el texto
    portion.Text = "Aspose TextBox";
    // Guarda la presentación en el disco
    pres.Save("TextBox_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo agregar columnas en un cuadro de texto.

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
	// Obtiene la primera diapositiva en la presentación
	ISlide slide = presentation.Slides[0];
	// Agrega un AutoShape con tipo establecido como Rectángulo
	IAutoShape aShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
	// Agrega TextFrame al Rectángulo
	aShape.AddTextFrame("Todas estas columnas están limitadas a estar dentro de un solo contenedor de texto -- " +
	"puedes agregar o eliminar texto y el nuevo o restante texto se ajusta automáticamente " +
	"para fluir dentro del contenedor. No puedes hacer que el texto fluya de un contenedor " +
	"a otro -- ¡te dijimos que las opciones de columna de PowerPoint para texto son limitadas!");
	// Obtiene el formato de texto de TextFrame
	ITextFrameFormat format = aShape.TextFrame.TextFrameFormat;
	// Especifica el número de columnas en TextFrame
	format.ColumnCount = 3;
	// Especifica el espaciado entre columnas
	format.ColumnSpacing = 10;
	// Guarda la presentación
	presentation.Save("ColumnCount.pptx", SaveFormat.Pptx);
}
```

### Véase también

* interfaz [ITextFrame](../../itextframe)
* clase [AutoShape](../../autoshape)
* espacio de nombres [Aspose.Slides](../../autoshape)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->