---
title: TextStyle
second_title: Aspose.Slides for Android Java API Referansı ile
description: Bu sınıf, metin stili biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/textstyle/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Bu sınıf metin stili biçimlendirme özelliklerini içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Stilin seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Varsayılan paragraf özellikleri. |
| [getEffective()](#getEffective--) | Uygulanan kalıtımla etkili metin stili biçimlendirme verilerini alır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur uzun.

**Döndürür:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Stil seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Seviyenin sıfır tabanlı indeksi. 0..8 aralığında olmalıdır. |

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - [IParagraphFormat](../../com.aspose.slides/iparagraphformat) seviyesinin biçimlendirmesi.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Varsayılan paragraf özellikleri. Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Uygulanan kalıtımla etkili metin stili biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
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


**Döndürür:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Bir [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).