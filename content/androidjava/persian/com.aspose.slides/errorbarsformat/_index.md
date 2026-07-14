---
title: ErrorBarsFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر نوارهای خطای سری نمودار.
type: docs
url: /fa/com.aspose.slides/errorbarsformat/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

نمایش نوارهای خطای سری نمودار. مقدارهای سفارشی ErrorBars در IChartDataPointCollection (در ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))) قرار دارند.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | دریافت یا تنظیم نوع نوارهای خطا. |
| [setType(int value)](#setType-int-) | دریافت یا تنظیم نوع نوارهای خطا. |
| [getValueType()](#getValueType--) | راه‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. |
| [setValueType(int value)](#setValueType-int-) | راه‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. |
| [hasEndCap()](#hasEndCap--) | مشخص می‌کند که یک سر انتهایی روی نوارهای خطا رسم نمی‌شود. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | مشخص می‌کند که یک سر انتهایی روی نوارهای خطا رسم نمی‌شود. |
| [getValue()](#getValue--) | دریافت یا تنظیم مقداری که همراه با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [setValue(float value)](#setValue-float-) | دریافت یا تنظیم مقداری که همراه با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [getFormat()](#getFormat--) | قالب نوارهای خطا را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | قالب نوارهای خطا را نشان می‌دهد. |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [isVisible()](#isVisible--) | دریافت یا تنظیم قابلیت مشاهده نوارهای خطا. |
| [setVisible(boolean value)](#setVisible-boolean-) | دریافت یا تنظیم قابلیت مشاهده نوارهای خطا. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد یک FillFormat را برمی‌گرداند. |
### getType() {#getType--}
```
public final int getType()
```

دریافت یا تنظیم نوع نوارهای خطا. خواندنی/نوشتنی [ErrorBarType](../../com.aspose.slides/errorbartype).

**بازگشت:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

دریافت یا تنظیم نوع نوارهای خطا. خواندنی/نوشتنی [ErrorBarType](../../com.aspose.slides/errorbartype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

راه‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. در حالت نوع مقدار سفارشی برای مشخص کردن مقدار، از ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) نقطه داده خاص در مجموعه DataPoints سری استفاده کنید. در حالت نوع مقدار Fixed، Percentage یا StandardDeviation، از ویژگی Value برای مشخص کردن مقدار استفاده کنید. خواندنی/نوشتنی [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**بازگشت:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

راه‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. در حالت نوع مقدار سفارشی برای مشخص کردن مقدار، از ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) نقطه داده خاص در مجموعه DataPoints سری استفاده کنید. در حالت نوع مقدار Fixed، Percentage یا StandardDeviation، از ویژگی Value برای مشخص کردن مقدار استفاده کنید. خواندنی/نوشتنی [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

مشخص می‌کند که یک سر انتهایی روی نوارهای خطا رسم نمی‌شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

مشخص می‌کند که یک سر انتهایی روی نوارهای خطا رسم نمی‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

دریافت یا تنظیم مقدار که همراه با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برگردانده می‌شود. خواندنی/نوشتنی float.

**بازگشت:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

دریافت یا تنظیم مقدار که همراه با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برگردانده می‌شود. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

قالب نوارهای خطا را نشان می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

قالب نوارهای خطا را نشان می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

دریافت یا تنظیم قابلیت مشاهده نوارهای خطا. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

دریافت یا تنظیم قابلیت مشاهده نوارهای خطا. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)