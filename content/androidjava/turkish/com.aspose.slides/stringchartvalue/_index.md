---
title: StringChartValue
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: String değerini iki şekilde temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre/hücrelerde, 2) literal değer olarak, pptx sunum belgesinde depolanabilir.
type: docs
url: /tr/com.aspose.slides/stringchartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

pptx sunum belgesinde saklanabilen string değerini iki şekilde temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre/hücrelerde; 2) literal değer olarak.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getAsCells()](#getAsCells--) | Null değer ataması yasaktır. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Null değer ataması yasaktır. |
| [getAsLiteralString()](#getAsLiteralString--) | Değeri literal metin olarak döndürür veya ayarlar. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Değeri literal metin olarak döndürür veya ayarlar. |
| [getData()](#getData--) | Data nesnesini döndürür veya ayarlar. |
| [setData(Object value)](#setData-java.lang.Object-) | Data nesnesini döndürür veya ayarlar. |
| [toString()](#toString--) | String değer verisini döndürür. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Belirtilen hücreden değeri ayarlar. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, string verisini temsil eden hücrelerin çalışma kitabındaki adresini döndürür. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Null değer ataması yasaktır. Dönen değer her zaman null değildir. Okuma/Yazma [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Döndürür:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Null değer ataması yasaktır. Dönen değer her zaman null değildir. Okuma/Yazma [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Değeri literal metin olarak döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Değeri literal metin olarak döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

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

### toString() {#toString--}
```
public String toString()
```

String değer verisini döndürür. DataSourceType false ise ve bir string değeri atanmadıysa null döndürür.

**Döndürür:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Belirtilen hücreden değeri ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, string verisini temsil eden hücrelerin çalışma kitabındaki adresini döndürür. Aksi takdirde boş string döndürür.

**Döndürür:**
java.lang.String