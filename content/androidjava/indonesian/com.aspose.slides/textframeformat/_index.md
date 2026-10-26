---
title: TextFrameFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Berisi properti formatTextFrameFormatting dari TextFrames.
type: docs
url: /id/com.aspose.slides/textframeformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Berisi properti formatTextFrameFormatting dari TextFrame.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Menginisialisasi instance baru dari kelas [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Mengembalikan gaya teks. |
| [getThreeDFormat()](#getThreeDFormat--) | Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. |
| [getMarginTop()](#getMarginTop--) | Mengembalikan atau mengatur margin atas (point) dalam TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Mengembalikan atau mengatur margin atas (point) dalam TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. |
| [getWrapText()](#getWrapText--) | True jika teks dibungkus pada margin TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True jika teks dibungkus pada margin TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. |
| [getCenterText()](#getCenterText--) | Jika NullableBool.True maka teks harus ditengahkan secara horizontal dalam kotak. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jika NullableBool.True maka teks harus ditengahkan secara horizontal dalam kotak. |
| [getTextVerticalType()](#getTextVerticalType--) | Menentukan orientasi teks. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Menentukan orientasi teks. |
| [getAutofitType()](#getAutofitType--) | Mengembalikan atau mengatur mode autofit teks. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Mengembalikan atau mengatur mode autofit teks. |
| [getColumnCount()](#getColumnCount--) | Mengembalikan atau mengatur jumlah kolom dalam area teks. |
| [setColumnCount(int value)](#setColumnCount-int-) | Mengembalikan atau mengatur jumlah kolom dalam area teks. |
| [getColumnSpacing()](#getColumnSpacing--) | Mengembalikan atau mengatur jarak antar kolom teks dalam area teks (dalam point). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Mengembalikan atau mengatur jarak antar kolom teks dalam area teks (dalam point). |
| [getRotationAngle()](#getRotationAngle--) | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur bentuk pembungkus teks. |
| [setTransform(byte value)](#setTransform-byte-) | Mendapatkan atau mengatur bentuk pembungkus teks. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Mendapatkan atau mengatur mempertahankan teks tetap datar meskipun efek Rotasi 3-D diterapkan. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Mendapatkan atau mengatur mempertahankan teks tetap datar meskipun efek Rotasi 3-D diterapkan. |
| [getEffective()](#getEffective--) | Mendapatkan data format bingkai teks yang efektif dengan pewarisan yang diterapkan. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Menginisialisasi instance baru dari kelas [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Mengembalikan gaya teks. Hanya-baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks. Hanya-baca [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Atur transformasi teks
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Atur ekstrusi
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Atur kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Atur kedalaman
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Atur material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Atur pencahayaan
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Atur tipe kamera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Mengembalikan atau mengatur margin atas (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Mengembalikan atau mengatur margin atas (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True jika teks dibungkus pada margin TextFrame. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True jika teks dibungkus pada margin TextFrame. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Mengembalikan:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Jika NullableBool.True maka teks harus ditengahkan secara horizontal dalam kotak. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Jika NullableBool.True maka teks harus ditengahkan secara horizontal dalam kotak. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Menentukan orientasi teks. Nilai visual rotasi teks yang dihasilkan diringkas dari properti ini dan sudut khusus di properti RotationAngle. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Mengembalikan:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Menentukan orientasi teks. Nilai visual rotasi teks yang dihasilkan diringkas dari properti ini dan sudut khusus di properti RotationAngle. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Mengembalikan atau mengatur mode autofit teks. Baca/tulis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Mengembalikan atau mengatur mode autofit teks. Baca/tulis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Mengembalikan atau mengatur jumlah kolom dalam area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diset ke nol. Nilai 0 berarti nilai tak terdefinisi. Baca/tulis int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Mengembalikan atau mengatur jumlah kolom dalam area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diset ke nol. Nilai 0 berarti nilai tak terdefinisi. Baca/tulis int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Mengembalikan atau mengatur jarak antar kolom teks dalam area teks (dalam point). Ini hanya berlaku ketika ada lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diset ke nol. Baca/tulis double.

**Mengembalikan:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Mengembalikan atau mengatur jarak antar kolom teks dalam area teks (dalam point). Ini hanya berlaku ketika ada lebih dari 1 kolom. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diset ke nol. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang melampirinya yang digunakan. Jika ditentukan, maka rotasi ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi selain rotasi yang diterapkan pada teks itu sendiri. Nilai visual rotasi teks yang dihasilkan diringkas dari properti ini dan tipe vertikal yang telah ditetapkan di properti TextVerticalType. Baca/tulis float.

--------------------

> ```
> Pertimbangkan kasus di mana sebuah bentuk memiliki rotasi 90 derajat searah jarum jam yang diterapkan padanya. 
>  Selain itu, tubuh teks itu sendiri memiliki rotasi -90 derajat 
>  berlawanan arah jarum jam yang diterapkan padanya. Maka bentuk yang dihasilkan akan tampak 
>  berputar tetapi teks di dalamnya akan tampak seolah-olah tidak diputar sama sekali.
```

**Mengembalikan:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang melampirinya yang digunakan. Jika ditentukan, maka rotasi ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi selain rotasi yang diterapkan pada teks itu sendiri. Nilai visual rotasi teks yang dihasilkan diringkas dari properti ini dan tipe vertikal yang telah ditetapkan di properti TextVerticalType. Baca/tulis float.

--------------------

> ```
> Pertimbangkan kasus di mana sebuah bentuk memiliki rotasi 90 derajat searah jarum jam yang diterapkan padanya. 
>  Selain itu, tubuh teks itu sendiri memiliki rotasi -90 derajat 
>  berlawanan arah jarum jam yang diterapkan padanya. Maka bentuk yang dihasilkan akan tampak 
>  berputar tetapi teks di dalamnya akan tampak seolah-olah tidak diputar sama sekali.
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Mendapatkan atau mengatur bentuk pembungkus teks. Baca/tulis [TextShapeType](../../com.aspose.slides/textshapetype).

**Mengembalikan:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Mendapatkan atau mengatur bentuk pembungkus teks. Baca/tulis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Mendapatkan atau mengatur mempertahankan teks tetap datar meskipun efek Rotasi 3-D diterapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Mendapatkan atau mengatur mempertahankan teks tetap datar meskipun efek Rotasi 3-D diterapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Mendapatkan data format bingkai teks yang efektif dengan pewarisan yang diterapkan.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).