---
title: IStringChartValue
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: تمثيل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من المصنف المرتبط بالمخطط 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/istringchartvalue/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

تمثل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من المصنف المرتبط بالمخطط؛ 2) كقيمة حرفية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | إرجاع أو ضبط السلسلة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | إرجاع أو ضبط السلسلة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. |
| [toString()](#toString--) | إرجاع تمثيل السلسلة. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | ضبط القيمة من الخلية المحددة. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | إذا كانت خاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في المصنف التي تمثل بيانات السلسلة. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

إرجاع أو ضبط السلسلة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

إرجاع أو ضبط السلسلة الحرفية إذا كانت خاصية DataSourceType هي DataSourceType.StringLiterals. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

إرجاع تمثيل السلسلة.

**الإرجاع:**
java.lang.String - تمثيل String لقيمة String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

ضبط القيمة من الخلية المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

إذا كانت خاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في المصنف التي تمثل بيانات السلسلة. وإلا تُرجع سلسلة فارغة.

**الإرجاع:**
java.lang.String - قيمة String