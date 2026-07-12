---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Kalıtım olmadan bir paragrafta madde işareti tipini döndürür veya ayarlar. |
| [setType(byte value)](#setType-byte-) | Kalıtım olmadan bir paragrafta madde işareti tipini döndürür veya ayarlar. |
| [getChar()](#getChar--) | Kalıtım olmadan bir paragrafta madde işareti karakterini döndürür veya ayarlar. |
| [setChar(char value)](#setChar-char-) | Kalıtım olmadan bir paragrafta madde işareti karakterini döndürür veya ayarlar. |
| [getFont()](#getFont--) | Kalıtım olmadan bir paragrafta madde işareti yazı tipini döndürür veya ayarlar. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Kalıtım olmadan bir paragrafta madde işareti yazı tipini döndürür veya ayarlar. |
| [getHeight()](#getHeight--) | Kalıtım olmadan bir paragrafta madde işareti yüksekliğini döndürür veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Kalıtım olmadan bir paragrafta madde işareti yüksekliğini döndürür veya ayarlar. |
| [getColor()](#getColor--) | Kalıtım olmadan bir paragrafta madde işaretinin renk biçimini döndürür. |
| [getPicture()](#getPicture--) | Kalıtım olmadan bir paragrafta madde işareti olarak kullanılan resmi döndürür. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür veya ayarlar. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür veya ayarlar. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Kalıtım olmadan numaralı madde işaretinin stilini döndürür veya ayarlar. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Kalıtım olmadan numaralı madde işaretinin stilini döndürür veya ayarlar. |
| [isBulletHardColor()](#isBulletHardColor--) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. |
| [isBulletHardFont()](#isBulletHardFont--) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Madde işaretleri etkin olduğunda (PowerPoint'in paragraf madde işaretleri/numaralandırmasını etkinleştirdiğinde yaptığı gibi) etkili paragraf Indent ve MarginLeft için sıfır olmayan varsayılan kaymaları ayarlar. Madde işaretleri devre dışı bırakıldığında sadece paragraf Indent ve MarginLeft sıfırlanır (PowerPoint'in madde işaretlerini devre dışı bırakması gibi). Girinti kaymaları mevcut madde işareti bağlamına göre uygulanır - IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight. Sıfır olmayan girinti kaymaları mevcut paragrafın etkili Indent ve MarginLeft değerlerine uygulanır (sonuç değerleri yerel olur). |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili madde işareti biçimlendirme verilerini alır. |
### getType() {#getType--}
```
public abstract byte getType()
```

Kalıtım olmadan bir paragrafta madde işareti tipini döndürür veya ayarlar. Okuma/Yazma [BulletType](../../com.aspose.slides/bullettype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Kalıtım olmadan bir paragrafta madde işareti tipini döndürür veya ayarlar. Okuma/Yazma [BulletType](../../com.aspose.slides/bullettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Kalıtım olmadan bir paragrafta madde işareti karakterini döndürür veya ayarlar. Okuma/Yazma char.

**Döndürür:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Kalıtım olmadan bir paragrafta madde işareti karakterini döndürür veya ayarlar. Okuma/Yazma char.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Kalıtım olmadan bir paragrafta madde işareti yazı tipini döndürür veya ayarlar. Okuma/Yazma [IFontData](../../com.aspose.slides/ifontdata).

**Döndürür:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Kalıtım olmadan bir paragrafta madde işareti yazı tipini döndürür veya ayarlar. Okuma/Yazma [IFontData](../../com.aspose.slides/ifontdata).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Kalıtım olmadan bir paragrafta madde işareti yüksekliğini döndürür veya ayarlar. Float.NaN değeri madde işaretinin yüksekliğini paragraftaki ilk bölüme devraldığını belirler. Okuma/Yazma float.

**Döndürür:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Kalıtım olmadan bir paragrafta madde işareti yüksekliğini döndürür veya ayarlar. Float.NaN değeri madde işaretinin yüksekliğini paragraftaki ilk bölüme devraldığını belirler. Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Kalıtım olmadan bir paragrafta madde işaretinin renk biçimini döndürür. Salt Okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Kalıtım olmadan bir paragrafta madde işareti olarak kullanılan resmi döndürür. Salt Okunur [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür veya ayarlar. Okuma/Yazma short.

**Döndürür:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Kalıtım olmadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür veya ayarlar. Okuma/Yazma short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Kalıtım olmadan numaralı madde işaretinin stilini döndürür veya ayarlar. Okuma/Yazma [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Döndürür:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Kalıtım olmadan numaralı madde işaretinin stilini döndürür veya ayarlar. Okuma/Yazma [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. **NullableBool#True** ise madde işareti kendi rengine sahiptir, **NullableBool#False** ise ilk bölüme göre renk devralır. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. **NullableBool#True** ise madde işareti kendi rengine sahiptir, **NullableBool#False** ise ilk bölüme göre renk devralır. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. **NullableBool#True** ise madde işareti kendi yazı tipine sahiptir, **NullableBool#False** ise ilk bölüme göre yazı tipi devralır. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Madde işaretinin kendi yazı tipinin olup olmadığını veya paragraftaki ilk bölüme göre devralınıp devralınmadığını belirler. **NullableBool#True** ise madde işareti kendi yazı tipine sahiptir, **NullableBool#False** ise ilk bölüme göre yazı tipi devralır. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Madde işaretleri etkin olduğunda (PowerPoint'in paragraf madde işaretleri/numaralandırmasını etkinleştirdiğinde yaptığı gibi) etkili paragraf Indent ve MarginLeft için sıfır olmayan varsayılan kaymaları ayarlar. Madde işaretleri devre dışı bırakıldığında sadece paragraf Indent ve MarginLeft sıfırlanır (PowerPoint'in madde işaretlerini devre dışı bırakması gibi). Girinti kaymaları mevcut madde işareti bağlamına göre uygulanır - IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight. Sıfır olmayan girinti kaymaları mevcut paragrafın etkili Indent ve MarginLeft değerlerine uygulanır (sonuç değerleri yerel olur).
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