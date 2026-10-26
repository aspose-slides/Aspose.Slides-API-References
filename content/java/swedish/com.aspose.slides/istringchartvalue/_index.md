---
title: IStringChartValue
second_title: Aspose.Slides för Java API-referens
description: Representerar strängvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/en cell i arbetsbok relaterad till diagram; 2) som bokstavligt värde.
type: docs
url: /sv/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Representerar ett strängvärde som kan lagras i pptx-presentationsdokument på två sätt: 1) i cell/en cell i arbetsbok relaterad till diagram; 2) som bokstavligt värde.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. |
| [toString()](#toString--) | Returnerar strängrepresentation. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ställer in värdet från angiven cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Om egenskapen DataSourceType är DataSourceType.Worksheet returnerar denna metod adressen till cellerna i arbetsboken som representerar strängdata. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. Läs/skriv String.

**Returnerar:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Returnerar eller anger den bokstavliga strängen om egenskapen DataSourceType är DataSourceType.StringLiterals. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Returnerar strängrepresentation.

**Returnerar:**
java.lang.String - Strängrepresentation av ett värde String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Ställer in värdet från angiven cell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Om egenskapen DataSourceType är DataSourceType.Worksheet returnerar denna metod adressen till cellerna i arbetsboken som representerar strängdata. Annars returneras en tom sträng.

**Returnerar:**
java.lang.String - String value String