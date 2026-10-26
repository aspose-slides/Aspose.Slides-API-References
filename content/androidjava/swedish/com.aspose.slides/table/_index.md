---
title: Table
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en tabell på en bild.
type: docs
url: /sv/com.aspose.slides/table/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Representerar en tabell på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Returnerar cellen på de angivna kolumn- och radindexen. |
| [getRows()](#getRows--) | Returnerar samlingen av rader. |
| [getColumns()](#getColumns--) | Returnerar samlingen av kolumner. |
| [getTableFormat()](#getTableFormat--) | Returnerar TableFormat-objektet som innehåller formateringsegenskaper för den här tabellen. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Slår samman intilliggande celler. |
| [getStylePreset()](#getStylePreset--) | Hämtar eller anger inbyggd tabellstil. |
| [setStylePreset(int value)](#setStylePreset-int-) | Hämtar eller anger inbyggd tabellstil. |
| [getRightToLeft()](#getRightToLeft--) | Fastställer om tabellen har läsordning från höger till vänster. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Fastställer om tabellen har läsordning från höger till vänster. |
| [getFirstRow()](#getFirstRow--) | Fastställer om den första raden i en tabell ska ritas med en speciell formatering. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Fastställer om den första raden i en tabell ska ritas med en speciell formatering. |
| [getFirstCol()](#getFirstCol--) | Fastställer om den första kolumnen i en tabell ska ritas med en speciell formatering. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Fastställer om den första kolumnen i en tabell ska ritas med en speciell formatering. |
| [getLastRow()](#getLastRow--) | Fastställer om den sista raden i en tabell ska ritas med en speciell formatering. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Fastställer om den sista raden i en tabell ska ritas med en speciell formatering. |
| [getLastCol()](#getLastCol--) | Fastställer om den sista kolumnen i en tabell ska ritas med en speciell formatering. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Fastställer om den sista kolumnen i en tabell ska ritas med en speciell formatering. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Fastställer om jämna rader ska ritas med en annan formatering. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Fastställer om jämna rader ska ritas med en annan formatering. |
| [getVerticalBanding()](#getVerticalBanding--) | Fastställer om jämna kolumner ska ritas med en annan formatering. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Fastställer om jämna kolumner ska ritas med en annan formatering. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ställer in definierade delformat-egenskaper för alla tabellcellers delar. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ställer in definierade styckeformat-egenskaper för alla tabellcellers stycken. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ställer in definierade textramformat-egenskaper för alla tabellcellers textramar. |
| [getFillFormat()](#getFillFormat--) | Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatering för tabellen. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```


Returnerar cellen på de angivna kolumn- och radindexen. Endast läsning [Cell](../../com.aspose.slides/cell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returnerar:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```


Returnerar samlingen av rader. Endast läsning [IRowCollection](../../com.aspose.slides/irowcollection).

**Returnerar:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```


Returnerar samlingen av kolumner. Endast läsning [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returnerar:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```


Returnerar TableFormat-objektet som innehåller formateringsegenskaper för den här tabellen. Endast läsning [ITableFormat](../../com.aspose.slides/itableformat).

**Returnerar:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Slår samman intilliggande celler.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell att slå samman. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell att slå samman. |
| allowSplitting | boolean | True för att tillåta delning av celler. |

**Returnerar:**
[ICell](../../com.aspose.slides/icell) - Slagen samman cell.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```


Hämtar eller anger inbyggd tabellstil. Läs/skriv [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returnerar:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```


Hämtar eller anger inbyggd tabellstil. Läs/skriv [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```


Fastställer om tabellen har läsordning från höger till vänster. Läs/skriv boolean .

**Returnerar:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```


Fastställer om tabellen har läsordning från höger till vänster. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```


Fastställer om den första raden i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```


Fastställer om den första raden i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```


Fastställer om den första kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```


Fastställer om den första kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```


Fastställer om den sista raden i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```


Fastställer om den sista raden i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```


Fastställer om den sista kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```


Fastställer om den sista kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```


Fastställer om jämna rader ska ritas med en annan formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```


Fastställer om jämna rader ska ritas med en annan formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```


Fastställer om jämna kolumner ska ritas med en annan formatering. Läs/skriv boolean .

**Returnerar:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```


Fastställer om jämna kolumner ska ritas med en annan formatering. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Ställer in definierade delformat-egenskaper för alla tabellcellers delar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-objekt med nödvändiga egenskaper satta. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ställer in definierade styckeformat-egenskaper för alla tabellcellers stycken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-objekt med nödvändiga egenskaper satta. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Ställer in definierade textramformat-egenskaper för alla tabellcellers textramar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-objekt med nödvändiga egenskaper satta. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatering för tabellen. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)