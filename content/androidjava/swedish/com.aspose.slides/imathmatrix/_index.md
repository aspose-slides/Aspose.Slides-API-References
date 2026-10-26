---
title: IMathMatrix
second_title: Aspose.Slides för Android via Java API-referens
description: Anger Matrix-objektet som består av underordnade element placerade i en eller flera rader och kolumner.
type: docs
url: /sv/com.aspose.slides/imathmatrix/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specificerar Matrix-objektet, bestående av underordnade element som är placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteserna bör du använda avgränsningsobjektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element i matrisen |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element i matrisen |
| [getRowCount()](#getRowCount--) | Antal rader i matrisen |
| [getColumnCount()](#getColumnCount--) | Antal kolumner i matrisen |
| [getHidePlaceholders()](#getHidePlaceholders--) | Dölj platshållarna för tomma matriselement Standard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Dölj platshållarna för tomma matriselement Standard: false |
| [getBaseJustification()](#getBaseJustification--) | Anger den vertikala justeringen i förhållande till omgivande text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Anger den vertikala justeringen i förhållande till omgivande text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minsta kolumnbredd i twips (1/20th of a point) Avståndet mellan kolumner (även kallat \\u201cColumn Gap\\u201d eller \\u201cGap Width\\u201d) läggs till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minsta kolumnbredd i twips (1/20th of a point) Avståndet mellan kolumner (även kallat \\u201cColumn Gap\\u201d eller \\u201cGap Width\\u201d) läggs till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller points (lagrade som twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller points (lagrade som twips). |
| [getColumnGap()](#getColumnGap--) | Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0.5 em-ökningar. |
| [setColumnGap(long value)](#setColumnGap-long-) | Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0.5 em-ökningar. |
| [getRowGapRule()](#getRowGapRule--) | Typ av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara lines eller points (lagrade som twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara lines eller points (lagrade som twips). |
| [getRowGap()](#getRowGap--) | Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halva rader. |
| [setRowGap(long value)](#setRowGap-long-) | Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halva rader. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Hämta horisontell justering för den angivna kolumnen |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ställ in horisontell justering för den angivna kolumnen |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ställ in horisontell justering för de angivna kolumnerna |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Infoga en ny rad före den angivna. Initialt är alla element i den nya raden null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Infoga en ny rad efter den angivna. Initialt är alla element i den nya raden null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Raderar den angivna raden |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Raderar den angivna kolumnen |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Element i matrisen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| row | int | Det nollbaserade indexet för raden att hämta objektet |
| column | int | Det nollbaserade indexet för kolumnen att hämta objektet |

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Element i matrisen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| row | int | Det nollbaserade indexet för raden att hämta objektet |
| column | int | Det nollbaserade indexet för kolumnen att hämta objektet |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Antal rader i matrisen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returnerar:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Antal kolumner i matrisen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returnerar:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Dölj platshållarna för tomma matriselement Standard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returnerar:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Dölj platshållarna för tomma matriselement Standard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom, and center. Standard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Returnerar:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom, and center. Standard: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Minsta kolumnbredd i twips (1/20th of a point) Avståndet mellan kolumner (även kallat \\u201cColumn Gap\\u201d eller \\u201cGap Width\\u201d) läggs till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). Standard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returnerar:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Minsta kolumnbredd i twips (1/20th of a point) Avståndet mellan kolumner (även kallat \\u201cColumn Gap\\u201d eller \\u201cGap Width\\u201d) läggs till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). Standard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

Typ av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller points (lagrade som twips). Standard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returnerar:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Typ av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller points (lagrade som twips). Standard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0.5 em-ökningar. I andra fall ignoreras. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returnerar:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0.5 em-ökningar. I andra fall ignoreras. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

Typ av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara lines eller points (lagrade som twips). Standard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returnerar:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Typ av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara lines eller points (lagrade som twips). Standard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returnerar:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20th of a point) Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Hämta horisontell justering för den angivna kolumnen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Nollbaserat kolumnindex |

**Returnerar:**
int - Horisontell justering för angiven kolumn

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Ställ in horisontell justering för den angivna kolumnen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Nollbaserat kolumnindex |
| val | int | Nytt värde för horisontell justering av angiven kolumn |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Ställ in horisontell justering för de angivna kolumnerna

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Nollbaserat index för den första kolumnen som ska justeras |
| columnsCount | long | Antalet kolumner som ska justeras |
| val | int | Nytt värde för horisontell justering av angiven kolumn |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Infoga en ny rad före den angivna. Initialt är alla element i den nya raden null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | int | Index för raden före vilken en ny ska infogas |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Infoga en ny rad efter den angivna. Initialt är alla element i den nya raden null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | int | Index för raden efter vilken en ny ska infogas |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Raderar den angivna raden

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | int | Det nollbaserade indexet för raden som ska raderas. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Index för kolumnen före vilken en ny ska infogas |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Index för kolumnen efter vilken en ny ska infogas |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Raderar den angivna kolumnen

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Det nollbaserade indexet för kolumnen som ska raderas. |