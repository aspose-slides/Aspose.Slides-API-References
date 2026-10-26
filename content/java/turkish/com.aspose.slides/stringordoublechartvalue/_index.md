---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Java API Referansı
description: pptx sunum belgesinde iki şekilde depolanabilen string veya double değeri temsil eder: 1) grafiğe bağlı çalışma kitabının hücre/hücrelerinde; 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/stringordoublechartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

pptx sunum belgesinde iki şekilde depolanabilen string veya double değeri temsil eder: 1) grafiğe bağlı çalışma kitabının hücre/hücrelerinde; 2) literal değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets value as literal string. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets value as literal string. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Değeri grafik veri hücresi olarak döndürür veya ayarlar. Okunur/Yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Değeri grafik veri hücresi olarak döndürür veya ayarlar. Okunur/Yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Değeri literal string olarak döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Değeri literal string olarak döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

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

double'a dönüştürür.

**Döndürür:**
double - Double değeri.