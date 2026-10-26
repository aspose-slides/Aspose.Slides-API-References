---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /tr/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Bir tablonun biçimini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Bir tablo doldurma özelliği nesnesi döndürür. |
| [getTransparency()](#getTransparency--) | Doldurma renginin şeffaflığını alır veya ayarlar. |
| [setTransparency(float value)](#setTransparency-float-) | Doldurma renginin şeffaflığını alır veya ayarlar. |
| [getEffective()](#getEffective--) | Miras ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Bir tablo doldurma özelliği nesnesi döndürür. Yalnızca okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Doldurma renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Döndürür:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Doldurma renginin şeffaflığını alır veya ayarlar. Okuma/yazma  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Miras ve tablo stilleri uygulanmış etkili tablo biçimlendirme özelliklerini alır.

**Döndürür:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Bir [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).