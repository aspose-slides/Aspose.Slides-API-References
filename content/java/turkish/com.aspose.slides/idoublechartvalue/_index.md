---
title: IDoubleChartValue
second_title: Aspose.Slides için Java API Referansı
description: pptx sunum belgesinde iki şekilde saklanabilen double değeri temsil eder: 1) grafikle ilişkili çalışma kitabındaki hücre/hücrelerde; 2) doğrudan değer olarak.
type: docs
url: /tr/com.aspose.slides/idoublechartvalue/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen çift (double) değeri temsil eder: 1) grafikle ilişkili çalışma kitabındaki hücre/ hücrelerde; 2) doğrudan değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals olduğunda doğrudan çift (double) değeri alır veya ayarlar. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals olduğunda doğrudan çift (double) değeri alır veya ayarlar. |
| [toDouble()](#toDouble--) | Double’a dönüştürür. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


DataSourceType = Charts.DataSourceType.DoubleLiterals olduğunda doğrudan çift (double) değeri alır veya ayarlar. Okunur/yazılabilir double.

**Döndürür:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


DataSourceType = Charts.DataSourceType.DoubleLiterals olduğunda doğrudan çift (double) değeri alır veya ayarlar. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Double’a dönüştürür.

**Döndürür:**  
double - Double değeri.