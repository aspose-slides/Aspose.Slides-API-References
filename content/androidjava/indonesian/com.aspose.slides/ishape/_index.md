---
title: IShape
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sebuah bentuk pada slide.
type: docs
url: /id/com.aspose.slides/ishape/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Mewakili sebuah bentuk pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Menentukan apakah bentuk adalah TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Mengembalikan placeholder untuk sebuah bentuk. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [removePlaceholder()](#removePlaceholder--) | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus bentuk. |
| [getRawFrame()](#getRawFrame--) | Mengembalikan atau mengatur properti bingkai bentuk mentah. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur properti bingkai bentuk mentah. |
| [getFrame()](#getFrame--) | Mengembalikan atau mengatur properti bingkai bentuk mentah. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur properti bingkai bentuk mentah. |
| [getLineFormat()](#getLineFormat--) | Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah bentuk. |
| [getThreeDFormat()](#getThreeDFormat--) | Mengembalikan objek ThreeDFormat yang berisi properti format garis untuk sebuah bentuk. |
| [getEffectFormat()](#getEffectFormat--) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek FillFormat yang berisi properti format isian untuk sebuah bentuk. |
| [getImage()](#getImage--) | Mengembalikan thumbnail bentuk. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Mengembalikan thumbnail bentuk. |
| [getHidden()](#getHidden--) | Menentukan apakah bentuk tersembunyi. |
| [setHidden(boolean value)](#setHidden-boolean-) | Menentukan apakah bentuk tersembunyi. |
| [getZOrderPosition()](#getZOrderPosition--) | Mengembalikan posisi sebuah bentuk dalam urutan z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Mengembalikan jumlah situs koneksi pada bentuk. |
| [getRotation()](#getRotation--) | Mengembalikan atau mengatur jumlah derajat bentuk yang diputar di sekitar sumbu z. |
| [setRotation(float value)](#setRotation-float-) | Mengembalikan atau mengatur jumlah derajat bentuk yang diputar di sekitar sumbu z. |
| [getX()](#getX--) | Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. |
| [setX(float value)](#setX-float-) | Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. |
| [getY()](#getY--) | Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. |
| [setY(float value)](#setY-float-) | Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. |
| [getWidth()](#getWidth--) | Mendapatkan atau mengatur lebar bentuk, diukur dalam poin. |
| [setWidth(float value)](#setWidth-float-) | Mendapatkan atau mengatur lebar bentuk, diukur dalam poin. |
| [getHeight()](#getHeight--) | Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin. |
| [setHeight(float value)](#setHeight-float-) | Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin. |
| [getAlternativeText()](#getAlternativeText--) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama sebuah bentuk. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama sebuah bentuk. |
| [isDecorative()](#isDecorative--) | Mendapatkan atau mengatur opsi 'Mark as decorative' boolean baca/tulis. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Mendapatkan atau mengatur opsi 'Mark as decorative' boolean baca/tulis. |
| [getShapeLock()](#getShapeLock--) | Mengembalikan kunci bentuk. |
| [getUniqueId()](#getUniqueId--) | Mengembalikan pengenal internal berskala presentasi yang ditujukan untuk penggunaan oleh add-in atau kode lainnya. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop merujuk bentuk dengan andal dari mana saja dalam dokumen. |
| [isGrouped()](#isGrouped--) | Menentukan apakah bentuk dikelompokkan. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode hitam-putih. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode hitam-putih. |
| [getParentGroup()](#getParentGroup--) | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Menyimpan konten Shape sebagai file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Menyimpan konten Shape sebagai file SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Menentukan apakah bentuk adalah TextHolder. Boolean hanya-baca.

**Mengembalikan:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Mengembalikan placeholder untuk sebuah bentuk. Hanya-baca [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Mengembalikan:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder untuk menyalin konten dari. |

**Mengembalikan:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - [IPlaceholder](../../com.aspose.slides/iplaceholder) baru.

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Mendefinisikan bahwa bentuk ini bukan placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Mengembalikan data khusus bentuk. Hanya-baca [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //atau
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Kode semacam ini dapat menyebabkan situasi yang tidak jelas. Jadi pembatasan telah ditambahkan untuk penggunaan nilai undefined pada IShape.getFrame(). Nilai x, y, width, height, flipH, flipV, dan rotationAngle harus didefinisikan (bukan Float.NaN atau NullableBool.NotDefined). Contoh kode di atas kini melempar pengecualian ArgumentException.
>  //Ini berlaku untuk kasus penggunaan berikut:
>  IShape shape = ...;
>  shape.setFrame(...); // tidak boleh undefined
>  IShapeCollection shapes = ...;
>  // parameter x, y, width, height tidak boleh Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // bentuk terhubung ke placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // sekarang shape mewarisi nilai x, y, height, flipH, flipV dari placeholder dan menggantikan width=100 serta rotationAngle=0.
> ```


**Mengembalikan:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Mengembalikan atau mengatur properti bingkai bentuk mentah. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //atau
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Kode semacam ini dapat menyebabkan situasi yang tidak jelas. Jadi pembatasan telah ditambahkan untuk penggunaan nilai undefined pada IShape.getFrame(). Nilai x, y, width, height, flipH, flipV, dan rotationAngle harus didefinisikan (bukan Float.NaN atau NullableBool.NotDefined). Contoh kode di atas kini melempar pengecualian ArgumentException.
>  //Ini berlaku untuk kasus penggunaan berikut:
>  IShape shape = ...;
>  shape.setFrame(...); // tidak boleh undefined
>  IShapeCollection shapes = ...;
>  // parameter x, y, width, height tidak boleh Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // bentuk terhubung ke placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // sekarang shape mewarisi nilai x, y, height, flipH, flipV dari placeholder dan menggantikan width=100 serta rotationAngle=0.
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Nilai setiap properti dari instance IShapeFrame yang dikembalikan tidak undefined (bukan NaN atau NotDefined). Nilai setiap properti dari instance IShapeFrame yang diberikan harus tidak undefined (bukan NaN atau NotDefined). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Mengembalikan:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Mengembalikan atau mengatur properti bingkai bentuk. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Nilai setiap properti dari instance IShapeFrame yang dikembalikan tidak undefined (bukan NaN atau NotDefined). Nilai setiap properti dari instance IShapeFrame yang diberikan harus tidak undefined (bukan NaN atau NotDefined). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah bentuk. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Mengembalikan objek ThreeDFormat yang berisi properti format garis untuk sebuah bentuk. Hanya-baca [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Mengembalikan:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk. Hanya-baca [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Mengembalikan:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Mengembalikan objek FillFormat yang berisi properti format isian untuk sebuah bentuk. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Mengembalikan thumbnail bentuk. Tipe batas ShapeThumbnailBounds.Shape digunakan secara default.

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - thumbnail bentuk.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Mengembalikan thumbnail bentuk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bounds | int | Tipe batas thumbnail bentuk. |
| scaleX | float | Skala X |
| scaleY | float | Skala Y |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - thumbnail bentuk atau null ketika ShapeThumbnailBounds.Appearance digunakan dan bentuk tidak memiliki elemen yang terlihat.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Menentukan apakah bentuk tersembunyi. Boolean baca/tulis.

**Mengembalikan:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Menentukan apakah bentuk tersembunyi. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Mengembalikan posisi sebuah bentuk dalam urutan z. Shapes[0] mengembalikan bentuk paling belakang, dan Shapes[Shapes.Count - 1] mengembalikan bentuk paling depan. Hanya-baca int.

**Mengembalikan:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Mengembalikan jumlah situs koneksi pada bentuk. Hanya-baca int.

**Mengembalikan:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Mengembalikan atau mengatur jumlah derajat bentuk yang diputar di sekitar sumbu z. Nilai positif berarti putaran searah jarum jam; nilai negatif berarti berlawanan arah jarum jam. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi (bukan Float.NaN). Nilai yang diberikan harus terdefinisi (bukan Float.NaN). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Mengembalikan:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Mengembalikan atau mengatur jumlah derajat bentuk yang diputar di sekitar sumbu z. Nilai positif berarti putaran searah jarum jam; nilai negatif berarti berlawanan arah jarum jam. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi (bukan Float.NaN). Nilai yang diberikan harus terdefinisi (bukan Float.NaN). Anda dapat menetapkan nilai undefined untuk properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Mengembalikan:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Mengembalikan:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Mendapatkan atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Mengembalikan:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Mendapatkan atau mengatur lebar bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Mengembalikan:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin. Baca/tulis float.

--------------------

Nilai yang dikembalikan selalu terdefinisi dan tidak pernah Float.NaN. Nilai yang diberikan juga harus terdefinisi; hanya menetapkan Float.NaN pada properti instance RawFrame.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Mengembalikan atau mengatur nama sebuah bentuk. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Mengembalikan atau mengatur nama sebuah bentuk. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Mendapatkan atau mengatur opsi 'Mark as decorative' boolean baca/tulis.

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
public abstract void setDecorative(boolean value)
```

Mendapatkan atau mengatur opsi 'Mark as decorative' boolean baca/tulis.

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
public abstract IBaseShapeLock getShapeLock()
```

Mengembalikan kunci bentuk. Hanya-baca [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Mengembalikan:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public 
```

Mengembalikan pengenal internal berskala presentasi yang ditujukan untuk penggunaan oleh add-in atau kode lainnya. Karena nilai ini dapat diubah oleh pengguna atau secara programatis, tidak boleh diperlakukan sebagai kunci unik yang persisten. Hanya-baca long. Lihat juga \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Mengembalikan:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup bentuk dan memungkinkan PowerPoint atau kode interop merujuk bentuk dengan andal dari mana saja dalam dokumen. Hanya-baca long. Lihat juga \#getUniqueId.getUniqueId.

**Mengembalikan:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Menentukan apakah bentuk dikelompokkan. Hanya-baca boolean.

--------------------

Properti \#getParentGroup.getParentGroup mengembalikan objek GroupShape induk jika bentuk dikelompokkan.

**Mengembalikan:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Properti menentukan bagaimana bentuk akan ditampilkan dalam mode hitam-putih. Baca/tulis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Mengembalikan:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Properti menentukan bagaimana bentuk akan ditampilkan dalam mode hitam-putih. Baca/tulis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan null. Hanya-baca [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Properti \#isGrouped.isGrouped menentukan apakah bentuk dikelompokkan.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Menyimpan konten Shape sebagai file SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream target |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Menyimpan konten Shape sebagai file SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream target |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opsi generasi SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini).

--------------------

> ```
> // dapatkan semua efek animasi (master/layout/slide) dari bentuk placeholder
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

null dikembalikan jika bentuk saat ini tidak diwarisi.

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)