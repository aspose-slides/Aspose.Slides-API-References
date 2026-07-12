---
title: AutoShape
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um AutoShape.
type: docs
url: /pt/com.aspose.slides/autoshape/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Representa um AutoShape.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retorna as travas da forma. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retorna as travas da autoshape. |
| [getTextFrame()](#getTextFrame--) | Retorna o objeto TextFrame para o AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina se esta autoshape deve ser preenchida com o preenchimento de fundo do slide em vez de ser especificada por estilo ou formato de preenchimento. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina se esta autoshape deve ser preenchida com o preenchimento de fundo do slide em vez de ser especificada por estilo ou formato de preenchimento. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adiciona um novo TextFrame a uma forma. |
| [isTextBox()](#isTextBox--) | Especifica se a forma é uma caixa de texto. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Retorna as travas da forma. Somente leitura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retorna:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Retorna as travas da autoshape. Somente leitura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retorna:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retorna o objeto TextFrame para o AutoShape. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Determina se esta autoshape deve ser preenchida com o preenchimento de fundo do slide em vez de ser especificada por estilo ou formato de preenchimento. Leitura/Gravação booleano.

**Retorna:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Determina se esta autoshape deve ser preenchida com o preenchimento de fundo do slide em vez de ser especificada por estilo ou formato de preenchimento. Leitura/Gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Adiciona um novo TextFrame a uma forma. Se a forma já possui TextFrame, simplesmente altera seu texto.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto padrão para um novo TextFrame. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Especifica se a forma é uma caixa de texto.

--------------------

Se a forma não for especificada como caixa de texto, isso não significa que ela não possa ter texto associado a ela. Uma caixa de texto é apenas uma forma especializada com propriedades específicas.

**Retorna:**
boolean