---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: نمایانگر مقداری از یک نمودار است.
type: docs
url: /fa/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

نمایانگر مقداری از یک نمودار است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | مشخص می‌کند کدام یک از خصوصیات AsCell یا AsLiteralString یا AsLiteralDouble فعال است. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | مشخص می‌کند کدام یک از خصوصیات AsCell یا AsLiteralString یا AsLiteralDouble فعال است. |
| [getData()](#getData--) | قابل خواندن/قابل نوشتن Object. |
| [setData(Object value)](#setData-java.lang.Object-) | قابل خواندن/قابل نوشتن Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


مشخص می‌کند کدام یک از خصوصیات AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار خصوصیت Data را تعیین می‌کند. این خصوصیت فقط-خواندنی است. برای تغییر مقدار این خصوصیت می‌توانید از یکی از خصوصیات ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. قابل خواندن/قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**بازگشت:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


مشخص می‌کند کدام یک از خصوصیات AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار خصوصیت Data را تعیین می‌کند. این خصوصیت فقط-خواندنی است. برای تغییر مقدار این خصوصیت می‌توانید از یکی از خصوصیات ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. قابل خواندن/قابل نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


قابل خواندن/قابل نوشتن Object.

**بازگشت:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


قابل خواندن/قابل نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |