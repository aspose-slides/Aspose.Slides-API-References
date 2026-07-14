---
title: IErrorBarsFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نوارهای خطای سری نمودار را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ierrorbarsformat/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

نمایش نوارهای خطای مجموعه داده‌های نمودار. مقادیر سفارشی ErrorBars در IChartDataPointCollection (در ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) قرار دارند.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```

دست یا تنظیم نوع نوارهای خطا. خواندن/نوشتن [ErrorBarType](../../com.aspose.slides/errorbartype).

**بازگشت:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

دست یا تنظیم نوع نوارهای خطا. خواندن/نوشتن [ErrorBarType](../../com.aspose.slides/errorbartype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

نمایش روش‌های ممکن برای تعیین طول نوارهای خطا. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) نقطه داده خاص در مجموعه DataPoints سری را استفاده کنید. خواندن/نوشتن [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**بازگشت:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

نمایش روش‌های ممکن برای تعیین طول نوارهای خطا. در صورت استفاده از نوع مقدار سفارشی برای تعیین مقدار، ویژگی [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) نقطه داده خاص در مجموعه DataPoints سری را استفاده کنید. خواندن/نوشتن [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

مشخص می‌کند که انتهای نوارهای خطا نمی‌باشد. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

مشخص می‌کند که انتهای نوارهای خطا نمی‌باشد. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

دست یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. خواندن/نوشتن float.

**بازگشت:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

دست یا تنظیم مقدار که با انواع مقدار Fixed, Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

نمایش قالب نوارهای خطا. خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

نمایش قالب نوارهای خطا. خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

دست یا تنظیم قابلیت نمایش نوارهای خطا. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

دست یا تنظیم قابلیت نمایش نوارهای خطا. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |