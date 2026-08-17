---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Etkili paragraf maddeleme biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Etkili paragraf maddeleme biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) parçası olarak kullanılır.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Bir paragrafın madde işareti tipini döndürür. |
| [getChar()](#getChar--) | Bir paragrafın madde işareti karakterini döndürür. |
| [getActualBulletValue()](#getActualBulletValue--) | Üst paragraf için gerçek madde işareti değerini döndürür. |
| [getFont()](#getFont--) | Bir paragrafın madde işareti yazı tipini döndürür. |
| [getHeight()](#getHeight--) | Bir paragrafın madde işareti yüksekliğini döndürür. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Numaralı bir madde işaretinin stilini döndürür. |
| [isBulletHardColor()](#isBulletHardColor--) | Madde işaretinin kendi renginin olup olmadığını ya da paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [isBulletHardFont()](#isBulletHardFont--) | Madde işaretinin kendi yazı tipine sahip olup olmadığını ya da paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [getPicture()](#getPicture--) | Paragrafta madde işareti olarak kullanılan resmi döndürür. |
| [getFillFormat()](#getFillFormat--) | Bir paragrafın madde işareti dolgu biçimini döndürür. |
### getType() {#getType--}
```
public abstract byte getType()
```

Bir paragrafın madde işareti tipini döndürür. Yalnızca okuma [BulletType](../../com.aspose.slides/bullettype).

**Döndürür:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Bir paragrafın madde işareti karakterini döndürür. Yalnızca okuma char.

**Döndürür:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Üst paragraf için gerçek madde işareti değerini döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Bir paragrafın madde işareti yazı tipini döndürür. Yalnızca okuma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Bir paragrafın madde işareti yüksekliğini döndürür. Yalnızca okuma float.

**Döndürür:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür. Yalnızca okuma short.

**Döndürür:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Numaralı bir madde işaretinin stilini döndürür. Yalnızca okuma [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Döndürür:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Madde işaretinin kendi renginin olup olmadığını ya da paragraftaki ilk bölümden miras alıp almadığını belirler. Madde işareti kendi rengine sahipse **true**, paragraftaki ilk bölümden rengi miras alıyorsa **false** döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Madde işaretinin kendi yazı tipine sahip olup olmadığını ya da paragraftaki ilk bölümden miras alıp almadığını belirler. Madde işareti kendi yazı tipine sahipse **true**, paragraftaki ilk bölümden yazı tipini miras alıyorsa **true** döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Paragrafta madde işareti olarak kullanılan resmi döndürür. Yalnızca okuma [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Döndürür:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Bir paragrafın madde işareti dolgu biçimini döndürür. Yalnızca okuma [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // İlk slayttaki ilk şeklin bazı metin içeren bir AutoShape olduğu varsayılıyor...
>      // Metin paragraflarının madde işaretleri hakkında bilgi çıktısı
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
```

**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)