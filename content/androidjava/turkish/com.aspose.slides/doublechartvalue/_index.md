---
title: DoubleChartValue
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: pptx sunum belgesinde iki şekilde saklanabilen double değerini temsil eder: 1) grafiğe ilişkin çalışma kitabındaki hücre/hücrelerde; 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/doublechartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen double değerini temsil eder: 1) grafik ile ilişkili çalışma kitabındaki hücre/hücrelerde; 2) literal değer olarak.
## Yöntemler

| Yöntem | Açıklama |
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


Grafik veri hücresini döndürür veya ayarlar. Okunur/yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Grafik veri hücresini döndürür veya ayarlar. Okunur/yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Değeri literal double olarak döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Değeri literal double olarak döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Data nesnesini döndürür veya ayarlar. Okunur/yazılır Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Data nesnesini döndürür veya ayarlar. Okunur/yazılır Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Double'a dönüştürür.

**Döndürür:**
double - DataSourceType DoubleLiterals ise LiteralDouble döndürür. DataSourceType Worksheet ise double'a başarılı bir şekilde dönüştürülmüş hücre değerini döndürür, aksi takdirde NaN döndürür.