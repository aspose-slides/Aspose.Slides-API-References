---
title: IStringOrDoubleChartValue
second_title: Referencja API Aspose.Slides dla Java
description: Reprezentuje wartość typu string lub double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość dosłowną.
type: docs
url: /pl/com.aspose.slides/istringordoublechartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje wartość ciągu znaków lub double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako dosłowną wartość.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Zwraca lub ustawia literalny ciąg znaków, jeśli właściwość DataSourceType jest DataSourceType.StringLiterals. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Zwraca lub ustawia literalny ciąg znaków, jeśli właściwość DataSourceType jest DataSourceType.StringLiterals. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType jest DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType jest DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konwertuje wartość na double.

**Zwraca:**
double - Double wartość double