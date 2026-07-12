---
title: AutoShape
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un AutoShape.
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

Representa un AutoShape.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de la forma. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Devuelve los bloqueos del autoshape. |
| [getTextFrame()](#getTextFrame--) | Devuelve el objeto TextFrame para el AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina si este autoshape debe rellenarse con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o el formato de relleno. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina si este autoshape debe rellenarse con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o el formato de relleno. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Añade un nuevo TextFrame a una forma. |
| [isTextBox()](#isTextBox--) | Especifica si la forma es un cuadro de texto. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Devuelve los bloqueos de la forma. Solo lectura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Devuelve:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Devuelve los bloqueos del autoshape. Solo lectura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Devuelve:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Devuelve el objeto TextFrame para el AutoShape. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Determina si este autoshape debe rellenarse con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o el formato de relleno. Lectura/escritura boolean.

**Devuelve:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Determina si este autoshape debe rellenarse con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o el formato de relleno. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Añade un nuevo TextFrame a una forma. Si la forma ya tiene TextFrame, simplemente cambia su texto.

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
>  // Instantiates Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds an AutoShape with type set as Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adds TextFrame to the Rectangle
>      ashp.addTextFrame(" ");
>      // Accesses the text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creates the Paragraph object for text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creates a Portion object for the paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Sets the text
>      portion.setText("Aspose TextBox");
>      // Saves the presentation to disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an AutoShape with type set as Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Add TextFrame to the Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Gets the text format of TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifies the number of columns in TextFrame
>      format.setColumnCount(3);
>      // Specifies the spacing between columns
>      format.setColumnSpacing(10);
>      // Saves the presentation
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

Si la forma no se especifica como un cuadro de texto, no significa que no pueda tener texto adjunto. Un cuadro de texto es simplemente una forma especializada con propiedades específicas.

**Devuelve:**
boolean