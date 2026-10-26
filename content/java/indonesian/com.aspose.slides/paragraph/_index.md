---
title: Paragraph
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah paragraf teks.
type: docs
url: /id/com.aspose.slides/paragraph/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Mewakili sebuah paragraf teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Paragraph()](#Paragraph--) | Menginisialisasi sebuah instance baru dari kelas Paragraph dengan properti default. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Konstruktor penyalin yang menginisialisasi sebuah instance baru dari kelas Paragraph. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortions()](#getPortions--) | Mengembalikan koleksi bagian teks. |
| [getParagraphFormat()](#getParagraphFormat--) | Mengembalikan objek pemformatan untuk paragraf ini. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama. |
| [getText()](#getText--) | Mendapatkan atau menetapkan teks polos dari sebuah paragraf. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau menetapkan teks polos dari sebuah paragraf. |
| [getRect()](#getRect--) | Mendapatkan koordinat rect yang membatasi paragraf. |
| [getLinesCount()](#getLinesCount--) | Mendapatkan jumlah baris dalam sebuah paragraf. |
| [getImage()](#getImage--) | Mengembalikan gambar dari paragraf. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Mengembalikan gambar dari paragraf dengan skala yang ditentukan. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah paragraf. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah paragraf. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Menginisialisasi sebuah instance baru dari kelas Paragraph dengan properti default.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Konstruktor penyalin yang menginisialisasi sebuah instance baru dari kelas Paragraph.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Mengembalikan koleksi bagian teks. Hanya-baca [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Mengembalikan:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Mengembalikan objek pemformatan untuk paragraf ini. Hanya-baca [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Objek pemformatan berisi parameter pemformatan yang didefinisikan hanya untuk paragraf saat ini, data yang diwarisi tidak diterapkan.

Untuk mendapatkan nilai efektif termasuk yang diwarisi, gunakan metode [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan pemformatan yang sama.

### getText() {#getText--}
```
public final String getText()
```

Mendapatkan atau menetapkan teks polos dari sebuah paragraf. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Mendapatkan atau menetapkan teks polos dari sebuah paragraf. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Mendapatkan koordinat rect yang membatasi paragraf. Rect mencakup semua baris teks dalam paragraf, termasuk yang kosong.

**Mengembalikan:**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Mendapatkan jumlah baris dalam sebuah paragraf.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int - Jumlah baris dalam paragraf

### getImage() {#getImage--}
```
public final IImage getImage()
```

Mengembalikan gambar dari paragraf.

--------------------

> ```
> Contoh berikut menunjukkan cara merender paragraf sebagai gambar:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Sebuah gambar yang berisi paragraf yang dirender, atau null jika paragraf tidak dapat ditemukan dalam koleksi induknya, tidak memiliki batas render yang valid, atau terjadi kesalahan saat merender gambar.

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Mengembalikan gambar dari paragraf dengan skala yang ditentukan.

--------------------

> ```
> Contoh berikut menunjukkan cara merender setiap paragraf kotak teks pada slide sebagai gambar dengan skala khusus:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Faktor skala horizontal yang diterapkan pada gambar paragraf. |
| scaleY | float | Faktor skala vertikal yang diterapkan pada gambar paragraf. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Sebuah gambar yang berisi paragraf yang dirender, atau null jika paragraf tidak dapat ditemukan dalam koleksi induknya, tidak memiliki batas render yang valid, atau terjadi kesalahan saat merender gambar.

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir.

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah paragraf. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah paragraf. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)