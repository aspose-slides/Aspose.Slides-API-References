---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili desen doldurma özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Etkili desen doldurma özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) ve [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) öğelerinin bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Desen stilini döndürür. |
| [getForeColor()](#getForeColor--) | Ön plan desen rengini döndürür. |
| [getBackColor()](#getBackColor--) | Arka plan desen rengini döndürür. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Belirtilen renklerle desen doldurması için bir döşeme resmi oluşturur. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Desen stilini döndürür. Salt okunur [PatternStyle](../../com.aspose.slides/patternstyle).

**Döndürür:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Ön plan desen rengini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Arka plan desen rengini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Belirtilen renklerle desen doldurması için bir döşeme resmi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.awt.Color | Desen için arka plan java.awt.Color. |
| foreground | java.awt.Color | Desen için ön plan java.awt.Color. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).