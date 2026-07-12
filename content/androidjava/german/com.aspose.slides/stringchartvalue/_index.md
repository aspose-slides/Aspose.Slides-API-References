---
title: StringChartValue
second_title: Aspose.Slides für Android über Java API-Referenz
description: "Stellt einen Zeichenfolgenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle(n) einer Arbeitsmappe, die mit einem Diagramm verknüpft ist; 2) als literaler Wert."
type: docs
url: /de/com.aspose.slides/stringchartvalue/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Stellt einen Zeichenfolgenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle(n) einer Arbeitsmappe, die mit einem Diagramm verknüpft ist; 2) als literaler Wert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsCells()](#getAsCells--) | Das Zuweisen eines Nullwerts ist nicht erlaubt. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Das Zuweisen eines Nullwerts ist nicht erlaubt. |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt den Wert als literale Zeichenfolge zurück oder setzt ihn. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt den Wert als literale Zeichenfolge zurück oder setzt ihn. |
| [getData()](#getData--) | Gibt das Data-Objekt zurück oder setzt es. |
| [setData(Object value)](#setData-java.lang.Object-) | Gibt das Data-Objekt zurück oder setzt es. |
| [toString()](#toString--) | Gibt die Zeichenfolgendaten zurück. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Setzt den Wert aus der angegebenen Zelle. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen in der Arbeitsmappe zurück, die die Zeichenfolgendaten repräsentieren. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Das Zuweisen eines Nullwerts ist nicht erlaubt. Der zurückgegebene Wert ist immer nicht null. Lesen/Schreiben [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Rückgabe:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Das Zuweisen eines Nullwerts ist nicht erlaubt. Der zurückgegebene Wert ist immer nicht null. Lesen/Schreiben [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Gibt den Wert als literale Zeichenfolge zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Gibt den Wert als literale Zeichenfolge zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Gibt das Data-Objekt zurück oder setzt es. Lesen/Schreiben Object.

**Rückgabe:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Gibt das Data-Objekt zurück oder setzt es. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Gibt die Zeichenfolgendaten zurück. Gibt null zurück, wenn DataSourceType false ist und kein Zeichenfolgenwert zugewiesen wurde.

**Rückgabe:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Setzt den Wert aus der angegebenen Zelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen in der Arbeitsmappe zurück, die die Zeichenfolgendaten repräsentieren. Andernfalls wird ein leerer String zurückgegeben.

**Rückgabe:**
java.lang.String