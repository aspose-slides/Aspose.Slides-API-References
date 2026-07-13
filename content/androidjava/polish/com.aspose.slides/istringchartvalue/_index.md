---
title: IStringChartValue
second_title: Aspose.Slides dla Androida - odniesienie do Java API
description: Reprezentuje wartość łańcucha, która może być przechowywana w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanych z wykresem, 2) jako wartość literalna.
type: docs
url: /pl/com.aspose.slides/istringchartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Reprezentuje wartość łańcucha, która może być przechowywana w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanych z wykresem; 2) jako wartość literalna.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Zwraca lub ustawia łańcuch literałowy, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Zwraca lub ustawia łańcuch literałowy, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. |
| [toString()](#toString--) | Zwraca reprezentację łańcucha. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ustawia wartość z określonej komórki. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, metoda zwraca adres komórek w skoroszycie, które reprezentują dane łańcucha. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Zwraca lub ustawia łańcuch literałowy, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Zwraca lub ustawia łańcuch literałowy, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### toString() {#toString--}
```
public abstract String toString()
```

Zwraca reprezentację łańcucha.

**Zwraca:**
java.lang.String - Reprezentacja łańcucha wartości String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Ustawia wartość z określonej komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Jeśli właściwość DataSourceType ma wartość DataSourceType.Worksheet, metoda zwraca adres komórek w skoroszycie, które reprezentują dane łańcucha. W przeciwnym razie zwraca pusty łańcuch.

**Zwraca:**
java.lang.String - Wartość łańcucha String