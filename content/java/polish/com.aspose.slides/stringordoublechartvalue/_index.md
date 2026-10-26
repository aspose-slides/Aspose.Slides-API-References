---
title: StringOrDoubleChartValue
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje wartość typu string lub double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem, 2) jako wartość literałowa.
type: docs
url: /pl/com.aspose.slides/stringordoublechartvalue/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Reprezentuje wartość typu string lub double, która może być przechowywana w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanym z wykresem; 2) jako wartość literałowa.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsCell()](#getAsCell--) | Zwraca lub ustawia komórkę danych wykresu. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Zwraca lub ustawia komórkę danych wykresu. |
| [getAsLiteralString()](#getAsLiteralString--) | Zwraca lub ustawia wartość jako ciąg znaków literałowy. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Zwraca lub ustawia wartość jako ciąg znaków literałowy. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Zwraca lub ustawia wartość jako podwójny literał (double). |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Zwraca lub ustawia wartość jako podwójny literał (double). |
| [getData()](#getData--) | Zwraca lub ustawia obiekt Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Zwraca lub ustawia obiekt Data. |
| [toDouble()](#toDouble--) | Konwertuje na double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Zwraca lub ustawia komórkę danych wykresu. Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Zwraca lub ustawia komórkę danych wykresu. Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Zwraca lub ustawia wartość jako ciąg znaków literałowy. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Zwraca lub ustawia wartość jako ciąg znaków literałowy. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Zwraca lub ustawia wartość jako podwójny literał (double). Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Zwraca lub ustawia wartość jako podwójny literał (double). Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
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
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konwertuje na double.

**Zwraca:**
double - wartość Double.