---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides pro Android - referenční příručka Java API
description: Reprezentuje řetězec nebo číselnou hodnotu, která může být v dokumentu prezentace pptx uložena dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/istringordoublechartvalue/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Reprezentuje řetězec nebo číselnou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s diagramem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Vrací nebo nastavuje doslovné číslo typu double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Vrací nebo nastavuje doslovné číslo typu double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Převádí hodnotu na double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Vrací nebo nastavuje doslovné číslo typu double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. Čtení/Zápis double.

**Vrací:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Vrací nebo nastavuje doslovné číslo typu double, pokud je vlastnost DataSourceType nastavena na DataSourceType.DoubleLiterals. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Převádí hodnotu na double.

**Vrací:**
double - Double hodnota double