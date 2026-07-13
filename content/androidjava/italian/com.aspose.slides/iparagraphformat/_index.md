---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Questa classe contiene le proprietà di formattazione del paragrafo.
type: docs
url: /it/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

--------------------

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che non viene applicata l'ereditarietà durante il recupero dei valori, quindi nella maggior parte dei casi otterrai valori che significano "non definito".

Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario utilizzare il metodo [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) che restituisce un'istanza [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBullet()](#getBullet--) | Restituisce il formato bullet del paragrafo. |
| [getDepth()](#getDepth--) | Restituisce o imposta la profondità del paragrafo. |
| [setDepth(short value)](#setDepth-short-) | Restituisce o imposta la profondità del paragrafo. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. |
| [setAlignment(int value)](#setAlignment-int-) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. |
| [getSpaceWithin()](#getSpaceWithin--) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Restituisce o imposta la quantità di spazio prima della prima linea in un paragrafo senza ereditarietà. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Restituisce o imposta la quantità di spazio prima della prima linea in un paragrafo senza ereditarietà. |
| [getSpaceAfter()](#getSpaceAfter--) | Restituisce o imposta la quantità di spazio dopo l'ultima linea in un paragrafo senza ereditarietà. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Restituisce o imposta la quantità di spazio dopo l'ultima linea in un paragrafo senza ereditarietà. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se viene utilizzata la interruzione di riga East Asian in un paragrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina se viene utilizzata la interruzione di riga East Asian in un paragrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se viene utilizzata la scrittura da destra a sinistra in un paragrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina se viene utilizzata la scrittura da destra a sinistra in un paragrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se viene utilizzata la interruzione di riga Latin in un paragrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina se viene utilizzata la interruzione di riga Latin in un paragrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se viene utilizzata la punteggiatura sospesa in un paragrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina se viene utilizzata la punteggiatura sospesa in un paragrafo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. |
| [setMarginRight(float value)](#setMarginRight-float-) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. |
| [getIndent()](#getIndent--) | Restituisce o imposta l'indentazione della prima linea/indentazione sospesa del paragrafo senza ereditarietà. |
| [setIndent(float value)](#setIndent-float-) | Restituisce o imposta l'indentazione della prima linea/indentazione sospesa del paragrafo senza ereditarietà. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà. |
| [getTabs()](#getTabs--) | Restituisce le tabulazioni di un paragrafo. |
| [getFontAlignment()](#getFontAlignment--) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Restituisce il formato della porzione predefinita di un paragrafo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Restituisce il formato bullet del paragrafo. Sola lettura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Restituisce:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Restituisce o imposta la profondità del paragrafo. Il valore 0 indica un valore non definito. Lettura/scrittura short.

**Restituisce:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Restituisce o imposta la profondità del paragrafo. Il valore 0 indica un valore non definito. Lettura/scrittura short.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

**Restituisce:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, negativo - dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, negativo - dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Restituisce o imposta la quantità di spazio prima della prima linea in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Restituisce o imposta la quantità di spazio prima della prima linea in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Restituisce o imposta la quantità di spazio dopo l'ultima linea in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Restituisce:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Restituisce o imposta la quantità di spazio dopo l'ultima linea in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Determina se viene utilizzata la interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Determina se viene utilizzata la interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Determina se viene utilizzata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Determina se viene utilizzata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Determina se viene utilizzata la interruzione di riga Latin in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Determina se viene utilizzata la interruzione di riga Latin in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Determina se viene utilizzata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Determina se viene utilizzata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura float.

**Restituisce:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura float.

**Restituisce:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Restituisce o imposta l'indentazione della prima linea/indentazione sospesa del paragrafo senza ereditarietà. L'indentazione sospesa può essere definita con valori negativi. Lettura/scrittura float.

**Restituisce:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Restituisce o imposta l'indentazione della prima linea/indentazione sospesa del paragrafo senza ereditarietà. L'indentazione sospesa può essere definita con valori negativi. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà. Lettura/scrittura float.

**Restituisce:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [ITabCollection](../../com.aspose.slides/itabcollection).

**Restituisce:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Restituisce:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Restituisce il formato della porzione predefinita di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata.

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).