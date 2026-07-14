---
title: StringChartValue
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من ورقة العمل المرتبطة بالمخطط 2) كقيمة حرفية.
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

يمثل قيمة سلسلة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من ورقة العمل المرتبطة بالمخطط؛ 2) كقيمة حرفية.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAsCells()](#getAsCells--) | تعيين قيمة null غير مسموح به. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | تعيين قيمة null غير مسموح به. |
| [getAsLiteralString()](#getAsLiteralString--) | يرجع أو يحدد القيمة كسلسلة حرفية. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | يرجع أو يحدد القيمة كسلسلة حرفية. |
| [getData()](#getData--) | يرجع أو يحدد كائن Data. |
| [setData(Object value)](#setData-java.lang.Object-) | يرجع أو يحدد كائن Data. |
| [toString()](#toString--) | يرجع بيانات قيمة السلسلة. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | يحدد القيمة من الخلية المحددة. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | إذا كانت الخاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في ورقة العمل التي تمثل بيانات السلسلة. |

### getAsCells() {#getAsCells--}}
```
public final IChartCellCollection getAsCells()
```

تعيين قيمة null غير مسموح به. القيمة المرتجعة دائمًا غير null. قراءة/كتابة [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**القيم المرتجعة:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

تعيين قيمة null غير مسموح به. القيمة المرتجعة دائمًا غير null. قراءة/كتابة [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

يرجع أو يحدد القيمة كسلسلة حرفية. قراءة/كتابة String.

**القيم المرتجعة:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

يرجع أو يحدد القيمة كسلسلة حرفية. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

يرجع أو يحدد كائن Data. قراءة/كتابة Object.

**القيم المرتجعة:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

يرجع أو يحدد كائن Data. قراءة/كتابة Object.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

يرجع بيانات قيمة السلسلة. يرجع null إذا كان DataSourceType false ولم يتم تعيين قيمة سلسلة.

**القيم المرتجعة:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

يحدد القيمة من الخلية المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | خلية. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}}
```
public final String getCellsAddressInWorkbook()
```

إذا كانت خاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في ورقة العمل التي تمثل بيانات السلسلة. وإلا تُرجع سلسلة فارغة.

**القيم المرتجعة:**
java.lang.String