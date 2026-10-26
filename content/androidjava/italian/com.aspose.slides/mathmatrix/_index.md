---
title: MathMatrix
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica l'oggetto Matrix composto da elementi figlio disposti in una o più righe e colonne.
type: docs
url: /it/com.aspose.slides/mathmatrix/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specifica l'oggetto Matrix, costituito da elementi figlio disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per collocare la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). Gli argomenti null possono essere utilizzati per creare spazi vuoti nelle matrici.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inizializza una nuova istanza della classe MathMatrix. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRowCount()](#getRowCount--) | Numero di righe nella matrice |
| [getColumnCount()](#getColumnCount--) | Numero di colonne nella matrice |
| [getHidePlaceholders()](#getHidePlaceholders--) | Nasconde i segnaposto per gli elementi vuoti della matrice Predefinito: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Nasconde i segnaposto per gli elementi vuoti della matrice Predefinito: false |
| [getBaseJustification()](#getBaseJustification--) | Specifica l'allineamento verticale rispetto al testo circostante. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifica l'allineamento verticale rispetto al testo circostante. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Larghezza minima della colonna in twip (1/20 di punto) La spaziatura del gap (anche denominata \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) viene aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra i stessi bordi di colonne diverse). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Larghezza minima della colonna in twip (1/20 di punto) La spaziatura del gap (anche denominata \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) viene aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra i stessi bordi di colonne diverse). |
| [getColumnGapRule()](#getColumnGapRule--) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). |
| [getColumnGap()](#getColumnGap--) | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). |
| [getRowGap()](#getRowGap--) | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. |
| [setRowGap(long value)](#setRowGap-long-) | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemento della matrice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemento della matrice |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Restituisce l'allineamento orizzontale della colonna specificata |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Imposta l'allineamento orizzontale della colonna specificata |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Imposta l'allineamento orizzontale delle colonne specificate |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Inserisce una nuova riga prima di quella specificata Inizialmente tutti gli elementi della nuova riga sono null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Inserisce una nuova riga dopo quella specificata Inizialmente tutti gli elementi della nuova riga sono null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Elimina la riga specificata |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Inserisce una nuova colonna prima di quella specificata Inizialmente tutti gli elementi della nuova colonna sono null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Inserisce una nuova colonna dopo quella specificata Inizialmente tutti gli elementi della nuova colonna sono null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Elimina la colonna specificata |
| [getChildren()](#getChildren--) | Restituisce gli elementi figli |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inizializza una nuova istanza della classe MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parametri:**

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowCount | int | conteggio delle righe |
| columnCount | int | conteggio delle colonne |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Numero di righe nella matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Restituisce:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Numero di colonne nella matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Restituisce:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Nasconde i segnaposto per gli elementi vuoti della matrice Predefinito: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Restituisce:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Nasconde i segnaposto per gli elementi vuoti della matrice Predefinito: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Restituisce:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Larghezza minima della colonna in twip (1/20 di punto) La spaziatura del gap (anche denominata \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) viene aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra i stessi bordi di colonne diverse). Predefinito: 0.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Restituisce:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Larghezza minima della colonna in twip (1/20 di punto) La spaziatura del gap (anche denominata \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) viene aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra i stessi bordi di colonne diverse). Predefinito: 0.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Restituisce:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. Negli altri casi ignorato. Predefinito: 0

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Restituisce:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. Negli altri casi ignorato. Predefinito: 0

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Restituisce:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Predefinito: 0

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Restituisce:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Predefinito: 0

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Elemento della matrice

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| row | int | L'indice basato su zero della riga da cui ottenere l'elemento |
| column | int | L'indice basato su zero della colonna da cui ottenere l'elemento |

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Elemento della matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| row | int | L'indice basato su zero della riga da cui ottenere l'elemento |
| column | int | L'indice basato su zero della colonna da cui ottenere l'elemento |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Restituisce l'allineamento orizzontale della colonna specificata

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice colonna basato su zero |

**Restituisce:**
int - Allineamento orizzontale della colonna specificata
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Imposta l'allineamento orizzontale della colonna specificata

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice colonna basato su zero |
| val | int | Nuovo valore dell'allineamento orizzontale della colonna specificata |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Imposta l'allineamento orizzontale delle colonne specificate

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice basato su zero della prima colonna per impostare l'allineamento |
| columnsCount | long | Il numero di colonne per specificare l'allineamento |
| val | int | Nuovo valore dell'allineamento orizzontale della colonna specificata |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Inserisce una nuova riga prima di quella specificata Inizialmente tutti gli elementi della nuova riga sono null.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | int | Indice della riga prima della quale inserire una nuova |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Inserisce una nuova riga dopo quella specificata Inizialmente tutti gli elementi della nuova riga sono null.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | int | Indice della riga dopo la quale inserire una nuova |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Elimina la riga specificata

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | int | L'indice basato su zero della riga da eliminare. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Inserisce una nuova colonna prima di quella specificata Inizialmente tutti gli elementi della nuova colonna sono null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice della colonna prima della quale inserire una nuova |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Inserisce una nuova colonna dopo quella specificata Inizialmente tutti gli elementi della nuova colonna sono null.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice della colonna dopo la quale inserire una nuova |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Elimina la colonna specificata

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | L'indice basato su zero della colonna da eliminare. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Restituisce gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]