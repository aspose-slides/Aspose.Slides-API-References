---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili satır doldurma özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/ilinefillformateffectivedata/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Etkili satır doldurma özelliklerini içeren değişmez nesne.

--------------------

Bu arabirim [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) öğesinin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillType()](#getFillType--) | Doldurma tipini döndürür. |
| [getSolidFillColor()](#getSolidFillColor--) | Katı doldurmanın rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan doldurma biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen doldurma biçimini döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Doldurmanın bir şekille birlikte döndürülüp döndürülmeyeceğini belirler. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Doldurma tipini döndürür. Salt okunur [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


Katı doldurmanın rengini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gradyan doldurma biçimini döndürür. Salt okunur [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Döndürür:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Desen doldurma biçimini döndürür. Salt okunur [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Döndürür:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Doldurmanın bir şekille birlikte döndürülüp döndürülmeyeceğini belirler. Salt okunur boolean.

**Döndürür:**
boolean