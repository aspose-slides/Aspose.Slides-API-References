---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje wartość typu string lub double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość literalną.
type: docs
url: /pl/com.aspose.slides/istringordoublechartvalue/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje wartość typu string lub double, którą można przechowywać w dokumencie prezentacji pptx na dwa sposoby: 1) w komórce/komórkach skoroszytu powiązanego z wykresem; 2) jako wartość literalną.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Zwraca lub ustawia literalny string, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Zwraca lub ustawia literalny string, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType ma wartość DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType ma wartość DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konwertuje wartość na double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Zwraca lub ustawia literalny string, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Zwraca lub ustawia literalny string, jeśli właściwość DataSourceType ma wartość DataSourceType.StringLiterals. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType ma wartość DataSourceType.DoubleLiterals. Odczyt/zapis double.

**Zwraca:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Zwraca lub ustawia literalny double, jeśli właściwość DataSourceType ma wartość DataSourceType.DoubleLiterals. Odczyt/zapis double.

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
double - Double value double