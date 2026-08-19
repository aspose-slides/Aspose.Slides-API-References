---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un pattern per riempire una forma.
type: docs
url: /it/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Rappresenta un pattern per riempire una forma.
## Metodi

| Metodo | Descrizione |
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


Restituisce o imposta lo stile del pattern. Lettura/scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Restituisce o imposta lo stile del pattern. Lettura/scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Restituisce il colore del pattern in primo piano. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Restituisce il colore del pattern di sfondo. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


Crea un'immagine tile per il riempimento a pattern con colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.awt.Color | Il colore java.awt.Color di sfondo per il pattern. |
| foreground | java.awt.Color | Il colore java.awt.Color in primo piano per il pattern. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


Crea un'immagine tile per il riempimento a pattern.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.awt.Color | Il colore java.awt.Color predefinito, definito nell'oggetto StyleEx di ShapeEx. I colori del riempimento possono dipendere da questo. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.