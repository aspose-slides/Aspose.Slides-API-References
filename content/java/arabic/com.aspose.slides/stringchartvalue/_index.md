---
title: StringChartValue
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل قيمة نصية يمكن تخزينها في مستند عرض تقديمي بصيغة pptx بطريقتين: 1) في خلية/خلايا من جدول البيانات المرتبط بالمخطط، 2) كقيمة حرفية.
type: docs
url: /ar/com.aspose.slides/stringchartvalue/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

يمثل قيمة نصية يمكن تخزينها في مستند عرض تقديمي بصيغة pptx بطريقتين: 1) في خلية/خلايا من جدول البيانات المرتبط بالمخطط؛ 2) كقيمة حرفية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAsCells()](#getAsCells--) | تعيين قيمة فارغة غير مسموح به. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | تعيين قيمة فارغة غير مسموح به. |
| [getAsLiteralString()](#getAsLiteralString--) | إرجاع أو تعيين القيمة كسلسلة حرفية. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | إرجاع أو تعيين القيمة كسلسلة حرفية. |
| [getData()](#getData--) | إرجاع أو تعيين كائن Data. |
| [setData(Object value)](#setData-java.lang.Object-) | إرجاع أو تعيين كائن Data. |
| [toString()](#toString--) | إرجاع بيانات قيمة النص. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | تعيين القيمة من الخلية المحددة. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | إذا كانت خاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في جدول البيانات التي تمثّل بيانات النص. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

تعيين قيمة فارغة غير مسموح به. إرجاع القيمة دائمًا ليس null. قراءة/كتابة [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**الإرجاع:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

تعيين قيمة فارغة غير مسموح به. إرجاع القيمة دائمًا ليس null. قراءة/كتابة [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

إرجاع أو تعيين القيمة كسلسلة حرفية. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

إرجاع أو تعيين القيمة كسلسلة حرفية. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

إرجاع أو تعيين كائن Data. قراءة/كتابة Object.

**الإرجاع:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

إرجاع أو تعيين كائن Data. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

إرجاع بيانات قيمة النص. إرجاع null إذا كانت DataSourceType false ولم يتم تعيين قيمة نصية.

**الإرجاع:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

تعيين القيمة من الخلية المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | خلية. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

إذا كانت خاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في جدول البيانات التي تمثّل بيانات النص. وإلا تُرجع سلسلة فارغة.

**الإرجاع:**
java.lang.String