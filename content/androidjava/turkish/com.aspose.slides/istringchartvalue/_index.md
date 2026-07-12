---
title: IStringChartValue
second_title: Aspose.Slides for Android via Java API Referansı
description: Pptx sunum belgesinde iki şekilde saklanabilen dize değerini temsil eder: 1) çizelgeye ilişkin çalışma kitabının hücrelerinde; 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/istringchartvalue/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx sunum belgesinde iki şekilde saklanabilen dize değerini temsil eder: 1) çizelgeye ilişkin çalışma kitabının hücrelerinde; 2) doğrudan değer olarak.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. |
| [toString()](#toString--) | Dize temsilini döndürür. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Belirtilen hücreden değeri ayarlar. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, dize verisini temsil eden çalışma kitabındaki hücrelerin adresini döndürür. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/yazılabilir String.

**Döndürür:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/yazılabilir String.

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
java.lang.String - Bir değer dizesinin temsili
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


Belirtilen hücreden değeri ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Hücre. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, dize verisini temsil eden çalışma kitabındaki hücrelerin adresini döndürür. Aksi takdirde boş dize döndürür.

**Döndürür:**  
java.lang.String - Dize değeri