---
title: AutoShape
second_title: Aspose.Slides Java API Referansı
description: Bir AutoShape'i temsil eder.
type: docs
url: /tr/com.aspose.slides/autoshape/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Bir AutoShape'i temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape'in kilitlerini döndürür. |
| [getTextFrame()](#getTextFrame--) | AutoShape için TextFrame nesnesini döndürür. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bu autoşeklin stil veya dolgu formatı tarafından belirtilen yerine slaydın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bu autoşeklin stil veya dolgu formatı tarafından belirtilen yerine slaydın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Bir şekle yeni bir TextFrame ekler. |
| [isTextBox()](#isTextBox--) | Şeklin bir metin kutusu olup olmadığını belirtir. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


Şeklin kilitlerini döndürür. Salt-okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


AutoShape'in kilitlerini döndürür. Salt-okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


AutoShape için TextFrame nesnesini döndürür. Salt-okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


Bu autoşeklin stil veya dolgu formatı tarafından belirtilen yerine slaydın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. Okunabilir-yazılabilir boolean.

**Döndürür:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Bu autoşeklin stil veya dolgu formatı tarafından belirtilen yerine slaydın arka plan dolgusu ile doldurulup doldurulmayacağını belirler. Okunabilir-yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


Bir şekle yeni bir TextFrame ekler. Şeklin zaten bir TextFrame’i varsa yalnızca metnini değiştirir.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrame için varsayılan metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


Şeklin bir metin kutusu olup olmadığını belirtir.

--------------------

Şeklin bir metin kutusu olarak belirtilmemiş olması, ona metin eklenemeyeceği anlamına gelmez. Bir metin kutusu yalnızca belirli özelliklere sahip özel bir şekildir.

**Döndürür:**
boolean