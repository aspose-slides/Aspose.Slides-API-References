---
title: StringChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett strängvärde som kan lagras i pptx presentationsdokument på två sätt 1 i cell/er i arbetsboken som är relaterad till diagrammet 2 som ett bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/stringchartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Representerar ett strängvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/er i arbetsboken som är relaterad till diagrammet; 2) som ett bokstavligt värde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsCells()](#getAsCells--) | Tilldelning av null-värde är inte tillåtet. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Tilldelning av null-värde är inte tillåtet. |
| [getAsLiteralString()](#getAsLiteralString--) | Returnerar eller sätter värdet som en bokstavlig sträng. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returnerar eller sätter värdet som en bokstavlig sträng. |
| [getData()](#getData--) | Returnerar eller sätter Data-objekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Returnerar eller sätter Data-objekt. |
| [toString()](#toString--) | Returnerar strängvärdesdata. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Sätter värdet från angiven cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Om egenskapen DataSourceType är DataSourceType.Worksheet returnerar den här metoden adressen till cellerna i arbetsboken som representerar strängdata. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Tilldelning av null-värde är inte tillåtet. Det returnerade värdet är alltid icke-null. Läs/skriv [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Returnerar:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Tilldelning av null-värde är inte tillåtet. Det returnerade värdet är alltid icke-null. Läs/skriv [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Returnerar eller sätter värdet som en bokstavlig sträng. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Returnerar eller sätter värdet som en bokstavlig sträng. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Returnerar eller sätter Data-objekt. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Returnerar eller sätter Data-objekt. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Returnerar strängvärdesdata. Returnerar null om DataSourceType är falskt och inget strängvärde har tilldelats.

**Returnerar:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Sätter värdet från angiven cell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Om egenskapen DataSourceType är DataSourceType.Worksheet returnerar den här metoden adressen till cellerna i arbetsboken som representerar strängdata. Annars returneras en tom sträng.

**Returnerar:**
java.lang.String