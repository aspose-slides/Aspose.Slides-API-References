---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a value of a chart.
type: docs
url: /ar/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

يمثل قيمةً في مخطط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | تحدّد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | تحدّد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. |
| [getData()](#getData--) | قراءة/كتابة Object. |
| [setData(Object value)](#setData-java.lang.Object-) | قراءة/كتابة Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

تحدّد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بمعنى آخر تحدّد نوع قيمة الخاصية Data. هذه الخاصية قراءة فقط. لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**الإرجاع:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

تحدّد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بمعنى آخر تحدّد نوع قيمة الخاصية Data. هذه الخاصية قراءة فقط. لتغيير قيمة هذه الخاصة يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

قراءة/كتابة Object.

**الإرجاع:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

قراءة/كتابة Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |