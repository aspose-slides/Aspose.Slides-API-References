---
title: Column
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una colonna in una tabella.
type: docs
url: /it/com.aspose.slides/column/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Tutte le interfacce implementate:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Rappresenta una colonna in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce o imposta la larghezza di una colonna. |
| [setWidth(double value)](#setWidth-double-) | Restituisce o imposta la larghezza di una colonna. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Imposta le proprietà di formato della porzione definite per tutte le porzioni delle celle della colonna. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Imposta le proprietà di formato del paragrafo definite per tutti i paragrafi delle celle della colonna. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Imposta le proprietà di formato del riquadro di testo definite per tutti i riquadri di testo delle celle della colonna. |
| [getColumnFormat()](#getColumnFormat--) | Restituisce l'oggetto ColumnFormat che contiene le proprietà di formattazione per questa colonna. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Restituisce o imposta la larghezza di una colonna. Lettura/scrittura double.

**Restituisce:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Restituisce o imposta la larghezza di una colonna. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Imposta le proprietà di formato della porzione definite per tutte le porzioni delle celle della colonna.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | oggetto IPortionFormat con le proprietà necessarie impostate. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Imposta le proprietà di formato del paragrafo definite per tutti i paragrafi delle celle della colonna.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | oggetto IParagraphFormat con le proprietà necessarie impostate. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Imposta le proprietà di formato del riquadro di testo definite per tutti i riquadri di testo delle celle della colonna.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | oggetto ITextFrameFormat con le proprietà necessarie impostate. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Restituisce l'oggetto ColumnFormat che contiene le proprietà di formattazione per questa colonna. Solo lettura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Restituisce:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)