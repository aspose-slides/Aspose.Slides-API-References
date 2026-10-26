---
title: DoubleChartValue
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem, 2) jako wartość dosłowną.
type: docs
url: /pl/com.aspose.slides/doublechartvalue/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Reprezentuje wartość podwójnej precyzji, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
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

Zwraca lub ustawia wartość jako literal double. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Zwraca lub ustawia wartość jako literal double. Odczyt/zapis double.

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
double - Zwraca LiteralDouble, jeśli DataSourceType jest równe DoubleLiterals. Jeśli DataSourceType jest równe Worksheet, zwraca pomyślnie przekonwertowaną wartość komórki typu double, w przeciwnym razie zwraca NaN.