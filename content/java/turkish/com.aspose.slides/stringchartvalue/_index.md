---
title: StringChartValue
second_title: Aspose.Slides için Java API Referansı
description: pptx sunum belgesinde saklanabilecek string değerini iki şekilde temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre/ hücrelerde, 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/stringchartvalue/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

pptx sunum belgesinde saklanabilecek string değeri iki şekilde temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre(ler)de; 2) literal değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsCells()](#getAsCells--) | Null değer ataması izin verilmez. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Null değer ataması izin verilmez. |
| [getAsLiteralString()](#getAsLiteralString--) | Değeri literal string olarak alır veya ayarlar. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Değeri literal string olarak alır veya ayarlar. |
| [getData()](#getData--) | Data nesnesini alır veya ayarlar. |
| [setData(Object value)](#setData-java.lang.Object-) | Data nesnesini alır veya ayarlar. |
| [toString()](#toString--) | String değer verisini döndürür. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Belirtilen hücreden değeri ayarlar. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, string veriyi temsil eden çalışma kitabındaki hücrelerin adresini döndürür. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Null değer ataması izin verilmez. Dönen değer her zaman null değildir. Okuma/Yazma [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Döndürür:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Null değer ataması izin verilmez. Dönen değer her zaman null değildir. Okuma/Yazma [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Değeri literal string olarak alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Değeri literal string olarak alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Data nesnesini alır veya ayarlar. Okuma/Yazma Object.

**Döndürür:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data nesnesini alır veya ayarlar. Okuma/Yazma Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

String değer verisini döndürür. DataSourceType false ise ve herhangi bir string değer atanmadıysa null döndürür.

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

DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, string veriyi temsil eden çalışma kitabındaki hücrelerin adresini döndürür. Aksi takdirde boş string döndürür.

**Döndürür:**
java.lang.String