---
title: DataLabelFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش گزینه‌های قالب‌بندی برای DataLabel.
type: docs
url: /fa/com.aspose.slides/datalabelformat/
---
**ارث‌برداری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

نمایش‌دهندهٔ گزینه‌های قالب‌بندی برای DataLabel.
## متدها

| متد | شرح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | خواندنی/نوشتنی boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | خواندنی/نوشتنی boolean. |
| [getNumberFormat()](#getNumberFormat--) | نمایش‌دهندهٔ رشتهٔ فرمت برای شیء DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | نمایش‌دهندهٔ رشتهٔ فرمت برای شیء DataLabels. |
| [getFormat()](#getFormat--) | نمایش‌دهندهٔ قالب برچسب داده. |
| [getPosition()](#getPosition--) | نمایش‌دهندهٔ موقعیت برچسب داده. |
| [setPosition(int value)](#setPosition-int-) | نمایش‌دهندهٔ موقعیت برچسب داده. |
| [getShowLegendKey()](#getShowLegendKey--) | نمایش‌دهندهٔ رفتار نمایش کلید افسانهٔ برچسب داده برای یک نمودار مشخص. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | نمایش‌دهندهٔ رفتار نمایش کلید افسانهٔ برچسب داده برای یک نمودار مشخص. |
| [getShowValue()](#getShowValue--) | نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [getShowCategoryName()](#getShowCategoryName--) | نمایش‌دهندهٔ رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | نمایش‌دهندهٔ رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. |
| [getShowSeriesName()](#getShowSeriesName--) | بازگرداندن یا تنظیم یک Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | بازگرداندن یا تنظیم یک Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار. |
| [getShowPercentage()](#getShowPercentage--) | نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [getShowBubbleSize()](#getShowBubbleSize--) | نمایش‌دهندهٔ رفتار نمایش مقدار اندازه حباب برچسب داده برای یک نمودار مشخص. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | نمایش‌دهندهٔ رفتار نمایش مقدار اندازه حباب برچسب داده برای یک نمودار مشخص. |
| [getShowLeaderLines()](#getShowLeaderLines--) | نمایش‌دهندهٔ رفتار نمایش خطوط راهنما برای برچسب داده در یک نمودار مشخص. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | نمایش‌دهندهٔ رفتار نمایش خطوط راهنما برای برچسب داده در یک نمودار مشخص. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | نمایش‌دهندهٔ رفتار نمایش مقدار سلول برچسب داده برای یک نمودار مشخص. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | نمایش‌دهندهٔ رفتار نمایش مقدار سلول برچسب داده برای یک نمودار مشخص. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | تعیین می‌کند که برچسب دادهٔ نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | تعیین می‌کند که برچسب دادهٔ نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود. |
| [getSeparator()](#getSeparator--) | تنظیم یا بازگرداندن یک Variant که جداکنندهٔ استفاده‌شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | تنظیم یا بازگرداندن یک Variant که جداکنندهٔ استفاده‌شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد. |
| [getTextFormat()](#getTextFormat--) | بازگرداندن فرمت متن نمودار. |
| [getChart()](#getChart--) | بازگرداندن نمودار. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**  
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**بازگشت:**  
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

نمایش‌دهندهٔ رشتهٔ فرمت برای شیء DataLabels. خواندنی/نوشتنی String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقدار تنظیم شود، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌شود (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**بازگشت:**  
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

نمایش‌دهندهٔ رشتهٔ فرمت برای شیء DataLabels. خواندنی/نوشتنی String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقدار تنظیم شود، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌شود (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

نمایش‌دهندهٔ قالب برچسب داده. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی قالب پیش‌فرض برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection را نشان می‌دهد.

**بازگشت:**  
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

نمایش‌دهندهٔ موقعیت برچسب داده. خواندنی/نوشتنی [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. نمایش موقعیت برای اشیاء DataLabel. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setPosition(val);" باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**بازگشت:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

نمایش‌دهندهٔ موقعیت برچسب داده. خواندنی/نوشتنی [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. نمایش موقعیت برای اشیاء DataLabel. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setPosition(val);" باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

نمایش‌دهندهٔ رفتار نمایش کلید افسانهٔ برچسب داده برای یک نمودار مشخص. True اگر کلید افسانهٔ برچسب داده قابل مشاهده باشد. خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**بازگشت:**  
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

نمایش‌دهندهٔ رفتار نمایش کلید افسانهٔ برچسب داده برای یک نمودار مشخص. True اگر کلید افسانهٔ برچسب داده قابل مشاهده باشد. خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**بازگشت:**  
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

نمایش‌دهندهٔ رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

نمایش‌دهندهٔ رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. True برای نمایش نام دسته برای برچسب‌های داده روی نمودار. False برای مخفی کردن. خواندنی/نوشتنی boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌گذاری ویژگی ShowCategoryName را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به‌عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**بازگشت:**  
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

نمایش‌دهندهٔ رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. True برای نمایش نام دسته برای برچسب‌های داده روی نمودار. False برای مخفی کردن. خواندنی/نوشتنی boolean.

--------------------
اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowCategoryName() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

یک Boolean را باز می‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowSeriesName() برابر val باشد).

**بازگشت:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

یک Boolean را باز می‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowSeriesName() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

رفتار نمایش مقدار درصد برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowPercentage() برابر val باشد).

**بازگشت:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

رفتار نمایش مقدار درصد برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowPercentage() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowBubbleSize() برابر val باشد).

**بازگشت:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowBubbleSize() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

رفتار نمایش خطوط راهنمای برچسب داده در یک نمودار مشخص را نشان می‌دهد. True خطوط راهنما را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLeaderLines() برابر val باشد).

**بازگشت:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

رفتار نمایش خطوط راهنمای برچسب داده در یک نمودار مشخص را نشان می‌دهد. True خطوط راهنما را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLeaderLines() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار سلول را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLabelValueFromCell() برابر val باشد).

**بازگشت:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص را نشان می‌دهد. True مقدار سلول را نمایش می‌دهد. False برای مخفی کردن. بولی خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLabelValueFromCell() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

تعیین می‌کند که برچسب دادهٔ یک نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر val باشد).

**بازگشت:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

تعیین می‌کند که برچسب دادهٔ یک نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

یک Variant که جداکننده استفاده شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد تنظیم یا باز می‌گرداند. String خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getSeparator() برابر val باشد).

**بازگشت:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

یک Variant که جداکننده استفاده شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد تنظیم یا باز می‌گرداند. String خواندنی/نوشتنی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های دادهٔ جدید در مجموعه DataLabelCollection باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همان مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" باعث می‌شود که همهٔ DataLabels.get_Item(i).getSeparator() برابر val باشد).
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)