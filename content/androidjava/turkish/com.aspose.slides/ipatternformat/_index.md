---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir şekli doldurmak için deseni temsil eder.
type: docs
url: /tr/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Bir şekli doldurmak için deseni temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Desen stilini alır veya ayarlar. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Desen stilini alır veya ayarlar. |
| [getForeColor()](#getForeColor--) | Ön plan desen rengini döndürür. |
| [getBackColor()](#getBackColor--) | Arka plan desen rengini döndürür. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Belirtilen renklerle desen doldurma için bir döşeme görüntüsü oluşturur. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Desen doldurma için bir döşeme görüntüsü oluşturur. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Desen stilini alır veya ayarlar. Okunur/yazılır [PatternStyle](../../com.aspose.slides/patternstyle).

**Döndürür:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Desen stilini alır veya ayarlar. Okunur/yazılır [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Ön plan desen rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Arka plan desen rengini döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Belirtilen renklerle desen doldurma için bir döşeme görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.lang.Integer | Desen için arka plan java.lang.Integer. |
| foreground | java.lang.Integer | Desen için ön plan java.lang.Integer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Desen doldurma için bir döşeme görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | java.lang.Integer | ShapeEx'in StyleEx nesnesinde tanımlanan varsayılan java.lang.Integer. Doldurmanın renkleri buna bağlı olabilir. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Döşeme android.graphics.Bitmap.