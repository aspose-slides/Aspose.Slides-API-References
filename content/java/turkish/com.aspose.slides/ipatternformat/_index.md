---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /tr/com.aspose.slides/ipatternformat/
---
```
public interface IPatternFormat
```

Bir şekli doldurmak için bir deseni temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Desen stilini döndürür veya ayarlar. Okuma/yazma [PatternStyle](../../com.aspose.slides/patternstyle).

**Döndürür:**  
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Desen stilini döndürür veya ayarlar. Okuma/yazma [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Ön plan desen rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Arka plan desen rengini döndürür. Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Belirtilen renklerle desen doldurması için bir karo görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | java.awt.Color | Desenin arka plan java.awt.Color değeri. |
| foreground | java.awt.Color | Desenin ön plan java.awt.Color değeri. |

**Döndürür:**  
[IImage](../../com.aspose.slides/iimage) - Karo java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Desen doldurması için bir karo görüntüsü oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | java.awt.Color | ShapeEx'in StyleEx nesnesinde tanımlı varsayılan java.awt.Color. Doldurmanın renkleri buna bağlı olabilir. |

**Döndürür:**  
[IImage](../../com.aspose.slides/iimage) - Karo java.awt.image.BufferedImage.