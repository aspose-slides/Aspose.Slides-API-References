---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli paragraf için tanımlanmış paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtımın uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini almak için [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) yöntemini kullanmanız gerekir; bu yöntem bir [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) örneği döndürür.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBullet()](#getBullet--) | Paragrafın madde işareti biçimini döndürür. |
| [getDepth()](#getDepth--) | Paragrafın derinliğini döndürür veya ayarlar. |
| [setDepth(short value)](#setDepth-short-) | Paragrafın derinliğini döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Paragraftaki metin hizalamasını kalıtım olmadan döndürür veya ayarlar. |
| [setAlignment(int value)](#setAlignment-int-) | Paragraftaki metin hizalamasını kalıtım olmadan döndürür veya ayarlar. |
| [getSpaceWithin()](#getSpaceWithin--) | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. |
| [getSpaceBefore()](#getSpaceBefore--) | İlk satır öncesindeki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | İlk satır öncesindeki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. |
| [getSpaceAfter()](#getSpaceAfter--) | Son satır sonrası boşluk miktarını kalıtım olmadan döndürür veya ayarlar. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Son satır sonrası boşluk miktarını kalıtım olmadan döndürür veya ayarlar. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. |
| [getRightToLeft()](#getRightToLeft--) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. |
| [getMarginLeft()](#getMarginLeft--) | Paragrafta sol kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Paragrafta sol kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. |
| [getMarginRight()](#getMarginRight--) | Paragrafta sağ kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. |
| [setMarginRight(float value)](#setMarginRight-float-) | Paragrafta sağ kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. |
| [getIndent()](#getIndent--) | Paragrafın İlk Satır Girintisi/Sarkan Girintisini kalıtım olmadan döndürür veya ayarlar. |
| [setIndent(float value)](#setIndent-float-) | Paragrafın İlk Satır Girintisi/Sarkan Girintisini kalıtım olmadan döndürür veya ayarlar. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Varsayılan sekme boyutunu kalıtım olmadan döndürür veya ayarlar. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Varsayılan sekme boyutunu kalıtım olmadan döndürür veya ayarlar. |
| [getTabs()](#getTabs--) | Paragrafın sekmelerini döndürür. |
| [getFontAlignment()](#getFontAlignment--) | Paragrafta font hizalamasını kalıtım olmadan döndürür veya ayarlar. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Paragrafta font hizalamasını kalıtım olmadan döndürür veya ayarlar. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Paragrafın varsayılan bölüm biçimini döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Paragrafın madde işareti biçimini döndürür. Yalnızca okunabilir [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Döndürür:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0, tanımsız değeri ifade eder. Okunabilir/yazılabilir kısa.

**Döndürür:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Paragrafın derinliğini döndürür veya ayarlar. Değer 0, tanımsız değeri ifade eder. Okunabilir/yazılabilir kısa.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Paragraftaki metin hizalamasını kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir [TextAlignment](../../com.aspose.slides/textalignment).

**Döndürür:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Paragraftaki metin hizalamasını kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir [TextAlignment](../../com.aspose.slides/textalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzde, negatif değer nokta cinsinden boyuttur. Kalıtım uygulanmaz. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzde, negatif değer nokta cinsinden boyuttur. Kalıtım uygulanmaz. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Paragrafta ilk satır öncesindeki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. Pozitif değer, boşluğun font boyutunun yüzdesini belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Paragrafta ilk satır öncesindeki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. Pozitif değer, boşluğun font boyutunun yüzdesini belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Paragrafta son satır sonrasındaki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. Pozitif değer, boşluğun font boyutunun yüzdesini belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Paragrafta son satır sonrasındaki boşluk miktarını kalıtım olmadan döndürür veya ayarlar. Pozitif değer, boşluğun font boyutunun yüzdesini belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Paragrafta sarkan noktalama işaretinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Paragrafta sol kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Paragrafta sol kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Paragrafta sağ kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Paragrafta sağ kenar boşluğunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Paragrafın İlk Satır Girintisi/Sarkan Girintisini kalıtım olmadan döndürür veya ayarlar. Sarkan girinti negatif değerlerle tanımlanabilir. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Paragrafın İlk Satır Girintisi/Sarkan Girintisini kalıtım olmadan döndürür veya ayarlar. Sarkan girinti negatif değerlerle tanımlanabilir. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Varsayılan sekme boyutunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Varsayılan sekme boyutunu kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ITabCollection](../../com.aspose.slides/itabcollection).

**Döndürür:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Paragrafta font hizalamasını kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir [FontAlignment](../../com.aspose.slides/fontalignment).

**Döndürür:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Paragrafta font hizalamasını kalıtım olmadan döndürür veya ayarlar. Okunabilir/yazılabilir [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IPortionFormat](../../com.aspose.slides/iportionformat).

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır.

**Döndürür:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).