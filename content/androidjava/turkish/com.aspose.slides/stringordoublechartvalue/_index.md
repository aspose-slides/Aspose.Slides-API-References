---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Android Java API Referansı aracılığıyla
description: pptx sunum belgesinde iki şekilde saklanabilen string veya double değeri temsil eder: 1) grafiğe ilişkin çalışma kitabının hücre/hücrelerinde; 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/stringordoublechartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen string veya double değeri temsil eder: 1) grafiğe ilişkin çalışma kitabının hücre/hücrelerinde; 2) literal değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsCell()](#getAsCell--) | Grafik veri hücresini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Grafik veri hücresini döndürür veya ayarlar. |
| [getAsLiteralString()](#getAsLiteralString--) | Değeri literal dize olarak döndürür veya ayarlar. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Değeri literal dize olarak döndürür veya ayarlar. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Değeri literal double olarak döndürür veya ayarlar. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Değeri literal double olarak döndürür veya ayarlar. |
| [getData()](#getData--) | Data nesnesini döndürür veya ayarlar. |
| [setData(Object value)](#setData-java.lang.Object-) | Data nesnesini döndürür veya ayarlar. |
| [toDouble()](#toDouble--) | Double'a dönüştürür. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Grafik veri hücresini döndürür veya ayarlar. Okuma/Yazma [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Grafik veri hücresini döndürür veya ayarlar. Okuma/Yazma [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Değeri literal dize olarak döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Değeri literal dize olarak döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Değeri literal double olarak döndürür veya ayarlar. Okuma/Yazma double.

**Döndürür:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Değeri literal double olarak döndürür veya ayarlar. Okuma/Yazma double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Data nesnesini döndürür veya ayarlar. Okuma/Yazma Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data nesnesini döndürür veya ayarlar. Okuma/Yazma Object.

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
double - Double değeri.