---
title: BaseChartValue
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل قيمة مخطط.
type: docs
url: /ar/com.aspose.slides/basechartvalue/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

يمثل قيمة مخطط.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble سارية في الفروع. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble سارية في الفروع. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

 yحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble سارية في الفروع. بعبارة أخرى يحدد نوع قيمة الخاصية Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

بالنسبة للنقاط في ChartDataPointCollection هذه الخاصية قراءة فقط. في هذه الحالة لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>.

**القيمة المرجعة:**
int

### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

 يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble سارية في الفروع. بعبارة أخرى يحدد نوع قيمة الخاصية Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

بالنسبة للنقاط في ChartDataPointCollection هذه الخاصية قراءة فقط. في هذه الحالة لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. قراءة/كتابة Object.

**القيمة المرجعة:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. قراءة/كتابة Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject