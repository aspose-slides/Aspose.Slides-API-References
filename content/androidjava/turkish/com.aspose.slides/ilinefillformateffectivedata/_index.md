---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides Android için, Java API Referansı aracılığıyla
description: Etkili satır doldurma özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/ilinefillformateffectivedata/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Etkili satır doldurma özelliklerini içeren değişmez nesne.

--------------------

Bu arabirim, [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) parçası olarak kullanılır.
## Yöntemler

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Dolgu tipini döndürür. |
| [getSolidFillColor()](#getSolidFillColor--) | Katı dolgunun rengini döndürür. |
| [getGradientFormat()](#getGradientFormat--) | Gradient dolgu biçimini döndürür. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu biçimini döndürür. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun bir şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Dolgu tipini döndürür. Salt okunur [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Katı dolgunun rengini döndürür. Salt okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Gradient dolgu biçimini döndürür. Salt okunur [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Döndürür:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Desen dolgu biçimini döndürür. Salt okunur [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Döndürür:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Dolgunun bir şekil ile birlikte döndürülüp döndürülmeyeceğini belirler. Salt okunur boolean.

**Döndürür:**
boolean