---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /fa/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

نمایانگر مقدار یک نمودار است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. |
| [getData()](#getData--) | خواندن/نوشتن Object. |
| [setData(Object value)](#setData-java.lang.Object-) | خواندن/نوشتن Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. این ویژگی فقط-خواندنی است. برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. خواندن/نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**بازگرداندن:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. این ویژگی فقط-خواندنی است. برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. خواندن/نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


خواندن/نوشتن Object.

**بازگرداندن:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


خواندن/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |