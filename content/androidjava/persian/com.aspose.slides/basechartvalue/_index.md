---
title: BaseChartValue
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مقدار یک نمودار است.
type: docs
url: /fa/com.aspose.slides/basechartvalue/
---
**ارث-بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

نمایانگر مقدار یک نمودار است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | مشخص می‌کند که آیا ویژگی AsCell, AsCells, AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | مشخص می‌کند که آیا ویژگی AsCell, AsCells, AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. |
| [getData()](#getData--) | داده. |
| [setData(Object value)](#setData-java.lang.Object-) | داده. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

مشخص می‌کند که آیا ویژگی AsCell, AsCells, AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. به عبارت دیگر، نوع مقدار ویژگی Data را تعیین می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

برای نقاط در ChartDataPointCollection این ویژگی فقط‌خواندنی است. در این حالت برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید.

**باز می‌گردد:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

مشخص می‌کند که آیا ویژگی AsCell, AsCells, AsLiteralString یا AsLiteralDouble در کلاس‌های مشتق شده واقعی است. به عبارت دیگر، نوع مقدار ویژگی Data را تعیین می‌کند. خواندنی/نوشتنی [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

برای نقاط در ChartDataPointCollection این ویژگی فقط‌خواندنی است. در این حالت برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

داده. خواندنی/نوشتنی Object.

**باز می‌گردد:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

داده. خواندنی/نوشتنی Object.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

یک شیء Parent_Immediate را باز می‌گرداند. فقط‌خواندنی IDOMObject.

**باز می‌گردد:**
com.aspose.slides.IDOMObject