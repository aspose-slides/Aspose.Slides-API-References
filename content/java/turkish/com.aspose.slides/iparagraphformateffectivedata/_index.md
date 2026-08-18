---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /tr/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Etkili paragraf biçimlendirme özelliklerini içeren değişmez nesne.

--------------------

Bu arayüz, [IParagraphFormat](../../com.aspose.slides/iparagraphformat) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [getBullet()](#getBullet--) | Returns a bullet format of a paragraph. |
| [getDepth()](#getDepth--) | Returns a depth of a paragraph. |
| [getAlignment()](#getAlignment--) | Returns the text alignment in a paragraph. |
| [getSpaceWithin()](#getSpaceWithin--) | Returns the amount of space between base lines in a paragraph. |
| [getSpaceBefore()](#getSpaceBefore--) | Returns the amount of space before the first line in a paragraph. |
| [getSpaceAfter()](#getSpaceAfter--) | Returns the amount of space after the last line in a paragraph. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determines whether the East Asian line break is used in a paragraph. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the Right to Left writing is used in a paragraph. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determines whether the Latin line break is used in a paragraph. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determines whether the hanging punctuation is used in a paragraph. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin in a paragraph. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin in a paragraph. |
| [getIndent()](#getIndent--) | Returns paragraph First Line Indent/Hanging Indent. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returns default tabulation size. |
| [getTabs()](#getTabs--) | Returns tabulations of a paragraph. |
| [getFontAlignment()](#getFontAlignment--) | Returns a font alignment in a paragraph. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returns default portion format of a paragraph. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Bir paragrafın madde işareti biçimini döndürür. Salt okunur [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Bir paragrafın derinliğini döndürür. Salt okunur short.

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Paragraftaki metin hizalamasını döndürür. Salt okunur [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür. Salt okunur float.

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Paragraftaki ilk satırdan önceki boşluk miktarını döndürür. Salt okunur float.

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Paragraftaki son satırdan sonraki boşluk miktarını döndürür. Salt okunur float.

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Paragrafta asılı noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Salt okunur boolean.

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Paragraftaki sol kenar boşluğunu döndürür. Salt okunur float.

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Paragraftaki sağ kenar boşluğunu döndürür. Salt okunur float.

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Paragrafın İlk Satır Girintisi/Asılı Girintisini döndürür. Asılı Girinti negatif değerlerle tanımlanabilir. Salt okunur float.

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Varsayılan sekme boyutunu döndürür. Salt okunur float.

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Paragraftaki sekmeleri döndürür. Salt okunur ITabEffectiveData[].

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Paragrafta bir yazı tipi hizalamasını döndürür. Salt okunur [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Paragrafta varsayılan bölüm biçimini döndürür. Salt okunur [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)