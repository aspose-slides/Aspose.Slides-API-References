---
title: Shape
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili bentuk pada slide.
type: docs
url: /id/com.aspose.slides/shape/
---
**Warisan:**  
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

Mewakili sebuah shape pada slide.  
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Menentukan apakah shape adalah TextHolder\_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Mengembalikan placeholder untuk sebuah shape. |
| [removePlaceholder()](#removePlaceholder--) | Menetapkan bahwa shape ini bukan placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Menambahkan placeholder baru bila tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini). |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus shape. |
| [getRawFrame()](#getRawFrame--) | Mengembalikan atau mengatur properti frame shape mentah. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur properti frame shape mentah. |
| [getFrame()](#getFrame--) | Mengembalikan atau mengatur properti frame shape. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur properti frame shape. |
| [getLineFormat()](#getLineFormat--) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk sebuah shape. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape. |
| [getImage()](#getImage--) | Mengembalikan thumbnail shape. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Mengembalikan thumbnail shape. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Menyimpan konten Shape sebagai file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Menyimpan konten Shape sebagai file SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Mengembalikan manajer hyperlink. |
| [getHidden()](#getHidden--) | Menentukan apakah shape tersembunyi. |
| [setHidden(boolean value)](#setHidden-boolean-) | Menentukan apakah shape tersembunyi. |
| [getZOrderPosition()](#getZOrderPosition--) | Mengembalikan posisi shape dalam urutan z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Mengembalikan jumlah situs koneksi pada shape. |
| [getRotation()](#getRotation--) | Mengembalikan atau mengatur jumlah derajat shape yang diputar di sekitar sumbu z. |
| [setRotation(float value)](#setRotation-float-) | Mengembalikan atau mengatur jumlah derajat shape yang diputar di sekitar sumbu z. |
| [getX()](#getX--) | Mengambil atau mengatur koordinat x sudut kiri atas shape, dalam poin. |
| [setX(float value)](#setX-float-) | Mengambil atau mengatur koordinat x sudut kiri atas shape, dalam poin. |
| [getY()](#getY--) | Mengambil atau mengatur koordinat y sudut kiri atas shape, dalam poin. |
| [setY(float value)](#setY-float-) | Mengambil atau mengatur koordinat y sudut kiri atas shape, dalam poin. |
| [getWidth()](#getWidth--) | Mengambil atau mengatur lebar shape, dalam poin. |
| [setWidth(float value)](#setWidth-float-) | Mengambil atau mengatur lebar shape, dalam poin. |
| [getHeight()](#getHeight--) | Mengambil atau mengatur tinggi shape, dalam poin. |
| [setHeight(float value)](#setHeight-float-) | Mengambil atau mengatur tinggi shape, dalam poin. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih. |
| [getUniqueId()](#getUniqueId--) | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen. |
| [getAlternativeText()](#getAlternativeText--) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama shape. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama shape. |
| [isDecorative()](#isDecorative--) | Mengambil atau mengatur opsi “Mark as decorative” Boolean Baca/tulis. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Mengambil atau mengatur opsi “Mark as decorative” Boolean Baca/tulis. |
| [getShapeLock()](#getShapeLock--) | Mengembalikan kunci shape. |
| [isGrouped()](#isGrouped--) | Menentukan apakah shape dikelompokkan. |
| [getParentGroup()](#getParentGroup--) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah shape. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah slide. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Menentukan apakah shape adalah TextHolder\_PPT. Baca-saja boolean.

**Mengembalikan:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Mengembalikan placeholder untuk sebuah shape. Mengembalikan null bila shape tidak memiliki placeholder. Baca-saja [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Membuat instance kelas Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterasi melalui shape untuk menemukan placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Mengubah teks pada setiap placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Menyimpan presentasi ke disk
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Iterasi melalui slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint menampilkan "Klik untuk menambahkan judul"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Menambahkan subtitle
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Menetapkan bahwa shape ini bukan placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Menambahkan placeholder baru bila tidak ada dan mengatur properti placeholder ke yang ditentukan.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder untuk menyalin konten dari. |

**Mengembalikan:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) – Baru #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini).

--------------------

> ```
> // dapatkan semua efek animasi (master/layout/slide) dari shape placeholder
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Null dikembalikan bila shape saat ini tidak diwarisi.

**Mengembalikan:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Mengembalikan data khusus shape. Baca-saja [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //atau
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Kode semacam ini dapat menyebabkan situasi yang tidak jelas. Jadi pembatasan telah ditambahkan untuk penggunaan nilai yang tidak terdefinisi pada IShape.getFrame(). Nilai x, y, lebar, tinggi, flipH, flipV, dan rotationAngle harus didefinisikan (bukan Float.NaN atau NullableBool.NotDefined). Contoh kode di atas sekarang melempar pengecualian ArgumentException.
>  //Ini berlaku untuk kasus penggunaan berikut:
>  IShape shape = ...;
>  shape.setFrame(...); // tidak boleh tidak terdefinisi
>  IShapeCollection shapes = ...;
>  // parameter x, y, lebar, tinggi tidak boleh Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //Namun properti frame IShape.RawFrame dapat tidak terdefinisi. Ini masuk akal ketika shape terhubung ke placeholder. Nilai frame yang tidak terdefinisi kemudian digantikan oleh nilai dari shape placeholder induk. Jika tidak ada placeholder induk untuk shape tersebut, maka shape akan menggunakan nilai default saat mengevaluasi frame efektif berdasarkan IShape.RawFrame-nya. Nilai default adalah 0 dan NullableBool.False untuk x, y, lebar, tinggi, flipH, flipV, dan rotationAngle. Misalnya:
>  IShape shape = ...; // shape terhubung ke placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // sekarang shape mewarisi nilai x, y, tinggi, flipH, flipV dari placeholder dan mengganti lebar=100 serta rotationAngle=0.{code}
> ```


**Mengembalikan:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Mengembalikan atau mengatur properti frame shape mentah. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //atau
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Kode semacam ini dapat menyebabkan situasi yang tidak jelas. Jadi pembatasan telah ditambahkan untuk penggunaan nilai yang tidak terdefinisi pada IShape.getFrame(). Nilai x, y, lebar, tinggi, flipH, flipV, dan rotationAngle harus didefinisikan (bukan Float.NaN atau NullableBool.NotDefined). Contoh kode di atas kini melempar pengecualian ArgumentException.
>  //Ini berlaku untuk kasus penggunaan berikut:
>  IShape shape = ...;
>  shape.setFrame(...); // tidak boleh tidak terdefinisi
>  IShapeCollection shapes = ...;
>  // parameter x, y, lebar, tinggi tidak boleh Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //Namun properti frame IShape.RawFrame dapat tidak terdefinisi. Hal ini masuk akal ketika shape terhubung ke placeholder. Nilai frame shape yang tidak terdefinisi akan digantikan oleh nilai dari placeholder induk. Jika tidak ada placeholder induk untuk shape tersebut, maka shape akan menggunakan nilai default saat mengevaluasi frame efektif berdasarkan IShape.RawFrame-nya. Nilai default adalah 0 dan NullableBool.False untuk x, y, lebar, tinggi, flipH, flipV, dan rotationAngle. Misalnya:
>  IShape shape = ...; // shape terhubung ke placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // sekarang shape mewarisi nilai x, y, tinggi, flipH, flipV dari placeholder dan mengganti lebar=100 serta rotationAngle=0.{code}
> ```


**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Mengembalikan atau mengatur properti frame shape. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Nilai setiap properti dari instance IShapeFrame yang dikembalikan tidak undefined (bukan NaN atau NotDefined). Nilai setiap properti dari instance IShapeFrame yang ditetapkan harus tidak undefined (bukan NaN atau NotDefined). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Mengembalikan:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Mengembalikan atau mengatur properti frame shape. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Nilai setiap properti dari instance IShapeFrame yang dikembalikan tidak undefined (bukan NaN atau NotDefined). Nilai setiap properti dari instance IShapeFrame yang ditetapkan harus tidak undefined (bukan NaN atau NotDefined). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti garis. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Mengembalikan objek ThreeDFormat yang berisi properti efek 3D untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti 3D. Baca-saja [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Mengembalikan:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti efek. Baca-saja [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape. Catatan: dapat mengembalikan null untuk jenis shape tertentu yang tidak memiliki properti isi. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Aksen 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Aksen 4, Lebih Terang 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Aksen 4, Lebih Terang 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Aksen 4, Lebih Terang 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Aksen 4, Lebih Gelap 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Aksen 4, Lebih Gelap 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Mengembalikan thumbnail shape. Tipe bounds ShapeThumbnailBounds.Shape digunakan secara default.

**Mengembalikan:**  
[IImage](../../com.aspose.slides/iimage) – Thumbnail shape.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Mengembalikan thumbnail shape.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bounds | int | Tipe bounds thumbnail shape. |
| scaleX | float | Skala X |
| scaleY | float | Skala Y |

**Mengembalikan:**  
[IImage](../../com.aspose.slides/iimage) – Thumbnail shape atau null bila ShapeThumbnailBounds.Appearance digunakan dan shape tidak memiliki elemen yang terlihat.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Menyimpan konten Shape sebagai file SVG.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream target |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Menyimpan konten Shape sebagai file SVG.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream target |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opsi pembuatan SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. Baca/tulis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. Baca/tulis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Mengembalikan:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. Baca/tulis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Mengembalikan manajer hyperlink. Baca-saja [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Mengembalikan:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Menentukan apakah shape tersembunyi. Baca/tulis boolean.

**Mengembalikan:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Menentukan apakah shape tersembunyi. Baca/tulis boolean.

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Mengembalikan posisi shape dalam urutan z. Shapes[0] mengembalikan shape paling belakang dalam urutan z, dan Shapes[Shapes.Count - 1] mengembalikan shape paling depan. Baca-saja int.

**Mengembalikan:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Mengembalikan jumlah situs koneksi pada shape. Baca-saja int.

**Mengembalikan:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Mengembalikan atau mengatur jumlah derajat shape yang diputar di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi (bukan Float.NaN). Nilai yang ditetapkan harus terdefinisi (bukan Float.NaN). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Mengembalikan:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Mengembalikan atau mengatur jumlah derajat shape yang ditentukan diputar di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi (bukan Float.NaN). Nilai yang ditetapkan harus terdefinisi (bukan Float.NaN). Anda dapat menetapkan nilai tidak terdefinisi untuk properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```


Mendapatkan atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Mengembalikan:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Mendapatkan atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Mendapatkan atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Mengembalikan:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Mendapatkan atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Mendapatkan atau mengatur lebar shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Mengembalikan:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Mendapatkan atau mengatur lebar shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Mendapatkan atau mengatur tinggi shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Mengembalikan:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Mendapatkan atau mengatur tinggi shape, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang ditetapkan juga harus terdefinisi; tetapkan Float.NaN hanya pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```


Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Mengembalikan:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```


Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih. Baca/tulis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```


Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lainnya. Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, nilai ini tidak boleh diperlakukan sebagai kunci unik yang persisten. Baca-saja long. Lihat juga \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Mengembalikan:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```


Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen. Baca-saja long. Lihat juga \#getUniqueId.getUniqueId.

**Mengembalikan:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Mengembalikan atau mengatur teks alternatif yang terkait dengan shape. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```


Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```


Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


Mengembalikan atau mengatur nama shape. Harus tidak null. Gunakan string kosong bila diperlukan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mengembalikan atau mengatur nama shape. Harus tidak null. Gunakan string kosong bila diperlukan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```


Mendapatkan atau mengatur opsi 'Mark as decorative'. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```


Mendapatkan atau mengatur opsi 'Mark as decorative'. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```


Mengembalikan kunci-kunci shape. Baca-saja [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Mengembalikan:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```


Menentukan apakah shape dikelompokkan. Baca-saja boolean.

--------------------

Properti \#getParentGroup.getParentGroup mengembalikan objek GroupShape induk jika shape dikelompokkan.

**Mengembalikan:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan null. Baca-saja [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Properti \#isGrouped.isGrouped menentukan apakah shape dikelompokkan.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```


Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

**Mengembalikan:**
java.awt.geom.Rectangle2D.Float - Sebuah java.awt.geom.Rectangle2D.Float yang mewakili batas visual shape dalam koordinat slide.

--------------------

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama proses rendering dalam ruang koordinat slide. Batas ini dapat berbeda dari batas model shape \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) dan dapat berisi koordinat negatif bila konten yang dirender melampaui asal slide. Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya rotasi), lebar dan sambungan garis, tata letak dan overflow teks, geometri SmartArt, serta efek tata letak lain yang memengaruhi tampilan akhir shape yang dirender. Batas yang dikembalikan tidak dipotong ke persegi panjang slide.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Mengembalikan slide induk dari sebuah shape. Baca-saja [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Mengembalikan presentasi induk dari sebuah slide. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)