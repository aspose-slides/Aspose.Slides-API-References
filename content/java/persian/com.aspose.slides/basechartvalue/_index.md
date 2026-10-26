---
title: BaseChartValue
second_title: مرجع API Aspose.Slides برای جاوا
description: مقدار یک نمودار را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/basechartvalue/
---
**ارث‌بری:**
java.lang.Object

**تمامی رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

یک مقدار از یک نمودار را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | مشخص می‌کند که آیا ویژگی AsCell، AsCells، AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | مشخص می‌کند که آیا ویژگی AsCell، AsCells، AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

مشخص می‌کند که آیا ویژگی AsCell، AsCells، AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. خواندن/نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

برای نقاط در ChartDataPointCollection این ویژگی فقط-خواندنی است. در این صورت برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید.

**بازگشت:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

مشخص می‌کند که آیا ویژگی AsCell، AsCells، AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. خواندن/نوشتن [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

برای نقاط در ChartDataPointCollection این ویژگی فقط-خواندنی است. در این صورت برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. خواندن/نوشتن Object.

**بازگشت:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. خواندن/نوشتن Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject