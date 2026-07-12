---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Etkili paragraf madde işareti biçimlendirme özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Değişmez nesne, etkili paragraf madde işareti biçimlendirme özelliklerini içerir.

--------------------

Bu arayüz, [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)'nin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Bir paragrafın madde işareti türünü döndürür. |
| [getChar()](#getChar--) | Bir paragrafın madde işareti karakterini döndürür. |
| [getActualBulletValue()](#getActualBulletValue--) | Üst paragraf için gerçek madde işareti değerini döndürür. |
| [getFont()](#getFont--) | Bir paragrafın madde işareti yazı tipini döndürür. |
| [getHeight()](#getHeight--) | Bir paragrafın madde işareti yüksekliğini döndürür. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Numara madde işaretleri grubunda kullanılan ilk sayıyı döndürür. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Numara bir madde işaretinin stilini döndürür. |
| [isBulletHardColor()](#isBulletHardColor--) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden devralınıp devralmadığını belirler. |
| [isBulletHardFont()](#isBulletHardFont--) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden devralınıp devralmadığını belirler. |
| [getPicture()](#getPicture--) | Paragrafta madde işareti olarak kullanılan resmi döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir paragrafın madde işareti doldurma biçimini döndürür. |
### getType() {#getType--}
```
public abstract byte getType()
```

Bir paragrafın madde işareti türünü döndürür. Salt okunur [BulletType](../../com.aspose.slides/bullettype).

**Döndürür:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Bir paragrafın madde işareti karakterini döndürür. Salt okunur char.

**Döndürür:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Üst paragraf için gerçek madde işareti değerini döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Bir paragrafın madde işareti yazı tipini döndürür. Salt okunur [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Bir paragrafın madde işareti yüksekliğini döndürür. Salt okunur float.

**Döndürür:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür. Salt okunur short.

**Döndürür:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Numaralı bir madde işaretinin stilini döndürür. Salt okunur [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Döndürür:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden rengi devralıp devralmadığını belirler. Madde işareti kendi rengini taşıyorsa **true**, paragraftaki ilk bölümden rengi devralıyorsa **false** döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden yazı tipini devralıp devralmadığını belirler. Madde işareti kendi yazı tipini taşıyorsa **true**, paragraftaki ilk bölümden yazı tipini devralıyorsa **true** döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Paragrafta madde işareti olarak kullanılan resmi döndürür. Salt okunur [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Döndürür:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Bir paragrafın madde işareti doldurma biçimini döndürür. Salt okunur [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // İlk slaydın ilk şeklinin bazı metin içeren bir AutoShape olduğunu varsayın...
>      // Metin paragraflarının madde işaretleri hakkında bilgi çıktısını al
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)