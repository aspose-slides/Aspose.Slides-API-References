---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: يمثل قيمةً لمخطط.
type: docs
url: /ar/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

يمثل قيمةً لمخطط.
## الطرق

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. |
| [getData()](#getData--) | قراءة/كتابة Object. |
| [setData(Object value)](#setData-java.lang.Object-) | قراءة/كتابة Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بمعنى آخر، يحدد نوع قيمة الخاصية Data. هذه الخاصية قراءة فقط. لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**الإرجاع:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بمعنى آخر، يحدد نوع قيمة الخاصية Data. هذه الخاصية قراءة فقط. لتغيير قيمة هذه الخاصية يمكنك استخدام إحدى خصائص ChartDataPointCollection.DataSourceTypeFor<...>. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**المعاملات:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |