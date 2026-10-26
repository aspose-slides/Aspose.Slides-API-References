---
title: AutoShape
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah AutoShape.
type: docs
url: /id/com.aspose.slides/autoshape/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Mewakili sebuah AutoShape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Mengembalikan kunci shape. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Mengembalikan kunci autoshape. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan objek TextFrame untuk AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh gaya atau format isian. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh gaya atau format isian. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Menambahkan TextFrame baru ke sebuah shape. |
| [isTextBox()](#isTextBox--) | Menentukan apakah shape adalah kotak teks. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Mengembalikan kunci shape. Hanya-baca [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Mengembalikan:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Mengembalikan kunci autoshape. Hanya-baca [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Mengembalikan:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Mengembalikan objek TextFrame untuk AutoShape. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh gaya atau format isian. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh gaya atau format isian. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Menambahkan TextFrame baru ke sebuah shape. Jika shape sudah memiliki TextFrame maka cukup mengubah teksnya.

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
>  // Menginisialisasi Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Mendapatkan slide pertama dalam presentasi
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Menambahkan AutoShape dengan tipe Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Menambahkan TextFrame ke Rectangle
>      ashp.addTextFrame(" ");
>      // Mengakses text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Membuat objek Paragraph untuk text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Membuat objek Portion untuk paragraf
>      IPortion portion = para.getPortions().get_Item(0);
>      // Mengatur teks
>      portion.setText("Aspose TextBox");
>      // Menyimpan presentasi ke disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Mendapatkan slide pertama dalam presentasi
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Menambahkan AutoShape dengan tipe Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Menambahkan TextFrame ke Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Mendapatkan format teks dari TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Menentukan jumlah kolom dalam TextFrame
>      format.setColumnCount(3);
>      // Menentukan jarak antar kolom
>      format.setColumnSpacing(10);
>      // Menyimpan presentasi
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks default untuk TextFrame baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Menentukan apakah shape adalah kotak teks.

--------------------

Jika shape tidak ditentukan sebagai kotak teks tidak berarti bahwa shape tidak dapat memiliki teks yang terlampir. Kotak teks hanyalah shape khusus dengan properti tertentu.

**Mengembalikan:**
boolean