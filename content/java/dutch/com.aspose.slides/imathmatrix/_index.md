---
title: IMathMatrix
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert het Matrix-object dat bestaat uit onderliggende elementen die in één of meer rijen en kolommen zijn opgesteld.
type: docs
url: /nl/com.aspose.slides/imathmatrix/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specificeert het Matrix-object, bestaande uit onderliggende elementen die in één of meer rijen en kolommen zijn opgesteld. Het is belangrijk op te merken dat matrices geen ingebouwde begrenzers hebben. Om de matrix in haakjes te plaatsen, moet u het begrenzer-object (IMathDelimiter) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

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
| [getHidePlaceholders()](#getHidePlaceholders--) | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [getBaseJustification()](#getBaseJustification--) | Specificeert de verticale uitlijning ten opzichte van omringende tekst. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificeert de verticale uitlijning ten opzichte van omringende tekst. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \u201cColumn Gap\u201d of \u201cGap Width\u201d genoemd) wordt opgeteld bij de MinColumnWidth om de totale Matrix-kolomspacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \u201cColumn Gap\u201d of \u201cGap Width\u201d genoemd) wordt opgeteld bij de MinColumnWidth om de totale Matrix-kolomspacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. |
| [getColumnGapRule()](#getColumnGapRule--) | Het type horizontale spatiëring tussen kolommen van een matrix; Horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Het type horizontale spatiëring tussen kolommen van een matrix; Horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). |
| [getColumnGap()](#getColumnGap--) | De waarde van de horizontale spatiëring tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als aantal 0,5-em-stappen. |
| [setColumnGap(long value)](#setColumnGap-long-) | De waarde van de horizontale spatiëring tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als aantal 0,5-em-stappen. |
| [getRowGapRule()](#getRowGapRule--) | Het type verticale spatiëring tussen rijen van een matrix; Verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Het type verticale spatiëring tussen rijen van een matrix; Verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). |
| [getRowGap()](#getRowGap--) | De waarde van de verticale spatiëring tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als half-lijnen. |
| [setRowGap(long value)](#setRowGap-long-) | De waarde van de verticale spatiëring tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als half-lijnen. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Haal de horizontale uitlijning op van de opgegeven kolom |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Stel de horizontale uitlijning in van de opgegeven kolom |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Stel de horizontale uitlijning in van de opgegeven kolommen |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Voeg een nieuwe rij in vóór de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Voeg een nieuwe rij in na de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Verwijdert de opgegeven rij |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Voeg een nieuwe kolom in vóór de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Voeg een nieuwe kolom in na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| row | int | De nulgebaseerde index van de rij om het item op te halen |
| column | int | De nulgebaseerde index van de kolom om het item op te halen |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| row | int | De nulgebaseerde index van de rij om het item op te halen |
| column | int | De nulgebaseerde index van de kolom om het item op te halen |
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

Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false

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
public abstract int getBaseJustification()
```

Specificeert de verticale uitlijning ten opzichte van omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center

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

Specificeert de verticale uitlijning ten opzichte van omringende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center

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
public abstract long getMinColumnWidth()
```

Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \u201cColumn Gap\u201d of \u201cGap Width\u201d genoemd) wordt opgeteld bij de MinColumnWidth om de totale Matrix-kolomspacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0.

--------------------

> ```
> Voorbeeld:
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

Minimale kolombreedte in twips (1/20ste van een punt) De tussenruimte (ook wel \u201cColumn Gap\u201d of \u201cGap Width\u201d genoemd) wordt opgeteld bij de MinColumnWidth om de totale Matrix-kolomspacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0.

--------------------

> ```
> Voorbeeld:
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
public abstract int getColumnGapRule()
```

Het type horizontale spatiëring tussen kolommen van een matrix; Horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Voorbeeld:
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

Het type horizontale spatiëring tussen kolommen van een matrix; Horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Voorbeeld:
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
public abstract long getColumnGap()
```

De waarde van de horizontale spatiëring tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als aantal 0,5-em-stappen. In andere gevallen wordt het genegeerd. Standaard: 0

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

De waarde van de horizontale spatiëring tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als aantal 0,5-em-stappen. In andere gevallen wordt het genegeerd. Standaard: 0

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
public abstract int getRowGapRule()
```

Het type verticale spatiëring tussen rijen van een matrix; Verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

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

Het type verticale spatiëring tussen rijen van een matrix; Verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getRowGap()
```

De waarde van de verticale spatiëring tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als half-lijnen. Standaard: 0

--------------------

> ```
> Voorbeeld:
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

De waarde van de verticale spatiëring tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als half-lijnen. Standaard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Haal de horizontale uitlijning op van de opgegeven kolom

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

**Retour:**
int - Horizontale uitlijning van opgegeven kolom
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Stel de horizontale uitlijning in van de opgegeven kolom

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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Stel de horizontale uitlijning in van de opgegeven kolommen

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Nulgebaseerde index van de eerste kolom waarvoor de uitlijning wordt ingesteld |
| columnsCount | long | Het aantal kolommen waarvoor de uitlijning wordt gespecificeerd |
| val | int | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Voeg een nieuwe rij in vóór de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.

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
| rowIndex | int | Index van de rij vóór welke een nieuwe moet worden ingevoegd |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Voeg een nieuwe rij in na de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | int | Index van de rij na welke een nieuwe moet worden ingevoegd |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Verwijdert de opgegeven rij

--------------------

> ```
> Voorbeeld:
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
public abstract void insertColumnBefore(int columnIndex)
```

Voeg een nieuwe kolom in vóór de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | Index van de kolom vóór welke een nieuwe moet worden ingevoegd |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Voeg een nieuwe kolom in na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.

--------------------

> ```
> Voorbeeld:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int | De nulgebaseerde index van de kolom die moet worden verwijderd. |