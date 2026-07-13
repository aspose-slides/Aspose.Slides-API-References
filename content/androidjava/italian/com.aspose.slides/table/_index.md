---
title: Table
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una tabella su una diapositiva.
type: docs
url: /it/com.aspose.slides/table/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Rappresenta una tabella su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Restituisce la cella agli indici di colonna e riga specificati. |
| [getRows()](#getRows--) | Restituisce la collezione di righe. |
| [getColumns()](#getColumns--) | Restituisce la collezione di colonne. |
| [getTableFormat()](#getTableFormat--) | Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Unisce le celle adiacenti. |
| [getStylePreset()](#getStylePreset--) | Ottiene o imposta lo stile predefinito della tabella. |
| [setStylePreset(int value)](#setStylePreset-int-) | Ottiene o imposta lo stile predefinito della tabella. |
| [getRightToLeft()](#getRightToLeft--) | Determina se la tabella ha ordine di lettura da destra a sinistra. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determina se la tabella ha ordine di lettura da destra a sinistra. |
| [getFirstRow()](#getFirstRow--) | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [getFirstCol()](#getFirstCol--) | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [getLastRow()](#getLastRow--) | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [getLastCol()](#getLastCol--) | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determina se le righe pari devono essere disegnate con una formattazione diversa. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determina se le righe pari devono essere disegnate con una formattazione diversa. |
| [getVerticalBanding()](#getVerticalBanding--) | Determina se le colonne pari devono essere disegnate con una formattazione diversa. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determina se le colonne pari devono essere disegnate con una formattazione diversa. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Imposta le proprietà di formattazione della porzione definite per tutte le porzioni delle celle della tabella. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Imposta le proprietà di formattazione del paragrafo definite per tutti i paragrafi delle celle della tabella. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Imposta le proprietà di formattazione del frame di testo definite per tutti i frame di testo delle celle della tabella. |
| [getFillFormat()](#getFillFormat--) | Restituisce un oggetto TableFormat.FillFormat contenente la formattazione di riempimento per la Tabella. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Restituisce la cella agli indici di colonna e riga specificati. **Solo lettura** [Cell](../../com.aspose.slides/cell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Restituisce:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Restituisce la collezione di righe. **Solo lettura** [IRowCollection](../../com.aspose.slides/irowcollection).

**Restituisce:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Restituisce la collezione di colonne. **Solo lettura** [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Restituisce:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. **Solo lettura** [ITableFormat](../../com.aspose.slides/itableformat).

**Restituisce:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Unisce le celle adiacenti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cella da unire. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cella da unire. |
| allowSplitting | boolean | Vero per consentire la suddivisione delle celle. |

**Restituisce:**
[ICell](../../com.aspose.slides/icell) - Cella unita.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Ottiene o imposta lo stile predefinito della tabella. **Lettura/scrittura** [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Restituisce:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Ottiene o imposta lo stile predefinito della tabella. **Lettura/scrittura** [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Determina se la tabella ha ordine di lettura da destra a sinistra. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Determina se la tabella ha ordine di lettura da destra a sinistra. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Determina se le righe pari devono essere disegnate con una formattazione diversa. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Determina se le righe pari devono essere disegnate con una formattazione diversa. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Determina se le colonne pari devono essere disegnate con una formattazione diversa. **Lettura/scrittura**  boolean .

**Restituisce:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Determina se le colonne pari devono essere disegnate con una formattazione diversa. **Lettura/scrittura**  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Imposta le proprietà di formattazione della porzione definite per tutte le porzioni delle celle della tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Oggetto IPortionFormat con le proprietà necessarie impostate. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Imposta le proprietà di formattazione del paragrafo definite per tutti i paragrafi delle celle della tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Oggetto IParagraphFormat con le proprietà necessarie impostate. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Imposta le proprietà di formattazione del frame di testo definite per tutti i frame di testo delle celle della tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Oggetto ITextFrameFormat con le proprietà necessarie impostate. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Restituisce un oggetto TableFormat.FillFormat contenente la formattazione di riempimento per la Tabella. **Solo lettura** [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)