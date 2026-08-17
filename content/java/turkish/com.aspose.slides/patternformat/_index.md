---
title: PatternFormat
second_title: Aspose.Slides için Java API Referansı
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

Bir şekli doldurmak için bir deseni temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Creates a tile image for the pattern fill. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur uzun.

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

Ön plan desen rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Arka plan desen rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Belirtilen renklerle desen doldurması için bir döşeme resmi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.awt.Color | Desen için arka plan java.awt.Color. |
| foreground | java.awt.Color | Desen için ön plan java.awt.Color. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Desen doldurması için bir döşeme resmi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | java.awt.Color | Varsayılan java.awt.Color |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme [IImage](../../com.aspose.slides/iimage).