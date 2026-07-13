---
title: IPatternFormat
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta un modello per riempire una forma.
type: docs
url: /it/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Rappresenta un modello per riempire una forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Restituisce o imposta lo stile del modello. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Restituisce o imposta lo stile del modello. |
| [getForeColor()](#getForeColor--) | Restituisce il colore di primo piano del modello. |
| [getBackColor()](#getBackColor--) | Restituisce il colore di sfondo del modello. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Crea un'immagine a tassello per il riempimento a modello con i colori specificati. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Crea un'immagine a tassello per il riempimento a modello. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Restituisce o imposta lo stile del modello. Lettura/Scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Restituisce o imposta lo stile del modello. Lettura/Scrittura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Restituisce il colore di primo piano del modello. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Restituisce il colore di sfondo del modello. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Crea un'immagine a tassello per il riempimento a modello con i colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.lang.Integer | Il java.lang.Integer di sfondo per il modello. |
| foreground | java.lang.Integer | Il java.lang.Integer di primo piano per il modello. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tassello android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Crea un'immagine a tassello per il riempimento a modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | java.lang.Integer | Il java.lang.Integer predefinito, definito nell'oggetto StyleEx di ShapeEx. I colori del riempimento possono dipendere da questo. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tassello android.graphics.Bitmap.