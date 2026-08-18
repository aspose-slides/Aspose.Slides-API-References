---
title: StringChartValue
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle(n) des Arbeitsblatts, das dem Diagramm zugeordnet ist; 2) als Literalwert.
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

Stellt einen Zeichenkettenwert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle(n) des Arbeitsblatts, das dem Diagramm zugeordnet ist; 2) als Literalwert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsCells()](#getAsCells--) | Das Zuweisen eines Nullwerts ist nicht erlaubt. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Das Zuweisen eines Nullwerts ist nicht erlaubt. |
| [getAsLiteralString()](#getAsLiteralString--) | Gibt den Wert als Literal-String zurück oder setzt ihn. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Gibt den Wert als Literal-String zurück oder setzt ihn. |
| [getData()](#getData--) | Gibt das Data-Objekt zurück oder setzt es. |
| [setData(Object value)](#setData-java.lang.Object-) | Gibt das Data-Objekt zurück oder setzt es. |
| [toString()](#toString--) | Gibt den Zeichenkettenwert zurück. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Setzt den Wert aus einer angegebenen Zelle. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenkettendaten repräsentieren. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Das Zuweisen eines Nullwerts ist nicht erlaubt. Der Rückgabewert ist stets nicht null. Lese/Schreiben [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Rückgabewert:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Das Zuweisen eines Nullwerts ist nicht erlaubt. Der Rückgabewert ist stets nicht null. Lese/Schreiben [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Gibt den Wert als Literal-String zurück oder setzt ihn. Lese/Schreiben String.

**Rückgabewert:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Gibt den Wert als Literal-String zurück oder setzt ihn. Lese/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Gibt das Data-Objekt zurück oder setzt es. Lese/Schreiben Object.

**Rückgabewert:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Gibt das Data-Objekt zurück oder setzt es. Lese/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Gibt den Zeichenkettenwert zurück. Gibt null zurück, wenn DataSourceType false ist und kein Zeichenkettenwert zugewiesen wurde.

**Rückgabewert:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Setzt den Wert aus einer angegebenen Zelle.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Wenn die Eigenschaft DataSourceType den Wert DataSourceType.Worksheet hat, gibt diese Methode die Adresse der Zellen im Arbeitsbuch zurück, die die Zeichenkettendaten repräsentieren. Andernfalls wird ein leerer String zurückgegeben.

**Rückgabewert:**
java.lang.String