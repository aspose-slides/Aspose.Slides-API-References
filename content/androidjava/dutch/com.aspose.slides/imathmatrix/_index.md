---
title: IMathMatrix
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het Matrix-object dat bestaat uit onderliggende elementen die zijn gerangschikt in een of meer rijen en kolommen.
type: docs
url: /nl/com.aspose.slides/imathmatrix/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specificeert het Matrix-object, bestaande uit onderliggende elementen gerangschikt in een of meer rijen en kolommen. Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. Om de matrix in de haakjes te plaatsen, moet u het delimiter-object (IMathDelimiter) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elementen van matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elementen van matrix |
| [getRowCount()](#getRowCount--) | Aantal rijen in de matrix |
| [getColumnCount()](#getColumnCount--) | Aantal kolommen in de matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Verberg de placeholders voor lege matrixelementen Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Verberg de placeholders voor lege matrixelementen Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de verticale uitlijning ten opzichte van omringende tekst. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de verticale uitlijning ten opzichte van omringende tekst. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix Column Spacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix Column Spacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. |
| [getColumnGapRule()](#getColumnGapRule--) | Het type horizontale afstand tussen kolommen van een matrix; Horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Het type horizontale afstand tussen kolommen van een matrix; Horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [getColumnGap()](#getColumnGap--) | De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-incrementen. |
| [setColumnGap(long value)](#setColumnGap-long-) | De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-incrementen. |
| [getRowGapRule()](#getRowGapRule--) | Het type verticale afstand tussen rijen van een matrix; Verticale afstandseenheden kunnen regels of punten zijn (opgeslagen als twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Het type verticale afstand tussen rijen van een matrix; Verticale afstandseenheden kunnen regels of punten zijn (opgeslagen als twips). |
| [getRowGap()](#getRowGap--) | De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als halve regels. |
| [setRowGap(long value)](#setRowGap-long-) | De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als halve regels. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Haal de horizontale uitlijning van de opgegeven kolom op |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Stel de horizontale uitlijning van de opgegeven kolom in |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Stel de horizontale uitlijning van de opgegeven kolommen in |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Voeg een nieuwe rij in vóór de opgegeven rij. Standaard zijn alle elementen in de nieuwe rij null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Voeg een nieuwe rij in na de opgegeven rij. Standaard zijn alle elementen in de nieuwe rij null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Verwijdert de opgegeven rij |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Voeg een nieuwe kolom in vóór de opgegeven kolom. Standaard zijn alle elementen in de nieuwe kolom null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Voeg een nieuwe kolom in na de opgegeven kolom. Standaard zijn alle elementen in de nieuwe kolom null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Verwijdert de opgegeven kolom |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elementen van matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | De nul-gebaseerde index van de rij om het item op te halen |
| column | int | De nul-gebaseerde index van de kolom om het item op te halen |

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elementen van matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | De nul-gebaseerde index van de rij om het item op te halen |
| column | int | De nul-gebaseerde index van de kolom om het item op te halen |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Aantal rijen in de matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Retour:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Aantal kolommen in de matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Retour:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Verberg de placeholders voor lege matrixelementen Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Retour:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Verberg de placeholders voor lege matrixelementen Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Specificeert de verticale uitlijning ten opzichte van omringende tekst. Mogelijke waarden zijn top, bottom en center. Standaard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Retour:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Specificeert de verticale uitlijning ten opzichte van omringende tekst. Mogelijke waarden zijn top, bottom en center. Standaard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix Column Spacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Retour:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix Column Spacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

Het type horizontale afstand tussen kolommen van een matrix; Horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retour:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Het type horizontale afstand tussen kolommen van een matrix; Horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-incrementen. In andere gevallen wordt genegeerd. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Retour:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-incrementen. In andere gevallen wordt genegeerd. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

Het type verticale afstand tussen rijen van een matrix; Verticale afstandseenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retour:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Het type verticale afstand tussen rijen van een matrix; Verticale afstandseenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Retour:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (\"Multiple\"), wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Haal de horizontale uitlijning van de opgegeven kolom op

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Nul-gebaseerde kolomindex |
| val | int | Nieuwe waarde voor de horizontale uitlijning van de opgegeven kolom |

**Retour:**
int - Horizontale uitlijning van de opgegeven kolom

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Stel de horizontale uitlijning van de opgegeven kolom in

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Nul-gebaseerde kolomindex |
| val | int | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Stel de horizontale uitlijning van de opgegeven kolommen in

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Nul-gebaseerde index van de eerste kolom waarvoor de uitlijning wordt ingesteld |
| columnsCount | long | Het aantal kolommen waarvoor de uitlijning wordt gespecificeerd |
| val | int | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Voeg een nieuwe rij in vóór de opgegeven rij. Standaard zijn alle elementen in de nieuwe rij null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index van de rij vóór welke een nieuwe moet worden ingevoegd |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Voeg een nieuwe rij in na de opgegeven rij. Standaard zijn alle elementen in de nieuwe rij null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index van de rij na welke een nieuwe moet worden ingevoegd |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Verwijdert de opgegeven rij

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | De nul-gebaseerde index van de rij die moet worden verwijderd. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Voeg een nieuwe kolom in vóór de opgegeven kolom. Standaard zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index van de kolom vóór welke een nieuwe moet worden ingevoegd |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Voeg een nieuwe kolom in na de opgegeven kolom. Standaard zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index van de kolom na welke een nieuwe moet worden ingevoegd |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Verwijdert de opgegeven kolom

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | De nul-gebaseerde index van de kolom die moet worden verwijderd. |