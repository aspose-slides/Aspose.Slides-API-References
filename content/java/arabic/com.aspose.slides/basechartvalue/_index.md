---
title: BaseChartValue
second_title: مرجع Aspose.Slides لواجهة برمجة التطبيقات للغة Java
description: يمثل قيمة مخطّط.
type: docs
url: /ar/com.aspose.slides/basechartvalue/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

يمثل قيمة مخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble فعلية في الفروع. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble فعلية في الفروع. |
| [getData()](#getData--) | البيانات. |
| [setData(Object value)](#setData-java.lang.Object-) | البيانات. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble فعلية في الفروع. بعبارة أخرى يحدد نوع قيمة الخاصية Data. قابل للقراءة والكتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

لنقاط في ChartDataPointCollection هذه الخاصية للقراءة فقط. في هذه الحالة لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>.

**القيمة المرجعة:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

يحدد ما إذا كانت الخاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble فعلية في الفروع. بعبارة أخرى يحدد نوع قيمة الخاصية Data. قابل للقراءة والكتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

لنقاط في ChartDataPointCollection هذه الخاصية للقراءة فقط. في هذه الحالة لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

البيانات. قابل للقراءة والكتابة Object.

**القيمة المرجعة:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

البيانات. قابل للقراءة والكتابة Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد الكائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject