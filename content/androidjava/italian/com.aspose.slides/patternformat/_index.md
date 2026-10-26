---
title: PatternFormat
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta un modello per riempire una forma.
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

Rappresenta un modello per riempire una forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Restituisce o imposta lo stile del modello. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Restituisce o imposta lo stile del modello. |
| [getForeColor()](#getForeColor--) | Restituisce il colore di primo piano del modello. |
| [getBackColor()](#getBackColor--) | Restituisce il colore di sfondo del modello. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Crea un'immagine tile per il riempimento a motivo con colori specificati. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Crea un'immagine tile per il riempimento a motivo. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Long di sola lettura.

**Restituisce:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Restituisce o imposta lo stile del modello. Lettura/scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Restituisce o imposta lo stile del modello. Lettura/scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Restituisce il colore di primo piano del modello. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Restituisce il colore di sfondo del modello. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Crea un'immagine tile per il riempimento a motivo con colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.lang.Integer | Il java.lang.Integer di sfondo per il modello. |
| foreground | java.lang.Integer | Il java.lang.Integer di primo piano per il modello. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Piastrella [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Crea un'immagine tile per il riempimento a motivo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.lang.Integer | Il java.lang.Integer predefinito |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Piastrella [IImage](../../com.aspose.slides/iimage).