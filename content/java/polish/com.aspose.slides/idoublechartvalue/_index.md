---
title: IDoubleChartValue
second_title: Aspose.Slides dla dokumentacji API Java
description: Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem, 2) jako wartość literalną.
type: docs
url: /pl/com.aspose.slides/idoublechartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje wartość typu double, która może być przechowywana w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość literalna.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Zwraca lub ustawia literalną wartość typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Zwraca lub ustawia literalną wartość typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konwertuje na double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Zwraca lub ustawia literalną wartość typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Zwraca lub ustawia literalną wartość typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konwertuje na double.

**Zwraca:**
double - wartość Double.