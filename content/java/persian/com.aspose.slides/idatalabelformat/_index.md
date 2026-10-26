---
title: IDataLabelFormat
second_title: راهنمای API Aspose.Slides برای جاوا
description: نمایش گزینه‌های قالب‌بندی برای DataLabel.
type: docs
url: /fa/com.aspose.slides/idatalabelformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

نمایش گزینه‌های قالب‌بندی برای DataLabel.
## متدها

| متد | توضیح |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قابل خواندن/نوشتن boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قابل خواندن/نوشتن boolean. |
| [getNumberFormat()](#getNumberFormat--) | نمایش رشته قالب برای شی DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | نمایش رشته قالب برای شی DataLabels. |
| [getFormat()](#getFormat--) | نمایش قالب برچسب داده. |
| [getPosition()](#getPosition--) | نمایش موقعیت برچسب داده. |
| [setPosition(int value)](#setPosition-int-) | نمایش موقعیت برچسب داده. |
| [getShowLegendKey()](#getShowLegendKey--) | نمایش رفتار نمایش کلید افسانه برچسب داده برای یک نمودار مشخص. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | نمایش رفتار نمایش کلید افسانه برچسب داده برای یک نمودار مشخص. |
| [getShowValue()](#getShowValue--) | نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [getShowCategoryName()](#getShowCategoryName--) | نمایش رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | نمایش رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. |
| [getShowSeriesName()](#getShowSeriesName--) | بازگرداندن یا تنظیم یک Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | بازگرداندن یا تنظیم یک Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار. |
| [getShowPercentage()](#getShowPercentage--) | نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. |
| [getShowBubbleSize()](#getShowBubbleSize--) | نمایش رفتار نمایش مقدار اندازه حباب برچسب داده برای یک نمودار مشخص. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | نمایش رفتار نمایش مقدار اندازه حباب برچسب داده برای یک نمودار مشخص. |
| [getShowLeaderLines()](#getShowLeaderLines--) | نمایش رفتار نمایش خطوط رهبری برچسب داده برای یک نمودار مشخص. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | نمایش رفتار نمایش خطوط رهبری برچسب داده برای یک نمودار مشخص. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | تعیین می‌کند که برچسب داده یک نمودار مشخص به عنوان فراخوانی داده یا به عنوان برچسب داده نمایش داده شود. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | تعیین می‌کند که برچسب داده یک نمودار مشخص به عنوان فراخوانی داده یا به عنوان برچسب داده نمایش داده شود. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | نمایش رفتار نمایش مقدار سلول برچسب داده برای یک نمودار مشخص. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | نمایش رفتار نمایش مقدار سلول برچسب داده برای یک نمودار مشخص. |
| [getSeparator()](#getSeparator--) | تنظیم یا بازگرداندن Variant نمایانگر جداکننده استفاده شده برای برچسب‌های داده در یک نمودار. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | تنظیم یا بازگرداندن Variant نمایانگر جداکننده استفاده شده برای برچسب‌های داده در یک نمودار. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی IsNumberFormatLinkedToSource برای تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" باعث می‌شود همه DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**بازگشت:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی IsNumberFormatLinkedToSource برای تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" باعث می‌شود همه DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

نمایش رشته قالب برای شی DataLabels. قابل خواندن/نوشتن String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقدار تنظیم شود، آن مقدار نیز برای ویژگی NumberFormat برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌شود (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود همه DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**بازگشت:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

نمایش رشته قالب برای شی DataLabels. قابل خواندن/نوشتن String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقدار تنظیم شود, آن مقدار نیز برای ویژگی NumberFormat برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌شود (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود همه DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

نمایش قالب برچسب داده. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی قالب پیش‌فرض برای برچسب‌های داده جدید در مجموعه DataLabelCollection را نشان می‌دهد.

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

نمایش موقعیت برچسب داده. قابل خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. نمایش موقعیت برای اشیاء DataLabel. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Position برای تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setPosition(val)" باعث می‌شود همه DataLabels.get_Item(i).getPosition() برابر با val باشد).

**بازگشت:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

نمایش موقعیت برچسب داده. قابل خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. نمایش موقعیت برای اشیاء DataLabel. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Position برای تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setPosition(val)" باعث می‌شود همه DataLabels.get_Item(i).getPosition() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

نمایش رفتار نمایش کلید افسانه برچسب داده برای یک نمودار مشخص. اگر کلید افسانه برچسب داده قابل مشاهده باشد true است. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLegendKey برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود همه DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**بازگشت:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

نمایش رفتار نمایش کلید افسانه برچسب داده برای یک نمودار مشخص. اگر کلید افسانه برچسب داده قابل مشاهده باشد true است. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLegendKey برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود همه DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. اگر true باشد مقدار درصد را نمایش می‌دهد. اگر false باشد مخفی می‌کند. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowValue برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود همه DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**بازگشت:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

نمایش رفتار نمایش مقدار درصد برچسب داده برای یک نمودار مشخص. اگر true باشد مقدار درصد را نمایش می‌دهد. اگر false باشد مخفی می‌کند. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowValue برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود همه DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

نمایش رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. اگر true باشد نام دسته را برای برچسب‌های داده در یک نمودار نمایش می‌دهد. اگر false باشد مخفی می‌کند. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شی DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowCategoryName برای تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" باعث می‌شود همه DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**بازگشت:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

نمایش رفتار نمایش نام دسته برچسب داده برای یک نمودار مشخص. اگر true باشد نام دسته را برای برچسب‌های داده در یک نمودار نمایش می‌دهد. اگر false باشد مخفی می‌کند. قابل خواندن/نوشتن boolean.

--------------------
اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

یک Boolean را بر می‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**بازگشت:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

یک Boolean را بر می‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

نمایش مقدار درصد برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**بازگشت:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

نمایش مقدار درصد برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

نمایش مقدار اندازه حباب برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**بازگشت:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

نمایش مقدار اندازه حباب برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

نمایش خطوط راهنمای برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True خطوط راهنما را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**بازگشت:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

نمایش خطوط راهنمای برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True خطوط راهنما را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

تعیین می‌کند که برچسب دادهٔ یک نمودار مشخص به عنوان فراخوان داده یا به عنوان برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**بازگشت:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

تعیین می‌کند که برچسب دادهٔ یک نمودار مشخص به عنوان فراخوان داده یا به عنوان برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

نمایش مقدار سلول برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار سلول را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**بازگشت:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

نمایش مقدار سلول برچسب دادهٔ یک نمودار مشخص را توصیف می‌کند. True مقدار سلول را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

یک Variant را تنظیم یا بر می‌گرداند که جداکننده مورد استفاده برای برچسب‌های داده روی نمودار را نشان می‌دهد. خواندنی/قابل نوشتن String.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).

**بازگشت:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

یک Variant را تنظیم یا بر می‌گرداند که جداکننده مورد استفاده برای برچسب‌های داده روی نمودار را نشان می‌دهد. خواندنی/قابل نوشتن String.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌گیرد (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |