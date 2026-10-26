---
title: PatternFormat
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un motivo per riempire una forma.
type: docs
url: /it/com.aspose.slides/patternformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Rappresenta un motivo per riempire una forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Restituisce o imposta lo stile del motivo. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Restituisce o imposta lo stile del motivo. |
| [getForeColor()](#getForeColor--) | Restituisce il colore del motivo in primo piano. |
| [getBackColor()](#getBackColor--) | Restituisce il colore del motivo di sfondo. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Crea un'immagine a tasselli per il riempimento a motivo con colori specificati. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Crea un'immagine a tasselli per il riempimento a motivo. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Restituisce o imposta lo stile del motivo. Lettura/Scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Restituisce o imposta lo stile del motivo. Lettura/Scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Restituisce il colore del motivo in primo piano. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Restituisce il colore del motivo di sfondo. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Crea un'immagine a tasselli per il riempimento a motivo con colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.awt.Color | Il colore java.awt.Color di sfondo per il motivo. |
| foreground | java.awt.Color | Il colore java.awt.Color di primo piano per il motivo. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tassello [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Crea un'immagine a tasselli per il riempimento a motivo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.awt.Color | Il java.awt.Color predefinito |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tassello [IImage](../../com.aspose.slides/iimage).