---
title: AutoShape
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un AutoShape.
type: docs
url: /it/com.aspose.slides/autoshape/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tutte le interfacce implementate:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Rappresenta un AutoShape.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Restituisce i blocchi della forma. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Restituisce i blocchi dell'autoshape. |
| [getTextFrame()](#getTextFrame--) | Restituisce l'oggetto TextFrame per l'AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Aggiunge un nuovo TextFrame a una forma. |
| [isTextBox()](#isTextBox--) | Specifica se la forma è una casella di testo. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Restituisce i blocchi della forma. Solo lettura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Restituisce:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Restituisce i blocchi dell'autoshape. Solo lettura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Restituisce:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Restituisce l'oggetto TextFrame per l'AutoShape. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. Booleano di lettura/scrittura.

**Restituisce:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Determina se questo autoshape deve essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. Booleano di lettura/scrittura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Aggiunge un nuovo TextFrame a una forma. Se la forma ha già un TextFrame, cambierà semplicemente il suo testo.

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
>  // Instanzia la presentazione
>  Presentation pres = new Presentation();
>  try {
>      // Ottiene la prima diapositiva nella presentazione
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Aggiunge un AutoShape con tipo impostato a Rettangolo
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Aggiunge TextFrame al rettangolo
>      ashp.addTextFrame(" ");
>      // Accede al frame di testo
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Crea l'oggetto Paragraph per il frame di testo
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Crea un oggetto Portion per il paragrafo
>      IPortion portion = para.getPortions().get_Item(0);
>      // Imposta il testo
>      portion.setText("Aspose TextBox");
>      // Salva la presentazione su disco
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Ottiene la prima diapositiva nella presentazione
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Aggiunge un AutoShape con tipo impostato a Rettangolo
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Aggiunge TextFrame al rettangolo
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Ottiene il formato del testo del TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifica il numero di colonne nel TextFrame
>      format.setColumnCount(3);
>      // Specifica lo spazio tra le colonne
>      format.setColumnSpacing(10);
>      // Salva la presentazione
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo predefinito per un nuovo TextFrame. |

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Specifica se la forma è una casella di testo.

--------------------

Se una forma non è specificata come casella di testo, ciò non significa che non possa avere del testo associato. Una casella di testo è semplicemente una forma specializzata con proprietà specifiche.

**Restituisce:**
boolean