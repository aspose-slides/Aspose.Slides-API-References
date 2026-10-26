---
title: AutoShape
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Bir AutoShape'i temsil eder.
type: docs
url: /tr/com.aspose.slides/autoshape/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Bir AutoShape'i temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape'in kilitlerini döndürür. |
| [getAutoShapeLock()](#getAutoShapeLock--) | autoshape'in kilitlerini döndürür. |
| [getTextFrame()](#getTextFrame--) | AutoShape için TextFrame nesnesini döndürür. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bu autoshape'in stil veya dolgu biçimiyle belirtilen yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bu autoshape'in stil veya dolgu biçimiyle belirtilen yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Bir shape'e yeni bir TextFrame ekler. |
| [isTextBox()](#isTextBox--) | shape'in bir metin kutusu olup olmadığını belirtir. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

shape'in kilitlerini döndürür. Salt okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

autoshape'in kilitlerini döndürür. Salt okunur [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Döndürür:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape için TextFrame nesnesini döndürür. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Bu autoshape'in stil veya dolgu biçimiyle belirtilen yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Bu autoshape'in stil veya dolgu biçimiyle belirtilen yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Bir shape'e yeni bir TextFrame ekler. Shape zaten bir TextFrame'e sahipse, sadece metnini değiştirir.

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
>  // Sunumu oluşturur
>  Presentation pres = new Presentation();
>  try {
>      // Sunumdaki ilk slaytı alır
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Türü Dikdörtgen olarak ayarlı bir AutoShape ekler
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Dikdörtgene TextFrame ekler
>      ashp.addTextFrame(" ");
>      // Metin çerçevesine erişir
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Metin çerçevesi için Paragraph nesnesi oluşturur
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Paragraph için Portion nesnesi oluşturur
>      IPortion portion = para.getPortions().get_Item(0);
>      // Metni ayarlar
>      portion.setText("Aspose TextBox");
>      // Sunumu diske kaydeder
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Sunumdaki ilk slaytı alır
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Bir AutoShape ekler, türü Dikdörtgen olarak ayarlanmış
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Dikdörtgene TextFrame ekler
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // TextFrame'in metin biçimini alır
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // TextFrame'de sütun sayısını belirtir
>      format.setColumnCount(3);
>      // Sütunlar arasındaki boşluğu belirtir
>      format.setColumnSpacing(10);
>      // Sunumu kaydeder
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

shape'in bir metin kutusu olup olmadığını belirtir.

--------------------

shape'in bir metin kutusu olarak belirtilmemiş olması, ona metin eklenemeyeceği anlamına gelmez. Bir metin kutusu, yalnızca belirli özelliklere sahip özel bir shape'dir.

**Döndürür:**
boolean