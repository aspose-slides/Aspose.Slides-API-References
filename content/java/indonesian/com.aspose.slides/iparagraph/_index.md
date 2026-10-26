---
title: IParagraph
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili paragraf dari sebuah teks.
type: docs
url: /id/com.aspose.slides/iparagraph/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Mewakili paragraf dari sebuah teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortions()](#getPortions--) | Mengembalikan koleksi bagian teks. |
| [getParagraphFormat()](#getParagraphFormat--) | Mengembalikan objek format untuk paragraf ini. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan format yang sama. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks polos dari sebuah paragraf. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks polos dari sebuah paragraf. |
| [getRect()](#getRect--) | Mendapatkan koordinat persegi panjang yang membatasi paragraf. |
| [getLinesCount()](#getLinesCount--) | Mendapatkan jumlah baris dalam sebuah paragraf. |
| [getImage()](#getImage--) | Mengembalikan gambar dari paragraf. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Mengembalikan gambar dari paragraf dengan skala yang ditentukan. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Menentukan properti bagian yang akan digunakan jika bagian lain disisipkan setelah yang terakhir. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Mengembalikan koleksi bagian teks. Baca-saja [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Mengembalikan:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Mengembalikan objek format untuk paragraf ini. Baca-saja [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan format yang sama.

### getText() {#getText--}
```
public abstract String getText()
```

Mendapatkan atau mengatur teks polos dari sebuah paragraf. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Mendapatkan atau mengatur teks polos dari sebuah paragraf. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Mendapatkan koordinat persegi panjang yang membatasi paragraf. Persegi panjang mencakup semua baris teks dalam paragraf, termasuk yang kosong.

**Mengembalikan:**
java.awt.geom.Rectangle2D.Float - Persegi panjang yang membatasi paragraf java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IImage getImage()
```

Mengembalikan gambar dari paragraf.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
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
[IImage](../../com.aspose.slides/iimage) - Sebuah gambar yang berisi paragraf yang dirender, atau null jika paragraf tidak dapat ditemukan dalam koleksi induknya, tidak memiliki batas rendering yang valid, atau terjadi error saat merender gambar.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Mengembalikan gambar dari paragraf dengan skala yang ditentukan.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
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
[IImage](../../com.aspose.slides/iimage) - Sebuah gambar yang berisi paragraf yang dirender, atau null jika paragraf tidak dapat ditemukan dalam koleksi induknya, tidak memiliki batas rendering yang valid, atau terjadi error saat merender gambar.
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