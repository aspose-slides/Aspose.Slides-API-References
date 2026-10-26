---
title: Row
second_title: Aspose.Slides per Android tramite API Java
description: Rappresenta una riga in una tabella.
type: docs
url: /it/com.aspose.slides/row/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Tutte le interfacce implementate:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Rappresenta una riga in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeight()](#getHeight--) | Restituisce l'altezza di una riga. |
| [getMinimalHeight()](#getMinimalHeight--) | Restituisce o imposta l'altezza minima possibile di una riga. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Restituisce o imposta l'altezza minima possibile di una riga. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Imposta le proprietà di formato della porzione definite a tutte le porzioni delle celle della riga. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Imposta le proprietà di formato del paragrafo definite a tutti i paragrafi delle celle della riga. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Imposta le proprietà di formato della cornice di testo definite a tutti i riquadri di testo delle celle della riga. |
| [getRowFormat()](#getRowFormat--) | Restituisce l'oggetto RowFormat che contiene le proprietà di formattazione per questa riga. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Restituisce l'altezza di una riga. Solo lettura double.

**Restituisce:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Restituisce o imposta l'altezza minima possibile di una riga. Lettura/scrittura double.

**Restituisce:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


Restituisce o imposta l'altezza minima possibile di una riga. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Imposta le proprietà di formato della porzione definite a tutte le porzioni delle celle della riga.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | oggetto IPortionFormat con le proprietà necessarie impostate. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Imposta le proprietà di formato del paragrafo definite a tutti i paragrafi delle celle della riga.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | oggetto IParagraphFormat con le proprietà necessarie impostate. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Imposta le proprietà di formato della cornice di testo definite a tutti i riquadri di testo delle celle della riga.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | oggetto ITextFrameFormat con le proprietà necessarie impostate. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Restituisce l'oggetto RowFormat che contiene le proprietà di formattazione per questa riga. Solo lettura [IRowFormat](../../com.aspose.slides/irowformat).

**Restituisce:**
[IRowFormat](../../com.aspose.slides/irowformat)