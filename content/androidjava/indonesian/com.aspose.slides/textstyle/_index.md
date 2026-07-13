---
title: TextStyle
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Kelas ini berisi properti pemformatan gaya teks.
type: docs
url: /id/com.aspose.slides/textstyle/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Kelas ini berisi properti pemformatan gaya teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Jika level gaya ada, mengembalikannya, jika tidak mengembalikan null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Properti paragraf default. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan gaya teks efektif dengan pewarisan yang diterapkan. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

Jika level gaya ada, mengembalikannya, jika tidak mengembalikan null.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol level. Harus berada dalam interval 0..8. |

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Pemformatan level [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

Properti paragraf default. Baca-saja [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Mengembalikan:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

Mendapatkan data pemformatan gaya teks efektif dengan pewarisan yang diterapkan.

--------------------

> ```
> Contoh ini menunjukkan cara mendapatkan beberapa properti gaya teks yang efektif.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Sebuah [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).