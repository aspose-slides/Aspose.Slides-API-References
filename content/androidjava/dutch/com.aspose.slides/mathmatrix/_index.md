---
title: MathMatrix
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het Matrix-object bestaande uit kindelementen die in één of meer rijen en kolommen zijn geplaatst.
type: docs
url: /nl/com.aspose.slides/mathmatrix/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specificeert het Matrix-object, bestaande uit kindelementen die in één of meer rijen en kolommen zijn geplaatst. Het is belangrijk op te merken dat matrices geen ingebouwde scheidingstekens hebben. Om de matrix in de haakjes te plaatsen, moet je het scheidingstekenobject (IMathDelimiter) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initialiseert een nieuw exemplaar van de MathMatrix-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRowCount()](#getRowCount--) | Aantal rijen in de matrix |
| [getColumnCount()](#getColumnCount--) | Aantal kolommen in de matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de verticale uitlijning ten opzichte van de omringende tekst. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de verticale uitlijning ten opzichte van de omringende tekst. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimale kolombreedte in twips (1/20e van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan MinColumnWidth om de totale matrixkolomafstand te bepalen (afstand tussen dezelfde randen van verschillende kolommen). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimale kolombreedte in twips (1/20e van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan MinColumnWidth om de totale matrixkolomafstand te bepalen (afstand tussen dezelfde randen van verschillende kolommen). |
| [getColumnGapRule()](#getColumnGapRule--) | Het type horizontale spatiëring tussen kolommen van een matrix; horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Het type horizontale spatiëring tussen kolommen van een matrix; horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [getColumnGap()](#getColumnGap--) | De waarde van de horizontale spatiëring tussen kolommen van een matrix; indien ColumnGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Indien ColumnGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als aantal van 0.5 em-increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | De waarde van de horizontale spatiëring tussen kolommen van een matrix; indien ColumnGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Indien ColumnGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als aantal van 0.5 em-increments. |
| [getRowGapRule()](#getRowGapRule--) | Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). |
| [getRowGap()](#getRowGap--) | De waarde van de verticale spatiëring tussen rijen van een matrix; indien RowGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Indien RowGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als halve lijnen. |
| [setRowGap(long value)](#setRowGap-long-) | De waarde van de verticale spatiëring tussen rijen van een matrix; indien RowGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Indien RowGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als halve lijnen. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element van matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element van matrix |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Haalt de horizontale uitlijning van de opgegeven kolom op |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Stelt de horizontale uitlijning van de opgegeven kolom in |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Stelt de horizontale uitlijning van de opgegeven kolommen in |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Voegt een nieuwe rij in vóór de opgegeven rij. Initieel zijn alle elementen in de nieuwe rij null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Voegt een nieuwe rij in na de opgegeven rij. Initieel zijn alle elementen in de nieuwe rij null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Verwijdert de opgegeven rij |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Voegt een nieuwe kolom in vóór de opgegeven kolom. Initieel zijn alle elementen in de nieuwe kolom null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Voegt een nieuwe kolom in na de opgegeven kolom. Initieel zijn alle elementen in de nieuwe kolom null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Verwijdert de opgegeven kolom |
| [getChildren()](#getChildren--) | Haalt onderliggende elementen op |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Initialiseert een nieuw exemplaar van de MathMatrix-klasse.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowCount | int | aantal rijen |
| columnCount | int | aantal kolommen |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Aantal rijen in de matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returns:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Aantal kolommen in de matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returns:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returns:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Specificeert de verticale uitlijning ten opzichte van de omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Specificeert de verticale uitlijning ten opzichte van de omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Minimale kolombreedte in twips (1/20e van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan MinColumnWidth om de totale matrixkolomafstand te bepalen (afstand tussen dezelfde randen van verschillende kolommen). Standaard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returns:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Minimale kolombreedte in twips (1/20e van een punt) De tussenruimte (ook wel \\u201cColumn Gap\\u201d of \\u201cGap Width\\u201d genoemd) wordt toegevoegd aan MinColumnWidth om de totale matrixkolomafstand te bepalen (afstand tussen dezelfde randen van verschillende kolommen). Standaard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Het type horizontale spatiëring tussen kolommen van een matrix; horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Het type horizontale spatiëring tussen kolommen van een matrix; horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

De waarde van de horizontale spatiëring tussen kolommen van een matrix; indien ColumnGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) indien ColumnGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als aantal van 0.5 em-increments. In andere gevallen genegeerd. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

De waarde van de horizontale spatiëring tussen kolommen van een matrix; indien ColumnGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) indien ColumnGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als aantal van 0.5 em-increments. In andere gevallen genegeerd. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

De waarde van de verticale spatiëring tussen rijen van een matrix; indien RowGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) indien RowGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als halve lijnen. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

De waarde van de verticale spatiëring tussen rijen van een matrix; indien RowGapRule is ingesteld op 3 (“Exactly”), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) indien RowGapRule is ingesteld op 4 (“Multiple”), wordt de eenheid geïnterpreteerd als halve lijnen. Standaard: 0

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Element van matrix

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| row | int | De nulgebaseerde index van de rij voor het ophalen van het item |
| column | int | De nulgebaseerde index van de kolom voor het ophalen van het item |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Element van matrix

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| row | int | De nulgebaseerde index van de rij voor het ophalen van het item |
| column | int | De nulgebaseerde index van de kolom voor het ophalen van het item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Haalt de horizontale uitlijning van de opgegeven kolom op

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Nulgebaseerde kolomindex |

**Returns:**
int - Horizontale uitlijning van opgegeven kolom
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Stelt de horizontale uitlijning van de opgegeven kolom in

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Nulgebaseerde kolomindex |
| val | int | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Stelt de horizontale uitlijning van de opgegeven kolommen in

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Nulgebaseerde index van de eerste kolom waarvoor uitlijning wordt ingesteld |
| columnsCount | long | Het aantal kolommen waarvoor de uitlijning wordt gespecificeerd |
| val | int | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Voegt een nieuwe rij in vóór de opgegeven rij. Initieel zijn alle elementen in de nieuwe rij null.

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | int | Index van de rij vóór welke een nieuwe rij wordt ingevoegd |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Voegt een nieuwe rij in na de opgegeven rij. Initieel zijn alle elementen in de nieuwe rij null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | int | Index van de rij na welke een nieuwe rij wordt ingevoegd |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | int | De nulgebaseerde index van de rij die moet worden verwijderd. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Voegt een nieuwe kolom in vóór de opgegeven kolom. Initieel zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Index van de kolom vóór welke een nieuwe kolom wordt ingevoegd |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Voegt een nieuwe kolom in na de opgegeven kolom. Initieel zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Index van de kolom na welke een nieuwe kolom wordt ingevoegd |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Verwijdert de opgegeven kolom

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | De nulgebaseerde index van de kolom die moet worden verwijderd. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haalt onderliggende elementen op

**Returns:**
com.aspose.slides.IMathElement[]