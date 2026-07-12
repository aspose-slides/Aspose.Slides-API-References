---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android için Java API Referansı
description: pptx sunum belgesinde iki şekilde depolanabilen dize veya double değerini temsil eder: 1) grafiğe bağlı çalışma kitabının hücre/ hücrelerinde; 2) literal değer olarak.
type: docs
url: /tr/com.aspose.slides/istringordoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

pptx sunum belgesinde iki şekilde depolanabilen dize veya double değerini temsil eder: 1) grafiğe ilişkin çalışma kitabının hücre/ hücrelerinde; 2) literal değer olarak.
## Yöntemler

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType özelliği DataSourceType.DoubleLiterals ise literal double'ı döndürür veya ayarlar. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType özelliği DataSourceType.DoubleLiterals ise literal double'ı döndürür veya ayarlar. |
| [toDouble()](#toDouble--) | Değeri double'a dönüştürür. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/Yazılır String.

**Dönen Değer:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

DataSourceType özelliği DataSourceType.StringLiterals ise literal dizeyi döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType özelliği DataSourceType.DoubleLiterals ise literal double'ı döndürür veya ayarlar. Okunur/Yazılır double.

**Dönen Değer:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType özelliği DataSourceType.DoubleLiterals ise literal double'ı döndürür veya ayarlar. Okunur/Yazılır double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Değeri double'a dönüştürür.

**Dönen Değer:**
double - Double value double