---
title: IErrorBarsFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: نوارهای خطا را برای سری نمودار نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ierrorbarsformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

نوارهای خطا را برای سری نمودار نمایش می‌دهد. مقادیر سفارشی ErrorBars در IChartDataPointCollection (در ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) قرار دارند.
## متدها

| Method | Description |
| --- | --- |
| [getType()](#getType--) | دریافت یا تنظیم نوع نوارهای خطا. |
| [setType(int value)](#setType-int-) | دریافت یا تنظیم نوع نوارهای خطا. |
| [getValueType()](#getValueType--) | روش‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. |
| [setValueType(int value)](#setValueType-int-) | روش‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. |
| [hasEndCap()](#hasEndCap--) | مشخص می‌کند که سرپوش در نوارهای خطا رسم نمی‌شود. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | مشخص می‌کند که سرپوش در نوارهای خطا رسم نمی‌شود. |
| [getValue()](#getValue--) | دریافت یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [setValue(float value)](#setValue-float-) | دریافت یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. |
| [getFormat()](#getFormat--) | قالب نوارهای خطا را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | قالب نوارهای خطا را نشان می‌دهد. |
| [isVisible()](#isVisible--) | دریافت یا تنظیم نمایان بودن نوارهای خطا. |
| [setVisible(boolean value)](#setVisible-boolean-) | دریافت یا تنظیم نمایان بودن نوارهای خطا. |
### getType() {#getType--}
```
public abstract int getType()
```

دریافت یا تنظیم نوع نوارهای خطا. خواندنی/نوشتنی [ErrorBarType](../../com.aspose.slides/errorbartype).

**برگشت:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

دریافت یا تنظیم نوع نوارهای خطا. خواندنی/نوشتنی [ErrorBarType](../../com.aspose.slides/errorbartype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

روش‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، از ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) نقطه دادهٔ خاص در مجموعه DataPoints سری استفاده کنید. خواندنی/نوشتنی [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**برگشت:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

روش‌های ممکن برای تعیین طول نوارهای خطا را نشان می‌دهد. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، از ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) نقطه دادهٔ خاص در مجموعه DataPoints سری استفاده کنید. خواندنی/نوشتنی [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

مشخص می‌کند که سرپوش در نوارهای خطا رسم نمی‌شود. خواندنی/نوشتنی boolean.

**برگشت:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

مشخص می‌کند که سرپوش در نوارهای خطا رسم نمی‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

دریافت یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. خواندنی/نوشتنی float.

**برگشت:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

دریافت یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. خواندنی/نوشتنی float.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب نوارهای خطا را نشان می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**برگشت:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

قالب نوارهای خطا را نشان می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

دریافت یا تنظیم نمایان بودن نوارهای خطا. خواندنی/نوشتنی boolean.

**برگشت:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

دریافت یا تنظیم نمایان بودن نوارهای خطا. خواندنی/نوشتنی boolean.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |