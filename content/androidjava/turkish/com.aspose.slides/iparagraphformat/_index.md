---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /tr/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir miras uygulanmadığı anlamına gelir; bu yüzden çoğu durumda değerler "tanımsız" olacaktır.

Miras dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) yöntemini kullanmanız gerekir; bu yöntem bir [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) örneği döndürür.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBullet()](#getBullet--) | Returns bullet format of the paragraph. |
| [getDepth()](#getDepth--) | Returns or sets depth of the paragraph. |
| [setDepth(short value)](#setDepth-short-) | Returns or sets depth of the paragraph. |
| [getAlignment()](#getAlignment--) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [getSpaceWithin()](#getSpaceWithin--) | Returns or sets the amount of space between base lines in a paragraph. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returns or sets the amount of space between base lines in a paragraph. |
| [getSpaceBefore()](#getSpaceBefore--) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [getSpaceAfter()](#getSpaceAfter--) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determines whether the East Asian line break is used in a paragraph. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determines whether the East Asian line break is used in a paragraph. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the Right to Left writing is used in a paragraph. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determines whether the Right to Left writing is used in a paragraph. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determines whether the Latin line break is used in a paragraph. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determines whether the Latin line break is used in a paragraph. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determines whether the hanging punctuation is used in a paragraph. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determines whether the hanging punctuation is used in a paragraph. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin in a paragraph with no inheritance. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returns or sets the left margin in a paragraph with no inheritance. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin in a paragraph with no inheritance. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returns or sets the right margin in a paragraph with no inheritance. |
| [getIndent()](#getIndent--) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [setIndent(float value)](#setIndent-float-) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returns or sets default tabulation size with no inheritance. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returns or sets default tabulation size with no inheritance. |
| [getTabs()](#getTabs--) | Returns tabulations of a paragraph. |
| [getFontAlignment()](#getFontAlignment--) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returns default portion format of a paragraph. |
| [getEffective()](#getEffective--) | Gets effective paragraph formatting data with the inheritance applied. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Paragrafın madde işareti biçimini döndürür. Yalnızca okuma [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Döndürür:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0, tanımsız değeri gösterir. Okunur/yazılır short.

**Döndürür:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0, tanımsız değeri gösterir. Okunur/yazılır short.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Paragrafta miras uygulanmadan metin hizalamasını döndürür veya ayarlar. Okunur/yazılır [TextAlignment](../../com.aspose.slides/textalignment).

**Döndürür:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Paragrafta miras uygulanmadan metin hizalamasını döndürür veya ayarlar. Okunur/yazılır [TextAlignment](../../com.aspose.slides/textalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Paragrafta temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzdeyi, negatif değer ise puan cinsinden boyutu gösterir. Miras uygulanmaz. Okunur/yazılır float.

**Döndürür:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Paragrafta temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzdeyi, negatif değer ise puan cinsinden boyutu gösterir. Miras uygulanmaz. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Paragrafta ilk satırdan önceki boşluk miktarını miras olmadan döndürür veya ayarlar. Pozitif değer, boşluğun yüzde olarak font boyutuna oranını, negatif değer ise puan cinsinden boyutunu belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Paragrafta ilk satırdan önceki boşluk miktarını miras olmadan döndürür veya ayarlar. Pozitif değer, boşluğun yüzde olarak font boyutuna oranını, negatif değer ise puan cinsinden boyutunu belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Paragrafta son satırdan sonraki boşluk miktarını miras olmadan döndürür veya ayarlar. Pozitif değer, boşluğun yüzde olarak font boyutuna oranını, negatif değer ise puan cinsinden boyutunu belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Paragrafta son satırdan sonraki boşluk miktarını miras olmadan döndürür veya ayarlar. Pozitif değer, boşluğun yüzde olarak font boyutuna oranını, negatif değer ise puan cinsinden boyutunu belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Paragrafta Doğu Asya satır sonu kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Paragrafta Doğu Asya satır sonu kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Paragrafta Sağdan Sola yazım kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Paragrafta Sağdan Sola yazım kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Paragrafta Latin satır sonu kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Paragrafta Latin satır sonu kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Paragrafta sarkıtılmış noktalama kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Paragrafta sarkıtılmış noktalama kullanımını belirler. Miras uygulanmaz. Okunur/yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Paragrafta miras olmadan sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Paragrafta miras olmadan sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Paragrafta miras olmadan sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Paragrafta miras olmadan sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Paragrafın İlk Satır Girintisi/Sarkıtılmış Girintisini miras olmadan döndürür veya ayarlar. Sarkıtılmış girinti negatif değerlerle tanımlanabilir. Okunur/yazılır float.

**Döndürür:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Paragrafın İlk Satır Girintisi/Sarkıtılmış Girintisini miras olmadan döndürür veya ayarlar. Sarkıtılmış girinti negatif değerlerle tanımlanabilir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Miras olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Miras olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Paragrafta sekmeleri döndürür. Miras uygulanmaz. Yalnızca okuma [ITabCollection](../../com.aspose.slides/itabcollection).

**Döndürür:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Miras olmadan bir yazı tipi hizalamasını döndürür veya ayarlar. Okunur/yazılır [FontAlignment](../../com.aspose.slides/fontalignment).

**Döndürür:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Miras olmadan bir yazı tipi hizalamasını döndürür veya ayarlar. Okunur/yazılır [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Paragrafın varsayılan parça biçimini döndürür. Miras uygulanmaz. Yalnızca okuma [IPortionFormat](../../com.aspose.slides/iportionformat).

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Miras uygulanmış etkili paragraf biçimlendirme verilerini alır.

**Döndürür:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).