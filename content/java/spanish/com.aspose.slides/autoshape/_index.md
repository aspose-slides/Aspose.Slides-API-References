---
title: AutoShape
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una AutoShape.
type: docs
url: /es/com.aspose.slides/autoshape/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas las interfaces implementadas:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Representa una AutoShape.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de la forma. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Devuelve los bloqueos de la autoshape. |
| [getTextFrame()](#getTextFrame--) | Devuelve el objeto TextFrame para la AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina si esta autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina si esta autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Agrega un nuevo TextFrame a una forma. |
| [isTextBox()](#isTextBox--) | Especifica si la forma es un cuadro de texto. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Devuelve los bloqueos de la forma. Solo de lectura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Devuelve:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Devuelve los bloqueos de la autoshape. Solo de lectura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Devuelve:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Devuelve el objeto TextFrame para la AutoShape. Solo de lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Determina si esta autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Determina si esta autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Agrega un nuevo TextFrame a una forma. Si la forma ya tiene un TextFrame, simplemente cambia su texto.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Instancia la presentación
>  Presentation pres = new Presentation();
>  try {
>      // Obtiene la primera diapositiva de la presentación
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Agrega una AutoShape con tipo establecido como Rectángulo
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Agrega TextFrame al rectángulo
>      ashp.addTextFrame(" ");
>      // Accede al marco de texto
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Crea el objeto Paragraph para el marco de texto
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Crea un objeto Portion para el párrafo
>      IPortion portion = para.getPortions().get_Item(0);
>      // Establece el texto
>      portion.setText("Aspose TextBox");
>      // Guarda la presentación en disco
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Obtiene la primera diapositiva de la presentación
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Agrega una AutoShape con tipo establecido como Rectángulo
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Agrega TextFrame al rectángulo
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Obtiene el formato de texto del TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Especifica el número de columnas en el TextFrame
>      format.setColumnCount(3);
>      // Especifica el espaciado entre columnas
>      format.setColumnSpacing(10);
>      // Guarda la presentación
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto predeterminado para un nuevo TextFrame. |

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Especifica si la forma es un cuadro de texto.

--------------------

Si la forma no está especificada como un cuadro de texto no significa que no pueda tener texto adjunto. Un cuadro de texto es simplemente una forma especializada con propiedades específicas.

**Devuelve:**
boolean