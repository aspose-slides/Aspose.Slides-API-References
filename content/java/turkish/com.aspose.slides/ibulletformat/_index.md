---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Paragrafta miras alınmadan madde işareti tipini alır veya ayarlar. |
| [setType(byte value)](#setType-byte-) | Paragrafta miras alınmadan madde işareti tipini alır veya ayarlar. |
| [getChar()](#getChar--) | Paragrafta miras alınmadan madde işareti karakterini alır veya ayarlar. |
| [setChar(char value)](#setChar-char-) | Paragrafta miras alınmadan madde işareti karakterini alır veya ayarlar. |
| [getFont()](#getFont--) | Paragrafta miras alınmadan madde işareti yazı tipini alır veya ayarlar. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Paragrafta miras alınmadan madde işareti yazı tipini alır veya ayarlar. |
| [getHeight()](#getHeight--) | Paragrafta miras alınmadan madde işareti yüksekliğini alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Paragrafta miras alınmadan madde işareti yüksekliğini alır veya ayarlar. |
| [getColor()](#getColor--) | Paragrafta miras alınmadan bir madde işaretinin renk biçimini alır. |
| [getPicture()](#getPicture--) | Paragrafta miras alınmadan madde işareti olarak kullanılan resmi alır. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Paragrafta miras alınmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Paragrafta miras alınmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Paragrafta miras alınmadan numaralı bir madde işaretinin stilini alır veya ayarlar. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Paragrafta miras alınmadan numaralı bir madde işaretinin stilini alır veya ayarlar. |
| [isBulletHardColor()](#isBulletHardColor--) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [isBulletHardFont()](#isBulletHardFont--) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Madde işaretleri etkin olduğunda (PowerPoint’te paragraf madde işareti/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf girintisi ve sol kenar boşluğu için varsayılan sıfır olmayan kaydırmaları ayarlar. |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili madde işareti biçimlendirme verilerini alır. |
### getType() {#getType--}
```
public abstract byte getType()
```


Paragrafta miras alınmadan madde işareti tipini alır veya ayarlar. Okunur/Yazılır [BulletType](../../com.aspose.slides/bullettype).

**Döndürür:**  
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Paragrafta miras alınmadan madde işareti tipini alır veya ayarlar. Okunur/Yazılır [BulletType](../../com.aspose.slides/bullettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Paragrafta miras alınmadan madde işareti karakterini alır veya ayarlar. Okunur/Yazılır char.

**Döndürür:**  
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Paragrafta miras alınmadan madde işareti karakterini alır veya ayarlar. Okunur/Yazılır char.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Paragrafta miras alınmadan madde işareti yazı tipini alır veya ayarlar. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Paragrafta miras alınmadan madde işareti yazı tipini alır veya ayarlar. Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Paragrafta miras alınmadan madde işareti yüksekliğini alır veya ayarlar. Float.NaN değeri, madde işaretinin yüksekliğinin paragraftaki ilk bölümden miras alındığını belirler. Okunur/Yazılır float.

**Döndürür:**  
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Paragrafta miras alınmadan madde işareti yüksekliğini alır veya ayarlar. Float.NaN değeri, madde işaretinin yüksekliğinin paragraftaki ilk bölümden miras alındığını belirler. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Paragrafta miras alınmadan bir madde işaretinin renk biçimini alır. Sadece okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Paragrafta miras alınmadan madde işareti olarak kullanılan resmi alır. Sadece okuma [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Paragrafta miras alınmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. Okunur/Yazılır short.

**Döndürür:**  
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Paragrafta miras alınmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. Okunur/Yazılır short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Paragrafta miras alınmadan numaralı bir madde işaretinin stilini alır veya ayarlar. Okunur/Yazılır [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Döndürür:**  
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Paragrafta miras alınmadan numaralı bir madde işaretinin stilini alır veya ayarlar. Okunur/Yazılır [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool\#True** madde işareti kendi rengindeyse ve **NullableBool\#False** madde işareti paragraftaki ilk bölümden rengi miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**  
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool\#True** madde işareti kendi rengindeyse ve **NullableBool\#False** madde işareti paragraftaki ilk bölümden rengi miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool\#True** madde işareti kendi yazı tipindeyse ve **NullableBool\#False** madde işareti paragraftaki ilk bölümden yazı tipini miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**  
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool\#True** madde işareti kendi yazı tipindeyse ve **NullableBool\#False** madde işareti paragraftaki ilk bölümden yazı tipini miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Madde işaretleri etkin olduğunda (PowerPoint’te paragraf madde işareti/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf girintisi ve sol kenar boşluğu için varsayılan sıfır olmayan kaydırmaları ayarlar. Madde işaretleri devre dışı bırakıldığında yalnızca paragraf girintisi ve sol kenar boşluğu sıfırlanır (PowerPoint’te paragraf madde işareti/numaralandırması devre dışı bırakıldığında olduğu gibi). Girinti kaydırmaları, geçerli madde işareti bağlamına — IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight değerine — göre uygulanır. Sıfır olmayan girinti kaydırmaları, geçerli paragrafın etkili Girinti ve Sol Kenar Boşluğu değerlerine uygulanır (sonuç değerleri yerel değerler olur).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Miras uygulanmış etkili madde işareti biçimlendirme verilerini alır.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).