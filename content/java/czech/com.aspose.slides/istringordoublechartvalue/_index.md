---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides pro Java API Referenci
description: Reprezentuje řetězec nebo hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako literální hodnota.
type: docs
url: /cs/com.aspose.slides/istringordoublechartvalue/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje řetězec nebo hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako literální hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje literální řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje literální řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Vrací nebo nastavuje literální double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Vrací nebo nastavuje literální double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Převede hodnotu na double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Vrací nebo nastavuje literální řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Čtení/zápis String.

**Vrací:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Vrací nebo nastavuje literální řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Vrací nebo nastavuje literální double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. Čtení/zápis double.

**Vrací:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Vrací nebo nastavuje literální double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Převede hodnotu na double.

**Vrací:**
double - Hodnota typu double