---
title: IMathMatrix
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica l'oggetto Matrix costituito da elementi figlio disposti in una o più righe e colonne.
type: docs
url: /it/com.aspose.slides/imathmatrix/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specifică l'oggetto Matrix, costituito da elementi figlio disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per posizionare la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). È possibile usare argomenti null per creare spazi vuoti nelle matrici.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elementi della matrice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elementi della matrice |
| [getRowCount()](#getRowCount--) | Numero di righe nella matrice |
| [getColumnCount()](#getColumnCount--) | Numero di colonne nella matrice |
| [getHidePlaceholders()](#getHidePlaceholders--) | Nascondi i segnaposto per gli elementi vuoti della matrice Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Nascondi i segnaposto per gli elementi vuoti della matrice Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifica l'allineamento verticale rispetto al testo circostante. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifica l'allineamento verticale rispetto al testo circostante. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Larghezza minima della colonna in twip (1/20 di punto) La spaziatura di interruzione (nota anche come \u201cColumn Gap\u201d o \u201cGap Width\u201d) è aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi delle diverse colonne). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Larghezza minima della colonna in twip (1/20 di punto) La spaziatura di interruzione (nota anche come \u201cColumn Gap\u201d o \u201cGap Width\u201d) è aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi delle diverse colonne). |
| [getColumnGapRule()](#getColumnGapRule--) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). |
| [getColumnGap()](#getColumnGap--) | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). |
| [getRowGap()](#getRowGap--) | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. |
| [setRowGap(long value)](#setRowGap-long-) | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Ottieni l'allineamento orizzontale della colonna specificata |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Imposta l'allineamento orizzontale della colonna specificata |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Imposta l'allineamento orizzontale delle colonne specificate |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Inserisci una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Inserisci una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Elimina la riga specificata |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Inserisci una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Elimina la colonna specificata |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elementi della matrice

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

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elementi della matrice

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

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
```

Numero di colonne nella matrice

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Restituisce:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Nascondi i segnaposto per gli elementi vuoti della matrice Default: false

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Restituisce:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Nascondi i segnaposto per gli elementi vuoti della matrice Default: false

--------------------

> ```
> Esempio:
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
public abstract int getBaseJustification()
```

Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Default: Center

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Restituisce:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Default: Center

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
public abstract long getMinColumnWidth()
```

Larghezza minima della colonna in twip (1/20 di punto) La spaziatura di interruzione (nota anche come \u201cColumn Gap\u201d o \u201cGap Width\u201d) è aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi delle diverse colonne). Default: 0.

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
public abstract void setMinColumnWidth(long value)
```

Larghezza minima della colonna in twip (1/20 di punto) La spaziatura di interruzione (nota anche come \u201cColumn Gap\u201d o \u201cGap Width\u201d) è aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi delle diverse colonne). Default: 0.

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
public abstract int getColumnGapRule()
```

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Default: SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Default: SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0.5 em. In altri casi ignorato. Default: 0

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
public abstract void setColumnGap(long value)
```

Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0.5 em. In altri casi ignorato. Default: 0

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
public abstract int getRowGapRule()
```

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Default: SingleSpacingGap (0)

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Restituisce:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Default: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Default: 0

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
public abstract void setRowGap(long value)
```

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Default: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Ottieni l'allineamento orizzontale della colonna specificata

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
| columnIndex | int | Indice della colonna basato su zero |

**Restituisce:**
int - Allineamento Orizzontale della colonna specificata
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
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
| columnIndex | int | Indice della colonna basato su zero |
| val | int | Nuovo valore dell'allineamento orizzontale della colonna specificata |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
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
| columnIndex | int | Indice basato su zero della prima colonna a cui impostare l'allineamento |
| columnsCount | long | Il numero di colonne per cui specificare l'allineamento |
| val | int | Nuovo valore dell'allineamento orizzontale della colonna specificata |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Inserisci una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

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
| rowIndex | int | Indice della riga prima della quale inserire una nuova riga |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Inserisci una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null.

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
| rowIndex | int | Indice della riga dopo la quale inserire una nuova riga |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Elimina la riga specificata

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowIndex | int | L'indice basato su zero della riga da eliminare. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Inserisci una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

--------------------

> ```
> Esempio:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int | Indice della colonna prima della quale inserire una nuova colonna |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Inserisci una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null.

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
| columnIndex | int | Indice della colonna dopo la quale inserire una nuova colonna |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
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