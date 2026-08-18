---
title: DoubleChartValue
second_title: Aspose.Slides for Java API Referansı
description: pptx sunum belgesinde iki şekilde saklanabilen double değerini temsil eder: 1) grafikle ilişkili çalışma kitabının hücre/hücrelerinde; 2) doğrudan değer olarak.
type: docs
url: /tr/com.aspose.slides/doublechartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen double değerini temsil eder: 1) grafikle ilişkili çalışma kitabının hücre/hücrelerinde; 2) doğrudan değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsCell()](#getAsCell--) | Grafik veri hücresini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Grafik veri hücresini döndürür veya ayarlar. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Değeri literal double olarak döndürür veya ayarlar. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Değeri literal double olarak döndürür veya ayarlar. |
| [getData()](#getData--) | Data nesnesini döndürür veya ayarlar. |
| [setData(Object value)](#setData-java.lang.Object-) | Data nesnesini döndürür veya ayarlar. |
| [toDouble()](#toDouble--) | Double'a dönüştürür. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Grafik veri hücresini döndürür veya ayarlar. Okunur/Yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Grafik veri hücresini döndürür veya ayarlar. Okunur/Yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Değeri literal double olarak döndürür veya ayarlar. Okunur/Yazılır double.

**Döndürür:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Değeri literal double olarak döndürür veya ayarlar. Okunur/Yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Data nesnesini döndürür veya ayarlar. Okunur/Yazılır Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Data nesnesini döndürür veya ayarlar. Okunur/Yazılır Object.

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
double - LiteralDouble döndürür eğer DataSourceType DoubleLiterals'a eşitse. Eğer DataSourceType Worksheet'e eşitse, double hücre değeri olarak başarılı bir şekilde dönüştürülmüş değeri döndürür, aksi takdirde NaN.