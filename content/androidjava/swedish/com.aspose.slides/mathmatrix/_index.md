---
title: MathMatrix
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar Matrix-objektet som består av underordnade element placerade i en eller flera rader och kolumner.
type: docs
url: /sv/com.aspose.slides/mathmatrix/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specificerar Matrix-objektet, bestående av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteserna bör du använda avgränsningsobjektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initierar en ny instans av MathMatrix-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRowCount()](#getRowCount--) | Antal rader i matrisen |
| [getColumnCount()](#getColumnCount--) | Antal kolumner i matrisen |
| [getHidePlaceholders()](#getHidePlaceholders--) | Döljer platshållarna för tomma matriselement Standard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Döljer platshållarna för tomma matriselement Standard: false |
| [getBaseJustification()](#getBaseJustification--) | Specificerar vertikal justering i förhållande till omgivande text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specificerar vertikal justering i förhållande till omgivande text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minsta kolumnbredd i twips (1/20 av en punkt) Gapavståndet (även kallat \u201cColumn Gap\u201d eller \u201cGap Width\u201d) adderas till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minsta kolumnbredd i twips (1/20 av en punkt) Gapavståndet (även kallat \u201cColumn Gap\u201d eller \u201cGap Width\u201d) adderas till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). |
| [getColumnGapRule()](#getColumnGapRule--) | Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). |
| [getColumnGap()](#getColumnGap--) | Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. |
| [setColumnGap(long value)](#setColumnGap-long-) | Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. |
| [getRowGapRule()](#getRowGapRule--) | Typen av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typen av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). |
| [getRowGap()](#getRowGap--) | Värdet på vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlinjer. |
| [setRowGap(long value)](#setRowGap-long-) | Värdet på vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlinjer. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element i matrisen |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element i matrisen |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Egenskaper för kontrolltecken |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Hämta horisontell justering för den angivna kolumnen |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ställ in horisontell justering för den angivna kolumnen |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ställ in horisontell justering för de angivna kolumnerna |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Infoga en ny rad före den angivna. Initialt är alla element i den nya raden null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Infoga en ny rad efter den angivna. Initialt är alla element i den nya raden null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Tar bort den angivna raden |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Tar bort den angivna kolumnen |
| [getChildren()](#getChildren--) | Hämta underordnade element |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Initierar en ny instans av MathMatrix-klassen.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowCount | int | antal rader |
| columnCount | int | antal kolumner |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Döljer platshållarna för tomma matriselement Standard: false

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
public final void setHidePlaceholders(boolean value)
```

Döljer platshållarna för tomma matriselement Standard: false

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
public final int getBaseJustification()
```

Specificerar vertikal justering i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center

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
public final void setBaseJustification(int value)
```

Specificerar vertikal justering i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center

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
public final long getMinColumnWidth()
```

Minsta kolumnbredd i twips (1/20 av en punkt) Gapavståndet (även kallat \u201cColumn Gap\u201d eller \u201cGap Width\u201d) adderas till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). Standard: 0.

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
public final void setMinColumnWidth(long value)
```

Minsta kolumnbredd i twips (1/20 av en punkt) Gapavståndet (även kallat \u201cColumn Gap\u201d eller \u201cGap Width\u201d) adderas till MinColumnWidth för att bestämma den totala Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). Standard: 0.

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
public final int getColumnGapRule()
```

Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. I andra fall ignoreras. Standard: 0

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
public final void setColumnGap(long value)
```

Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. I andra fall ignoreras. Standard: 0

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
public final int getRowGapRule()
```

Typen av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

Typen av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

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
public final long getRowGap()
```

Värdet på vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlinjer. Standard: 0

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
public final void setRowGap(long value)
```

Värdet på vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlinjer. Standard: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
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
| row | int | Nollbaserat index för raden som ska hämtas |
| column | int | Nollbaserat index för kolumnen som ska hämtas |

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
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
| row | int | Nollbaserat index för raden som ska hämtas |
| column | int | Nollbaserat index för kolumnen som ska hämtas |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Egenskaper för kontrolltecken

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Hämta horisontell justering för den angivna kolumnen

--------------------

> ```
> Exempel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int | Nollbaserat kolumnindex |

**Returnerar:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
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
| val | int | Nytt värde för horisontell justering av den angivna kolumnen |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
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
| columnsCount | long | Antalet kolumner som ska få angiven justering |
| val | int | Nytt värde för horisontell justering av den angivna kolumnen |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
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
public final void insertRowAfter(int rowIndex)
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
public final void deleteRow(int rowIndex)
```

Tar bort den angivna raden

--------------------

> ```
> Exempel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | int | Nollbaserat index för raden som ska tas bort. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null.

--------------------

> ```
> Exempel:
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
public final void insertColumnAfter(int columnIndex)
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
public final void deleteColumn(int columnIndex)
```

Tar bort den angivna kolumnen

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
| columnIndex | int | Nollbaserat index för kolumnen som ska tas bort. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämta underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]