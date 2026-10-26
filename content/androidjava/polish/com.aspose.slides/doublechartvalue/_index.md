---
title: DoubleChartValue
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórkach/komórce skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną.
type: docs
url: /pl/com.aspose.slides/doublechartvalue/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako dosłowną wartość.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsCell()](#getAsCell--) | Zwraca lub ustawia komórkę danych wykresu. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Zwraca lub ustawia komórkę danych wykresu. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Zwraca lub ustawia wartość jako dosłowny double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Zwraca lub ustawia wartość jako dosłowny double. |
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
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Zwraca lub ustawia wartość jako dosłowny double. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Zwraca lub ustawia wartość jako dosłowny double. Odczyt/zapis double.

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
double - Zwraca LiteralDouble, jeśli DataSourceType jest równy DoubleLiterals. Jeśli DataSourceType jest równy Worksheet, zwraca pomyślnie skonwertowaną do double wartość komórki, w przeciwnym razie zwraca NaN.