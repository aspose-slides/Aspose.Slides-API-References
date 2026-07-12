---
title: BulletFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/bulletformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Kalıtım olmadan bir paragrafın madde işareti tipini alır veya ayarlar. |
| [setType(byte value)](#setType-byte-) | Kalıtım olmadan bir paragrafın madde işareti tipini alır veya ayarlar. |
| [getChar()](#getChar--) | Kalıtım olmadan bir paragrafın madde işareti karakterini alır veya ayarlar. |
| [setChar(char value)](#setChar-char-) | Kalıtım olmadan bir paragrafın madde işareti karakterini alır veya ayarlar. |
| [getFont()](#getFont--) | Kalıtım olmadan bir paragrafın madde işareti yazı tipini alır veya ayarlar. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Kalıtım olmadan bir paragrafın madde işareti yazı tipini alır veya ayarlar. |
| [getHeight()](#getHeight--) | Kalıtım olmadan bir paragrafın madde işareti yüksekliğini alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Kalıtım olmadan bir paragrafın madde işareti yüksekliğini alır veya ayarlar. |
| [getColor()](#getColor--) | Kalıtım olmadan bir paragrafın madde işareti renginin biçimini alır. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı alır veya ayarlar. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Kalıtım olmadan bir numaralı madde işaretinin stilini alır veya ayarlar. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Kalıtım olmadan bir numaralı madde işaretinin stilini alır veya ayarlar. |
| [isBulletHardColor()](#isBulletHardColor--) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [isBulletHardFont()](#isBulletHardFont--) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. |
| [getPicture()](#getPicture--) | Kalıtım olmadan bir paragrafta madde işareti olarak kullanılan resmi alır. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Madde işaretleri etkin olduğunda (PowerPoint'te paragraf madde işaretleri/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf Girinti ve Sol Marjin için sıfır olmayan varsayılan kaymaları ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili madde işareti biçimlendirme verilerini alır. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Okunur/Yazılır [BulletType](../../com.aspose.slides/bullettype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Okunur/Yazılır [BulletType](../../com.aspose.slides/bullettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

Okunur/Yazılır  char .

**Döndürür:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Okunur/Yazılır  char .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Okunur/Yazılır [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Okunur/Yazılır  float .

Float.NaN değeri, madde işaretinin yüksekliğinin paragraftaki ilk bölümden miras alındığını belirler.

--------------------

Negatif bir yükseklik değeri, yüksekliğin puan cinsinden verildiği anlamına gelir ve pozitif bir değer, yüksekliğin çevre metnin yüzdesi olduğu anlamına gelir.

**Döndürür:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Okunur/Yazılır  float .

Float.NaN değeri, madde işaretinin yüksekliğinin paragraftaki ilk bölümden miras alındığını belirler.

--------------------

Negatif bir yükseklik değeri, yüksekliğin puan cinsinden verildiği anlamına gelir ve pozitif bir değer, yüksekliğin çevre metnin yüzdesi olduğu anlamına gelir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Okunur/Yazılır  short .

**Döndürür:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Okunur/Yazılır  short .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Okunur/Yazılır [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Döndürür:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Okunur/Yazılır [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool.True** eğer madde işareti kendi rengine sahipse ve **NullableBool.False** eğer madde işareti rengini paragraftaki ilk bölümden miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool.True** eğer madde işareti kendi rengine sahipse ve **NullableBool.False** eğer madde işareti rengini paragraftaki ilk bölümden miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool.True** eğer madde işareti kendi yazı tipine sahipse ve **NullableBool.False** eğer madde işareti yazı tipini paragraftaki ilk bölümden miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **NullableBool.True** eğer madde işareti kendi yazı tipine sahipse ve **NullableBool.False** eğer madde işareti yazı tipini paragraftaki ilk bölümden miras alıyorsa. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Salt okunur [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Madde işaretleri etkin olduğunda (PowerPoint'te paragraf madde işaretleri/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf Girinti ve Sol Marjin için sıfır olmayan varsayılan kaymaları ayarlar. Eğer madde işaretleri devre dışı bırakılırsa sadece paragraf Girinti ve Sol Marjin sıfırlanır (PowerPoint'te paragraf madde işaretleri/numaralandırması devre dışı bırakıldığında olduğu gibi). Girinti kaymaları mevcut madde işareti bağlamına göre uygulanır - IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight. Sıfır olmayan girinti kaymaları mevcut paragrafın etkili Girinti ve Sol Marjinine uygulanır (sonuç değerlerini yerel değerler yapar).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili madde işareti biçimlendirme verilerini alır.

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
### getVersion() {#getVersion--}
```
public long getVersion()
```

Salt okunur long.

**Döndürür:**
long