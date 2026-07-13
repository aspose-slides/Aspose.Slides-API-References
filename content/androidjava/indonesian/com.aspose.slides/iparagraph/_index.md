---
title: IParagraph
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sebuah paragraf teks.
type: docs
url: /id/com.aspose.slides/iparagraph/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Mewakili sebuah paragraf teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortions()](#getPortions--) | Mengembalikan koleksi potongan teks. |
| [getParagraphFormat()](#getParagraphFormat--) | Mengembalikan objek pemformatan untuk paragraf ini. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks biasa paragraf. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks biasa paragraf. |
| [getRect()](#getRect--) | Mendapatkan koordinat rect yang membatasi paragraf. |
| [getLinesCount()](#getLinesCount--) | Mendapatkan jumlah baris dalam paragraf. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Mengembalikan koleksi potongan teks. Hanya baca [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Mengembalikan:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Mengembalikan objek pemformatan untuk paragraf ini. Hanya baca [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Menggabungkan run dengan pemformatan yang sama.

### getText() {#getText--}
```
public abstract String getText()
```


Mendapatkan atau mengatur teks biasa paragraf. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Mendapatkan atau mengatur teks biasa paragraf. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Mendapatkan koordinat rect yang membatasi paragraf. Rect mencakup semua baris teks dalam paragraf, termasuk yang kosong.

**Mengembalikan:**
android.graphics.RectF - Rectangle yang membatasi paragraf android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir.

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |