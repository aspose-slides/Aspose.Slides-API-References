---
title: PatternFormat
second_title: Aspose.Slides for Android Java API Referansı
description: Bir şekli doldurmak için bir deseni temsil eder.
type: docs
url: /tr/com.aspose.slides/patternformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Bir şekli doldurmak için bir desen temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Desen stilini döndürür veya ayarlar. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Desen stilini döndürür veya ayarlar. |
| [getForeColor()](#getForeColor--) | Ön plan desen rengini döndürür. |
| [getBackColor()](#getBackColor--) | Arka plan desen rengini döndürür. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Belirtilen renklerle desen doldurması için bir döşeme görüntüsü oluşturur. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Desen doldurması için bir döşeme görüntüsü oluşturur. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunur long.

**Döndürür:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Desen stilini döndürür veya ayarlar. Okunur/yazılır [PatternStyle](../../com.aspose.slides/patternstyle).

**Döndürür:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Desen stilini döndürür veya ayarlar. Okunur/yazılır [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Ön plan desen rengini döndürür. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Arka plan desen rengini döndürür. Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Belirtilen renklerle desen doldurması için bir döşeme görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.lang.Integer | Desen için arka plan java.lang.Integer. |
| foreground | java.lang.Integer | Desen için ön plan java.lang.Integer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Desen doldurması için bir döşeme görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | java.lang.Integer | Varsayılan java.lang.Integer |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme [IImage](../../com.aspose.slides/iimage).