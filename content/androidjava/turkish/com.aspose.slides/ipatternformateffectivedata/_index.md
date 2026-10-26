---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Etkili desen doldurma özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Etkili desen doldurma özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) ve [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)'nin bir parçası olarak kullanılır.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Desen stilini döndürür. |
| [getForeColor()](#getForeColor--) | Ön plan desen rengini döndürür. |
| [getBackColor()](#getBackColor--) | Arka plan desen rengini döndürür. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Belirtilen renklerle desen doldurma için bir döşe resmi oluşturur. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Desen stilini döndürür. Salt okunur [PatternStyle](../../com.aspose.slides/patternstyle).

**Döndürür:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Ön plan desen rengini döndürür. Salt okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Arka plan desen rengini döndürür. Salt okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Belirtilen renklerle desen doldurma için bir döşe resmi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.lang.Integer | Desen için arka plan java.lang.Integer. |
| foreground | java.lang.Integer | Desen için ön plan java.lang.Integer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).