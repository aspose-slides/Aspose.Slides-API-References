---
title: AutoShape
second_title: Referência da API Aspose.Slides para Java
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
| [getShapeLock()](#getShapeLock--) | Retorna os bloqueios da forma. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retorna os bloqueios do autoshape. |
| [getTextFrame()](#getTextFrame--) | Retorna o objeto TextFrame para o AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de ser especificado por estilo ou formato de preenchimento. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de ser especificado por estilo ou formato de preenchimento. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adiciona um novo TextFrame a uma forma. |
| [isTextBox()](#isTextBox--) | Especifica se a forma é uma caixa de texto. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Retorna os bloqueios da forma. Somente leitura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retorna:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Retorna os bloqueios do autoshape. Somente leitura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

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

Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de ser especificado por estilo ou formato de preenchimento. Leitura/Gravação boolean.

**Retorna:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de ser especificado por estilo ou formato de preenchimento. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Adiciona um novo TextFrame a uma forma. Se a forma já possui TextFrame, então simplesmente altera seu texto.

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
>  // Instancia Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Obtém o primeiro slide da apresentação
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adiciona um AutoShape com o tipo definido como Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adiciona TextFrame ao Rectangle
>      ashp.addTextFrame(" ");
>      // Acessa o TextFrame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Cria o objeto Paragraph para o TextFrame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Cria um objeto Portion para o Paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Define o texto
>      portion.setText("Aspose TextBox");
>      // Salva a apresentação em disco
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Obtém o primeiro slide da apresentação
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Adiciona um AutoShape com o tipo definido como Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Adiciona TextFrame ao Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Obtém o formato de texto do TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Especifica o número de colunas no TextFrame
>      format.setColumnCount(3);
>      // Especifica o espaçamento entre colunas
>      format.setColumnSpacing(10);
>      // Salva a apresentação
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

Se a forma não for especificada como caixa de texto, isso não significa que ela não possa ter texto anexado a ela. Uma caixa de texto é apenas uma forma especializada com propriedades específicas.

**Retorna:**
boolean