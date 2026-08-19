---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /it/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), tutte le proprietà di questa classe sono modificabili.

--------------------

Questa classe è utilizzata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che non viene applicata alcuna eredità quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che indicano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione, inclusi quelli ereditati, è necessario utilizzare il metodo [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) che restituisce un'istanza [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBullet()](#getBullet--) | Restituisce il formato del punto elenco del paragrafo. |
| [getDepth()](#getDepth--) | Restituisce o imposta la profondità del paragrafo. |
| [setDepth(short value)](#setDepth-short-) | Restituisce o imposta la profondità del paragrafo. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta l'allineamento del testo in un paragrafo senza eredità. |
| [setAlignment(int value)](#setAlignment-int-) | Restituisce o imposta l'allineamento del testo in un paragrafo senza eredità. |
| [getSpaceWithin()](#getSpaceWithin--) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza eredità. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza eredità. |
| [getSpaceAfter()](#getSpaceAfter--) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza eredità. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza eredità. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se il ritorno a capo asiatica orientale è usato in un paragrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina se il ritorno a capo asiatica orientale è usato in un paragrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se il ritorno a capo latino è usato in un paragrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina se il ritorno a capo latino è usato in un paragrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se la punteggiatura sospesa è usata in un paragrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina se la punteggiatura sospesa è usata in un paragrafo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro in un paragrafo senza eredità. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Restituisce o imposta il margine sinistro in un paragrafo senza eredità. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro in un paragrafo senza eredità. |
| [setMarginRight(float value)](#setMarginRight-float-) | Restituisce o imposta il margine destro in un paragrafo senza eredità. |
| [getIndent()](#getIndent--) | Restituisce o imposta l'Indentazione Prima Linea/Indentazione Sospesa del paragrafo senza eredità. |
| [setIndent(float value)](#setIndent-float-) | Restituisce o imposta l'Indentazione Prima Linea/Indentazione Sospesa del paragrafo senza eredità. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Restituisce o imposta la dimensione di tabulazione predefinita senza eredità. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Restituisce o imposta la dimensione di tabulazione predefinita senza eredità. |
| [getTabs()](#getTabs--) | Restituisce le tabulazioni di un paragrafo. |
| [getFontAlignment()](#getFontAlignment--) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza eredità. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza eredità. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Restituisce il formato della porzione predefinita di un paragrafo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del paragrafo effettivi con l'eredità applicata. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Restituisce il formato del punto elenco del paragrafo. Sola lettura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Restituisce:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Restituisce o imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Lettura/scrittura short.

**Restituisce:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Restituisce o imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Lettura/scrittura short.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Restituisce o imposta l'allineamento del testo in un paragrafo senza eredità. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

**Restituisce:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Restituisce o imposta l'allineamento del testo in un paragrafo senza eredità. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, un valore negativo la dimensione in punti. Nessuna eredità applicata. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, un valore negativo la dimensione in punti. Nessuna eredità applicata. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza eredità. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occuparre. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza eredità. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occuparre. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza eredità. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occuparre. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza eredità. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occuparre. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Determina se il ritorno a capo asiatica orientale è usato in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Determina se il ritorno a capo asiatica orientale è usato in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Determina se il ritorno a capo latino è usato in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Determina se il ritorno a capo latino è usato in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Determina se la punteggiatura sospesa è usata in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Determina se la punteggiatura sospesa è usata in un paragrafo. Nessuna eredità applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Restituisce o imposta il margine sinistro in un paragrafo senza eredità. Lettura/scrittura float.

**Restituisce:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Restituisce o imposta il margine sinistro in un paragrafo senza eredità. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Restituisce o imposta il margine destro in un paragrafo senza eredità. Lettura/scrittura float.

**Restituisce:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Restituisce o imposta il margine destro in un paragrafo senza eredità. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Restituisce o imposta l'Indentazione Prima Linea/Indentazione Sospesa del paragrafo senza eredità. L'Indentazione Sospesa può essere definita con valori negativi. Lettura/scrittura float.

**Restituisce:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Restituisce o imposta l'Indentazione Prima Linea/Indentazione Sospesa del paragrafo senza eredità. L'Indentazione Sospesa può essere definita con valori negativi. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Restituisce o imposta la dimensione di tabulazione predefinita senza eredità. Lettura/scrittura float.

**Restituisce:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Restituisce o imposta la dimensione di tabulazione predefinita senza eredità. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Restituisce le tabulazioni di un paragrafo. Nessuna eredità applicata. Sola lettura [ITabCollection](../../com.aspose.slides/itabcollection).

**Restituisce:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Restituisce o imposta l'allineamento del carattere in un paragrafo senza eredità. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Restituisce:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Restituisce o imposta l'allineamento del carattere in un paragrafo senza eredità. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Restituisce il formato della porzione predefinita di un paragrafo. Nessuna eredità applicata. Sola lettura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione del paragrafo effettivi con l'eredità applicata.

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).