---
title: Table
second_title: Aspose.Slides för Java API-referens
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
| [getTableFormat()](#getTableFormat--) | Returnerar TableFormat-objektet som innehåller formateringsegenskaper för denna tabell. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Slår ihop intilliggande celler. |
| [getStylePreset()](#getStylePreset--) | Hämtar eller anger inbyggd tabellstil. |
| [setStylePreset(int value)](#setStylePreset-int-) | Hämtar eller anger inbyggd tabellstil. |
| [getRightToLeft()](#getRightToLeft--) | Bestämmer om tabellen har läshållning från höger till vänster. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bestämmer om tabellen har läshållning från höger till vänster. |
| [getFirstRow()](#getFirstRow--) | Bestämmer om den första raden i en tabell ska ritas med en särskild formatering. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bestämmer om den första raden i en tabell ska ritas med en särskild formatering. |
| [getFirstCol()](#getFirstCol--) | Bestämmer om den första kolumnen i en tabell ska ritas med en särskild formatering. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bestämmer om den första kolumnen i en tabell ska ritas med en särskild formatering. |
| [getLastRow()](#getLastRow--) | Bestämmer om den sista raden i en tabell ska ritas med en särskild formatering. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bestämmer om den sista raden i en tabell ska ritas med en särskild formatering. |
| [getLastCol()](#getLastCol--) | Bestämmer om den sista kolumnen i en tabell ska ritas med en särskild formatering. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bestämmer om den sista kolumnen i en tabell ska ritas med en särskild formatering. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bestämmer om jämna rader ska ritas med en annan formatering. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bestämmer om jämna rader ska ritas med en annan formatering. |
| [getVerticalBanding()](#getVerticalBanding--) | Bestämmer om jämna kolumner ska ritas med en annan formatering. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bestämmer om jämna kolumner ska ritas med en annan formatering. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ställer in definierade portionsformateringsegenskaper för alla tabellcellers portioner. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ställer in definierade styckeformateringsegenskaper för alla tabellcellers stycken. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ställer in definierade textramformatsegenskaper för alla tabellcellers textramar. |
| [getFillFormat()](#getFillFormat--) | Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatering för tabellen. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Returnerar cellen på de angivna kolumn- och radindexen. Skrivskyddad [Cell](../../com.aspose.slides/cell).

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

Returnerar samlingen av rader. Skrivskyddad [IRowCollection](../../com.aspose.slides/irowcollection).

**Returnerar:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Returnerar samlingen av kolumner. Skrivskyddad [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returnerar:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Returnerar TableFormat-objektet som innehåller formateringsegenskaper för denna tabell. Skrivskyddad [ITableFormat](../../com.aspose.slides/itableformat).

**Returnerar:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Slår ihop intilliggande celler.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell att slå ihop. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell att slå ihop. |
| allowSplitting | boolean | Sant för att tillåta delning av celler. |

**Returnerar:**
[ICell](../../com.aspose.slides/icell) - Sammanslagen cell.

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

Bestämmer om tabellen har läshållning från höger till vänster. Läs/skriv boolean.

**Returnerar:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Bestämmer om tabellen har läshållning från höger till vänster. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Bestämmer om den första raden i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Bestämmer om den första raden i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Bestämmer om den första kolumnen i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Bestämmer om den första kolumnen i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Bestämmer om den sista raden i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Bestämmer om den sista raden i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Bestämmer om den sista kolumnen i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Bestämmer om den sista kolumnen i en tabell ska ritas med en särskild formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Bestämmer om jämna rader ska ritas med en annan formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Bestämmer om jämna rader ska ritas med en annan formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Bestämmer om jämna kolumner ska ritas med en annan formatering. Läs/skriv boolean.

**Returnerar:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Bestämmer om jämna kolumner ska ritas med en annan formatering. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Ställer in definierade portionsformateringsegenskaper för alla tabellcellers portioner.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-objekt med nödvändiga egenskaper satta. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Ställer in definierade styckeformateringsegenskaper för alla tabellcellers stycken.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-objekt med nödvändiga egenskaper satta. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Ställer in definierade textramformatsegenskaper för alla tabellcellers textramar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-objekt med nödvändiga egenskaper satta. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatering för tabellen. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)