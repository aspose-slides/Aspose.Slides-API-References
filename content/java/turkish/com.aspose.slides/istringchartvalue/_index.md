---
title: IStringChartValue
second_title: Aspose.Slides için Java API Referansı
description: pptx sunum belgesinde saklanabilen dize değerini iki şekilde temsil eder: 1) grafiğe bağlı çalışma kitabındaki hücre/hücrelerde, 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/istringchartvalue/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx sunum belgesinde saklanabilecek dize değerini iki şekilde temsil eder: 1) grafikle ilişkili çalışma kitabındaki hücre/hücrelerde; 2) literal değer olarak.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [toString()](#toString--) | Returns string representation. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Sets value from specified cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Dize temsilini döndürür.

**Döndürür:**
java.lang.String - Değer Stringinin dize temsili

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Belirtilen hücreden değeri ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

DataSourceType özelliği DataSourceType.Worksheet ise bu metot, dize verisini temsil eden çalışma kitabındaki hücrelerin adresini döndürür. Aksi takdirde boş dize döner.

**Döndürür:**
java.lang.String - String değeri String