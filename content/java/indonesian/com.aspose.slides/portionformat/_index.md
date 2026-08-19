---
title: PortionFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Kelas ini berisi properti pemformatan bagian teks.
type: docs
url: /id/com.aspose.slides/portionformat/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Kelas ini berisi properti pemformatan bagian teks. Tidak seperti [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), semua properti kelas ini dapat ditulis.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Membuat objek presentasi yang mewakili file presentasi
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides menggunakan pengenal khusus ini (mirip dengan yang digunakan di PowerPoint):
>      // +mn-lt - Font Tubuh Latin (Font Latin Minor)
>      // +mj-lt - Font Heading Latin (Font Latin Mayor)
>      // +mn-ea - Font Tubuh Asia Timur (Font Asia Timur Minor)
>      // +mj-ea - Font Tubuh Asia Timur (Font Asia Timur Minor)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan bagian teks yang didefinisikan untuk bagian tertentu. Ini berarti tidak ada warisan yang diterapkan ketika mengambil nilai sehingga pada kebanyakan kasus Anda akan mendapatkan nilai yang berarti "undefined".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda harus menggunakan metode [getEffective](../../com.aspose.slides/portionformat\#getEffective) yang mengembalikan sebuah instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Menginisialisasi sebuah instance baru dari kelas [PortionFormat](../../com.aspose.slides/portionformat). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Mengembalikan atau mengatur pengidentifikasi penanda buku. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Mengembalikan atau mengatur pengidentifikasi penanda buku. |
| [getSmartTagClean()](#getSmartTagClean--) | Menentukan apakah smart tag harus dibersihkan. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Menentukan apakah smart tag harus dibersihkan. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Manajer hyperlink. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan bagian yang efektif dengan warisan yang diterapkan. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Menginisialisasi sebuah instance baru dari kelas [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Mengembalikan atau mengatur pengidentifikasi penanda buku. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Mengembalikan atau mengatur pengidentifikasi penanda buku. Baca/tulis String.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Menentukan apakah smart tag harus dibersihkan. Tidak ada warisan yang diterapkan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Menentukan apakah smart tag harus dibersihkan. Tidak ada warisan yang diterapkan. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |
### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Manajer hyperlink. Hanya Baca [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Mengembalikan:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan bagian yang efektif dengan warisan yang diterapkan.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).