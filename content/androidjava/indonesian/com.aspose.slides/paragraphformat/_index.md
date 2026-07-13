---
title: ParagraphFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas ini berisi properti pemformatan paragraf.
type: docs
url: /id/com.aspose.slides/paragraphformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), semua properti kelas ini dapat ditulis.

--------------------

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam kebanyakan kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda perlu menggunakan metode [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) yang mengembalikan instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Menginisialisasi sebuah instance baru dari kelas [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBullet()](#getBullet--) | Mengembalikan format bullet paragraf. |
| [getDepth()](#getDepth--) | Mengembalikan atau mengatur kedalaman paragraf. |
| [setDepth(short value)](#setDepth-short-) | Mengembalikan atau mengatur kedalaman paragraf. |
| [getAlignment()](#getAlignment--) | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. |
| [setAlignment(int value)](#setAlignment-int-) | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. |
| [getSpaceWithin()](#getSpaceWithin--) | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. |
| [getSpaceBefore()](#getSpaceBefore--) | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. |
| [getSpaceAfter()](#getSpaceAfter--) | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Menentukan apakah pemisah baris Asia Timur digunakan dalam paragraf. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Menentukan apakah pemisah baris Asia Timur digunakan dalam paragraf. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah penulisan Right to Left digunakan dalam paragraf. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Menentukan apakah penulisan Right to Left digunakan dalam paragraf. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Menentukan apakah pemisah baris Latin digunakan dalam paragraf. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Menentukan apakah pemisah baris Latin digunakan dalam paragraf. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Menentukan apakah tanda baca gantung digunakan dalam paragraf. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Menentukan apakah tanda baca gantung digunakan dalam paragraf. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. |
| [setMarginRight(float value)](#setMarginRight-float-) | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. |
| [getIndent()](#getIndent--) | Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. |
| [setIndent(float value)](#setIndent-float-) | Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. |
| [getTabs()](#getTabs--) | Mengembalikan tabulasi sebuah paragraf. |
| [getFontAlignment()](#getFontAlignment--) | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Mengembalikan format bagian default sebuah paragraf. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan diterapkan. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


Menginisialisasi sebuah instance baru dari kelas [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


Mengembalikan format bullet paragraf. Hanya-baca [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Mengembalikan:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


Mengembalikan atau mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis  short .

**Mengembalikan:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


Mengembalikan atau mengatur kedalaman paragraf. Nilai 0 berarti nilai tidak terdefinisi. Baca/tulis  short .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Membuat objek Presentation yang merepresentasikan file PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Mengakses slide pertama
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Mengakses placeholder pertama dan kedua di slide dan melakukan typecasting menjadi AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Mengubah teks di kedua placeholder
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Mengambil paragraf pertama dari placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Menyelaraskan paragraf teks ke tengah
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Menulis presentasi sebagai file PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan. Baca/tulis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Membuat objek Presentation yang merepresentasikan file PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Mengakses slide pertama
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Mengakses placeholder pertama dan kedua di slide dan melakukan typecasting menjadi AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Mengubah teks di kedua placeholder
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Mengambil paragraf pertama dari placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Menyelaraskan paragraf teks ke tengah
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Menulis presentasi sebagai file PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, nilai negatif – ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca/tulis  float .

**Mengembalikan:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


Mengembalikan atau mengatur jumlah ruang antara garis dasar dalam paragraf. Nilai positif berarti persentase, nilai negatif – ukuran dalam poin. Tidak ada pewarisan yang diterapkan. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis  float .

**Mengembalikan:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


Mengembalikan atau mengatur jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis  float .

**Mengembalikan:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


Mengembalikan atau mengatur jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan. Nilai positif menentukan persentase ukuran font untuk ruang putih. Nilai negatif menentukan ukuran ruang putih dalam poin. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


Menentukan apakah pemisah baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


Menentukan apakah pemisah baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


Menentukan apakah penulisan Right to Left digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


Menentukan apakah penulisan Right to Left digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


Menentukan apakah pemisah baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


Menentukan apakah pemisah baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis  float .

**Mengembalikan:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis  float .

**Mengembalikan:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis  float .

**Mengembalikan:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis  float .

**Mengembalikan:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


Mengembalikan tabulasi sebuah paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [ITabCollection](../../com.aspose.slides/itabcollection).

**Mengembalikan:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [FontAlignment](../../com.aspose.slides/fontalignment).

**Mengembalikan:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan. Baca/tulis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


Mengembalikan format bagian default sebuah paragraf. Tidak ada pewarisan yang diterapkan. Hanya-baca [IPortionFormat](../../com.aspose.slides/iportionformat).

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan diterapkan.

--------------------

> ```
> Contoh ini menunjukkan cara mendapatkan beberapa properti format paragraf yang efektif.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Sebuah [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long