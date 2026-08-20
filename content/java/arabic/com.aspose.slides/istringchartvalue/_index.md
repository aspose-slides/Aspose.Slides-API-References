---
title: IStringChartValue
second_title: مرجع API Aspose.Slides for Java
description: يمثل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي بصيغة pptx بطريقتين: 1) في خلية/خلايا من دفتر العمل المرتبط بالمخطط 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/istringchartvalue/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

يمثل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي بصيغة pptx بطريقتين: 1) في خلية/خلايا من دفتر العمل المرتبط بالمخطط؛ 2) كقيمة حرفية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | تُرجع أو تُعيّن السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | تُرجع أو تُعيّن السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. |
| [toString()](#toString--) | تُرجع تمثيل السلسلة. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | يُعيّن القيمة من الخلية المحددة. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | إذا كانت الخاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في دفتر العمل التي تمثل بيانات السلسلة. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


تُرجع أو تُعيّن السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


تُرجع أو تُعيّن السلسلة الحرفية إذا كانت الخاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


تُرجع تمثيل السلسلة.

**الإرجاع:**
java.lang.String - String representation of a value String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


يقوم بتعيين القيمة من الخلية المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | خلية. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


إذا كانت الخاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في دفتر العمل التي تمثل بيانات السلسلة. وإلا تُرجع سلسلة فارغة.

**الإرجاع:**
java.lang.String - String value String