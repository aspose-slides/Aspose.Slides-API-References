---
title: IStringChartValue
second_title: Aspose.Slides dla Java - Dokumentacja API
description: Reprezentuje wartość ciągu znaków, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem, 2) jako wartość dosłowną.
type: docs
url: /pl/com.aspose.slides/istringchartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Reprezentuje wartość ciągu znaków, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Zwraca lub ustawia dosłowny ciąg znaków, jeśli właściwość DataSourceType jest DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Zwraca lub ustawia dosłowny ciąg znaków, jeśli właściwość DataSourceType jest DataSourceType.StringLiterals. |
| [toString()](#toString--) | Zwraca reprezentację ciągu znaków. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ustawia wartość z określonej komórki. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Jeśli właściwość DataSourceType jest DataSourceType.Worksheet, to ta metoda zwraca adres komórek w skoroszycie, które reprezentują dane w postaci ciągu znaków. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

**Zwraca:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Zwraca lub ustawia dosłowny ciąg znaków, jeśli właściwość DataSourceType jest DataSourceType.StringLiterals. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### toString() {#toString--}
```
public abstract String toString()
```

Zwraca reprezentację ciągu znaków.

**Zwraca:**  
java.lang.String - String wartość String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Ustawia wartość z określonej komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Jeśli właściwość DataSourceType jest DataSourceType.Worksheet, to ta metoda zwraca adres komórek w skoroszycie, które reprezentują dane w postaci ciągu znaków. W przeciwnym razie zwraca pusty ciąg.

**Zwraca:**  
java.lang.String - String wartość String