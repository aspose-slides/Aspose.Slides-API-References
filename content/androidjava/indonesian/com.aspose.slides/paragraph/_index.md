---
title: Paragraph
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili sebuah paragraf teks.
type: docs
url: /id/com.aspose.slides/paragraph/
---
**Warisan:**
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
| [Paragraph()](#Paragraph--) | Menginisialisasi instance baru dari kelas Paragraph dengan properti default. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Konstruktor salin yang menginisialisasi instance baru dari kelas Paragraph. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortions()](#getPortions--) | Mengembalikan koleksi bagian teks. |
| [getParagraphFormat()](#getParagraphFormat--) | Mengembalikan objek format untuk paragraf ini. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan format yang sama. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks biasa dari sebuah paragraf. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks biasa dari sebuah paragraf. |
| [getRect()](#getRect--) | Mendapatkan koordinat rect yang membatasi paragraf. |
| [getLinesCount()](#getLinesCount--) | Mendapatkan jumlah baris dalam paragraf. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah paragraf. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah paragraf. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Menginisialisasi instance baru dari kelas Paragraph dengan properti default.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Konstruktor salin yang menginisialisasi instance baru dari kelas Paragraph.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |
### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Mengembalikan koleksi bagian teks. Baca-saja [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Mengembalikan:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Mengembalikan objek format untuk paragraf ini. Baca-saja [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Objek format berisi parameter format yang didefinisikan hanya untuk paragraf saat ini, data yang diwariskan tidak diterapkan.

Untuk mendapatkan nilai efektif termasuk yang diwariskan, gunakan metode [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan format yang sama.

### getText() {#getText--}
```
public final String getText()
```

Mendapatkan atau mengatur teks biasa dari sebuah paragraf. Baca/tulis String.

Value: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Mendapatkan atau mengatur teks biasa dari sebuah paragraf. Baca/tulis String.

Value: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public final RectF getRect()
```

Mendapatkan koordinat rect yang membatasi paragraf. Rect mencakup semua baris teks dalam paragraf, termasuk yang kosong.

**Mengembalikan:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Mendapatkan jumlah baris dalam paragraf.

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

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah paragraf. Baca-saja [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah paragraf. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)