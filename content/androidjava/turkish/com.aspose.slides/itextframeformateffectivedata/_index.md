---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /tr/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Etkili metin çerçevesi biçimlendirme özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [ITextFrameFormat](../../com.aspose.slides/itextframeformat) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns effective text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | Returns if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | Returns if text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Returns text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns text autofit mode. |
| [getColumnCount()](#getColumnCount--) | Specifies the number of columns of text in the bounding rectangle. |
| [getColumnSpacing()](#getColumnSpacing--) | Specifies the space between text columns in the text area (in points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Metnin etkili stilini döndürür. Yalnızca okunabilir [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Metin çerçevesindeki sol kenar boşluğunu (nokta) döndürür. Yalnızca okunabilir double.

**Returns:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Metin çerçevesindeki sağ kenar boşluğunu (nokta) döndürür. Yalnızca okunabilir double.

**Returns:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Metin çerçevesindeki üst kenar boşluğunu (nokta) döndürür. Yalnızca okunabilir double.

**Returns:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Metin çerçevesindeki alt kenar boşluğunu (nokta) döndürür. Yalnızca okunabilir double.

**Returns:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Metin çerçevesinin kenar boşluklarında metnin sarılıp sarılmadığını döndürür. Yalnızca okunabilir boolean.

**Returns:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Metin çerçevesindeki dikey tutma metnini döndürür. Yalnızca okunabilir [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Metnin yatay olarak kutuya ortalanıp ortalanmadığını döndürür. Yalnızca okunabilir boolean.

**Returns:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Metin yönelimini döndürür. Yalnızca okunabilir [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Metin otomatik sığdırma modunu döndürür. Yalnızca okunabilir [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returns:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Sınırlayıcı dikdörtgende metnin sütun sayısını belirtir. Yalnızca okunabilir int.

**Returns:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Metin alanındaki sütunlar arasındaki boşluğu (nokta) belirtir. Yalnızca okunabilir float.

**Returns:**
float