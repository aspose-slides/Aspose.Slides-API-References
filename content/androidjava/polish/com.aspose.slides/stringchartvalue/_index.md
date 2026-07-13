---
title: StringChartValue
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje wartość tekstową, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem, 2) jako wartość literalną.
type: docs
url: /pl/com.aspose.slides/stringchartvalue/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Reprezentuje wartość ciągu znaków, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość literalną.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsCells()](#getAsCells--) | Przypisanie wartości null nie jest dozwolone. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Przypisanie wartości null nie jest dozwolone. |
| [getAsLiteralString()](#getAsLiteralString--) | Zwraca lub ustawia wartość jako ciąg znaków literalny. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Zwraca lub ustawia wartość jako ciąg znaków literalny. |
| [getData()](#getData--) | Zwraca lub ustawia obiekt Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Zwraca lub ustawia obiekt Data. |
| [toString()](#toString--) | Zwraca dane wartości ciągu znaków. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ustawia wartość z określonej komórki. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, metoda zwraca adres komórek w skoroszycie, które reprezentują dane ciągu znaków. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Przypisanie wartości null nie jest dozwolone. Zwracana wartość zawsze nie jest null. Odczyt/zapis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Zwraca:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Przypisanie wartości null nie jest dozwolone. Zwracana wartość zawsze nie jest null. Odczyt/zapis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Zwraca lub ustawia wartość jako ciąg znaków literalny. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Zwraca lub ustawia wartość jako ciąg znaków literalny. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Zwraca lub ustawia obiekt Data. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Zwraca lub ustawia obiekt Data. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Zwraca dane wartości ciągu znaków. Zwraca null, jeśli DataSourceType jest false i nie przypisano wartości ciągu znaków.

**Zwraca:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Ustawia wartość z określonej komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, metoda zwraca adres komórek w skoroszycie, które reprezentują dane ciągu znaków. W przeciwnym razie zwraca pusty ciąg.

**Zwraca:**
java.lang.String