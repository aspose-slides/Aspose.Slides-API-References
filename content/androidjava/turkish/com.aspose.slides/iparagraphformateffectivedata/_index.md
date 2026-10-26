---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android için Java API Referansı
description: Etkili paragraf biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Etkili paragraf biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IParagraphFormat](../../com.aspose.slides/iparagraphformat) arayüzü ile birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBullet()](#getBullet--) | Bir paragrafın madde işareti biçimini döndürür. |
| [getDepth()](#getDepth--) | Bir paragrafın derinliğini döndürür. |
| [getAlignment()](#getAlignment--) | Bir paragraftaki metin hizalamasını döndürür. |
| [getSpaceWithin()](#getSpaceWithin--) | Bir paragrafta temel satırlar arasındaki boşluk miktarını döndürür. |
| [getSpaceBefore()](#getSpaceBefore--) | Bir paragrafta ilk satırdan önceki boşluk miktarını döndürür. |
| [getSpaceAfter()](#getSpaceAfter--) | Bir paragrafta son satırdan sonraki boşluk miktarını döndürür. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Bir paragrafta Doğu Asya satır sonu kullanımının olup olmadığını belirler. |
| [getRightToLeft()](#getRightToLeft--) | Bir paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Bir paragrafta Latin satır sonu kullanımının olup olmadığını belirler. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Bir paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. |
| [getMarginLeft()](#getMarginLeft--) | Bir paragrafta sol kenar boşluğunu döndürür. |
| [getMarginRight()](#getMarginRight--) | Bir paragrafta sağ kenar boşluğunu döndürür. |
| [getIndent()](#getIndent--) | Paragrafın İlk Satır Girintisini/Sarkan Girintiyi döndürür. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Varsayılan sekme boyutunu döndürür. |
| [getTabs()](#getTabs--) | Bir paragrafın sekmelerini döndürür. |
| [getFontAlignment()](#getFontAlignment--) | Bir paragrafta yazı tipi hizalamasını döndürür. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Bir paragrafın varsayılan bölüm biçimini döndürür. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Bir paragrafın madde işareti biçimini döndürür. Salt okunur [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Döndürür:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Bir paragrafın derinliğini döndürür. Salt okunur short.

**Döndürür:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Bir paragraftaki metin hizalamasını döndürür. Salt okunur [TextAlignment](../../com.aspose.slides/textalignment).

**Döndürür:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Bir paragrafta temel satırlar arasındaki boşluk miktarını döndürür. Salt okunur float.

**Döndürür:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Bir paragrafta ilk satırdan önceki boşluk miktarını döndürür. Salt okunur float.

**Döndürür:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Bir paragrafta son satırdan sonraki boşluk miktarını döndürür. Salt okunur float.

**Döndürür:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Bir paragrafta Doğu Asya satır sonu kullanımının olup olmadığını belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Bir paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Bir paragrafta Latin satır sonu kullanımının olup olmadığını belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Bir paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Döndürür:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Bir paragrafta sol kenar boşluğunu döndürür. Salt okunur float.

**Döndürür:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Bir paragrafta sağ kenar boşluğunu döndürür. Salt okunur float.

**Döndürür:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Paragrafın İlk Satır Girintisini/Sarkan Girintiyi döndürür. Sarkan Girinti negatif değerlerle tanımlanabilir. Salt okunur float.

**Döndürür:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Varsayılan sekme boyutunu döndürür. Salt okunur float.

**Döndürür:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Bir paragrafın sekmelerini döndürür. Salt okunur ITabEffectiveData[].

**Döndürür:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Bir paragrafta yazı tipi hizalamasını döndürür. Salt okunur [FontAlignment](../../com.aspose.slides/fontalignment).

**Döndürür:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Bir paragrafın varsayılan bölüm biçimini döndürür. Salt okunur [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Döndürür:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)