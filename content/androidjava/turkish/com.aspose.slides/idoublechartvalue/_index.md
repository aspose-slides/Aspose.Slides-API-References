---
title: IDoubleChartValue
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: pptx sunum belgesinde iki şekilde saklanabilen çift değeri temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre/hücrelerde; 2) doğrudan değer olarak.
type: docs
url: /tr/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen çift değeri temsil eder: 1) grafikle ilişkili çalışma kitabındaki hücre/hucrelerde; 2) doğrudan değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals ise literal çift değer döndürür veya ayarlar. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals ise literal çift değer döndürür veya ayarlar. |
| [toDouble()](#toDouble--) | Double'a dönüştürür. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


DataSourceType = Charts.DataSourceType.DoubleLiterals ise literal çift değer döndürür veya ayarlar. Okunur/yazılabilir çift.

**Dönen Değer:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


DataSourceType = Charts.DataSourceType.DoubleLiterals ise literal çift değer döndürür veya ayarlar. Okunur/yazılabilir çift.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Double'a dönüştürür.

**Dönen Değer:**
double - Double değeri.