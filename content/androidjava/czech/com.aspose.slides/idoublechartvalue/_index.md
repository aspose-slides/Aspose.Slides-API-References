---
title: IDoubleChartValue
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem, 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/idoublechartvalue/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Představuje hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Vrací nebo nastavuje doslovnou hodnotu typu double, pokud DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Vrací nebo nastavuje doslovnou hodnotu typu double, pokud DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Převádí na double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Vrací nebo nastavuje doslovnou hodnotu typu double, pokud DataSourceType = Charts.DataSourceType.DoubleLiterals. Čtení/zápis double.

**Vrací:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Vrací nebo nastavuje doslovnou hodnotu typu double, pokud DataSourceType = Charts.DataSourceType.DoubleLiterals. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Převádí na double.

**Vrací:**
double - Hodnota typu double.