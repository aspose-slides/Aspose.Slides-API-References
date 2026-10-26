---
title: ErrorBarsFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نوارهای خطا را در سری نمودار نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/errorbarsformat/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

نمایش می‌دهد نوارهای خطا در سری نمودار. مقادیر سفارشی ErrorBars در IChartDataPointCollection (در ویژگی ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))) قرار دارند.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | دریافت یا تنظیم نوع نوارهای خطا. |
| [setType(int value)](#setType-int-) | دریافت یا تنظیم نوع نوارهای خطا. |
| [getValueType()](#getValueType--) | نمایش می‌دهد روش‌های ممکن برای تعیین طول نوارهای خطا. |
| [setValueType(int value)](#setValueType-int-) | نمایش می‌دهد روش‌های ممکن برای تعیین طول نوارهای خطا. |
| [hasEndCap()](#hasEndCap--) | مشخص می‌کند سر انتهایی در نوارهای خطا رسم نمی‌شود. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | مشخص می‌کند سر انتهایی در نوارهای خطا رسم نمی‌شود. |
| [getValue()](#getValue--) | دریافت یا تنظیم مقداری که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [setValue(float value)](#setValue-float-) | دریافت یا تنظیم مقداری که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [getFormat()](#getFormat--) | نمایش می‌دهد قالب نوارهای خطا. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | نمایش می‌دهد قالب نوارهای خطا. |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [isVisible()](#isVisible--) | دریافت یا تنظیم قابلیت نمایش نوارهای خطا. |
| [setVisible(boolean value)](#setVisible-boolean-) | دریافت یا تنظیم قابلیت نمایش نوارهای خطا. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک FillFormat را برمی‌گرداند. |
### getType() {#getType--}
```
public final int getType()
```


دریافت یا تنظیم نوع نوارهای خطا. قابل‌خواندن/قابل‌نوشتن [ErrorBarType](../../com.aspose.slides/errorbartype).

**بازگشت:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


دریافت یا تنظیم نوع نوارهای خطا. قابل‌خواندن/قابل‌نوشتن [ErrorBarType](../../com.aspose.slides/errorbartype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```


نمایش می‌دهد روش‌های ممکن برای تعیین طول نوارهای خطا. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، از ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) نقطه داده خاص در مجموعه DataPoints سری استفاده کنید. در صورت استفاده از نوع مقدار Fixed، Percentage یا StandardDeviation، از ویژگی Value برای تعیین مقدار استفاده کنید. قابل‌خواندن/قابل‌نوشتن [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**بازگشت:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```


نمایش می‌دهد روش‌های ممکن برای تعیین طول نوارهای خطا. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، از ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) نقطه داده خاص در مجموعه DataPoints سری استفاده کنید. در صورت استفاده از نوع مقدار Fixed، Percentage یا StandardDeviation، از ویژگی Value برای تعیین مقدار استفاده کنید. قابل‌خواندن/قابل‌نوشتن [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```


مشخص می‌کند سر انتهایی در نوارهای خطا رسم نمی‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**بازگشت:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```


مشخص می‌کند سر انتهایی در نوارهای خطا رسم نمی‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```


دریافت یا تنظیم مقداری که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن float.

**بازگشت:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


دریافت یا تنظیم مقداری که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برمی‌گرداند. قابل‌خواندن/قابل‌نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


نمایش می‌دهد قالب نوارهای خطا. قابل‌خواندن/قابل‌نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


نمایش می‌دهد قالب نوارهای خطا. قابل‌خواندن/قابل‌نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```


نمودار والد را برمی‌گرداند. فقط‌خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


دریافت یا تنظیم قابلیت نمایش نوارهای خطا. قابل‌خواندن/قابل‌نوشتن boolean.

**بازگشت:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


دریافت یا تنظیم قابلیت نمایش نوارهای خطا. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


اسلاید والد یک FillFormat را برمی‌گرداند. فقط‌خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


ارائه والد یک FillFormat را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)