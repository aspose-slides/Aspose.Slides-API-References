---
title: IDoubleChartValue
second_title: Aspose.Slides dla Androida poprzez dokumentację Java API
description: Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość literał.
type: docs
url: /pl/com.aspose.slides/idoublechartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje wartość typu double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanym z wykresem; 2) jako wartość literał.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Zwraca lub ustawia wartość literału typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Zwraca lub ustawia wartość literału typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konwertuje na double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Zwraca lub ustawia wartość literału typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Zwraca lub ustawia wartość literału typu double, jeśli DataSourceType = Charts.DataSourceType.DoubleLiterals. Odczyt/zapis double.

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
double - wartość typu double.