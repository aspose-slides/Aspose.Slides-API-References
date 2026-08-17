---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkin metin çerçevesi biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Etkin metin çerçevesi biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ITextFrameFormat](../../com.aspose.slides/itextframeformat) arayüzüyle birlikte, kalıtım uygulanmış etkin biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Etkin metnin stilini döndürür. |
| [getMarginLeft()](#getMarginLeft--) | Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür. |
| [getMarginRight()](#getMarginRight--) | Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür. |
| [getMarginTop()](#getMarginTop--) | Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür. |
| [getMarginBottom()](#getMarginBottom--) | Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür. |
| [getWrapText()](#getWrapText--) | Metnin TextFrame kenar boşluklarında kaydırılıp kaydırılmadığını döndürür. |
| [getAnchoringType()](#getAnchoringType--) | Bir TextFrame içinde dikey sabit metni döndürür. |
| [getCenterText()](#getCenterText--) | Metnin kutuda yatay olarak ortalanıp ortalanmadığını döndürür. |
| [getTextVerticalType()](#getTextVerticalType--) | Metin yönünü döndürür. |
| [getAutofitType()](#getAutofitType--) | Metin otomatik sığdırma modunu döndürür. |
| [getColumnCount()](#getColumnCount--) | Sınırlayıcı dikdörtgendeki metin sütun sayısını belirtir. |
| [getColumnSpacing()](#getColumnSpacing--) | Metin alanındaki metin sütunları arasındaki boşluğu (nokta olarak) belirtir. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Etkin metnin stilini döndürür. Salt okunur [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Döndürür:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Bir TextFrame içinde sol kenar boşluğunu (nokta) döndürür. Salt okunur double.

**Döndürür:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Bir TextFrame içinde sağ kenar boşluğunu (nokta) döndürür. Salt okunur double.

**Döndürür:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Bir TextFrame içinde üst kenar boşluğunu (nokta) döndürür. Salt okunur double.

**Döndürür:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Bir TextFrame içinde alt kenar boşluğunu (nokta) döndürür. Salt okunur double.

**Döndürür:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Metnin TextFrame kenar boşluklarında kaydırılıp kaydırılmadığını döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Bir TextFrame içinde dikey sabit metni döndürür. Salt okunur [TextAnchorType](../../com.aspose.slides/textanchortype).

**Döndürür:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Metnin kutuda yatay olarak ortalanıp ortalanmadığını döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Metin yönünü döndürür. Salt okunur [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Döndürür:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Metin otomatik sığdırma modunu döndürür. Salt okunur [TextAutofitType](../../com.aspose.slides/textautofittype).

**Döndürür:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Sınırlayıcı dikdörtgendeki metin sütun sayısını belirtir. Salt okunur int.

**Döndürür:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Metin alanındaki metin sütunları arasındaki boşluğu (nokta olarak) belirtir. Salt okunur float.

**Döndürür:**
float