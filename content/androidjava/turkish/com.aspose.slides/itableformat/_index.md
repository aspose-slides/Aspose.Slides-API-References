---
title: ITableFormat
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir tablonun formatını temsil eder.
type: docs
url: /tr/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Bir tablonun formatını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir tablo dolgu özellikleri nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Dolgu renginin saydamlığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Dolgu renginin saydamlığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Bir tablo dolgu özellikleri nesnesi döndürür. Yalnızca okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Dolgu renginin saydamlığını alır veya ayarlar. Okuma/yazma  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Dolgu renginin saydamlığını alır veya ayarlar. Okuma/yazma  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Kalıtım ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır.

**Döndürür:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Bir [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).