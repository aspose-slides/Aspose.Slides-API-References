---
title: IDataLabelFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/idatalabelformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.

## متدها

| Method | Description |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | خواندن/نوشتن بولی. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | خواندن/نوشتن بولی. |
| [getNumberFormat()](#getNumberFormat--) | رشته قالب برای شیء DataLabels را نشان می‌دهد. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | رشته قالب برای شیء DataLabels را نشان می‌دهد. |
| [getFormat()](#getFormat--) | قالب برچسب داده را نشان می‌دهد. |
| [getPosition()](#getPosition--) | موقعیت برچسب داده را نشان می‌دهد. |
| [setPosition(int value)](#setPosition-int-) | موقعیت برچسب داده را نشان می‌دهد. |
| [getShowLegendKey()](#getShowLegendKey--) | رفتار نمایش کلید افسانه‌ای برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | رفتار نمایش کلید افسانه‌ای برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowValue()](#getShowValue--) | رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowCategoryName()](#getShowCategoryName--) | رفتار نمایش نام دسته برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | رفتار نمایش نام دسته برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowSeriesName()](#getShowSeriesName--) | یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. |
| [getShowPercentage()](#getShowPercentage--) | رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowBubbleSize()](#getShowBubbleSize--) | رفتار نمایش مقدار اندازه حباب برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | رفتار نمایش مقدار اندازه حباب برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowLeaderLines()](#getShowLeaderLines--) | رفتار نمایش خطوط رهبری برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | رفتار نمایش خطوط رهبری برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | تعیین می‌کند که برچسب دادهٔ نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | تعیین می‌کند که برچسب دادهٔ نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | رفتار نمایش مقدار سلول برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | رفتار نمایش مقدار سلول برچسب داده برای نمودار مشخص را نشان می‌دهد. |
| [getSeparator()](#getSeparator--) | یک Variant را تنظیم یا برمی‌گرداند که جداکنندهٔ استفاده‌شده برای برچسب‌های داده روی نمودار را نشان می‌دهد. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | یک Variant را تنظیم یا برمی‌گرداند که جداکنندهٔ استفاده‌شده برای برچسب‌های داده روی نمودار را نشان می‌دهد. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);» باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**بازگشت:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);» باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

رشته قالب برای شیء DataLabels را نشان می‌دهد. خواندن/نوشتن رشته.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. هنگامی که این ویژگی با مقدار تنظیم می‌شود، آن مقدار نیز برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌شود (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);» باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**بازگشت:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

رشته قالب برای شیء DataLabels را نشان می‌دهد. خواندن/نوشتن رشته.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. هنگامی که این ویژگی با مقدار تنظیم می‌شود، آن مقدار نیز برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌شود (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);» باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب برچسب داده را نشان می‌دهد. فقط‌خواندنی [IFormat](../../com.aspose.slides/iformat).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی قالب پیش‌فرض برای برچسب‌های داده جدید در مجموعه DataLabelCollection را نمایان می‌کند.

**بازگشت:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت برچسب داده را نشان می‌دهد. خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. موقعیت برای اشیاء DataLabel را نشان می‌دهد. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setPosition(val)» باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**بازگشت:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت برچسب داده را نشان می‌دهد. خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. موقعیت برای اشیاء DataLabel را نشان می‌دهد. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setPosition(val)» باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

رفتار نمایش کلید افسانه‌ای برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر کلید افسانه‌ای برچسب داده قابل رؤیت باشد، true است. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

رفتار نمایش کلید افسانه‌ای برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر کلید افسانه‌ای برچسب داده قابل رؤیت باشد، true است. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار درصد نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowValue(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**بازگشت:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار درصد نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowValue(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

رفتار نمایش نام دسته برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر نام دسته نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**بازگشت:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

رفتار نمایش نام دسته برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر نام دسته نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. اگر نام سری نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**بازگشت:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده روی نمودار را نشان دهد. اگر نام سری نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار درصد نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**بازگشت:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

رفتار نمایش مقدار درصد برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار درصد نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

رفتار نمایش مقدار اندازه حباب برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار اندازه حباب نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**بازگشت:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

رفتار نمایش مقدار اندازه حباب برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار اندازه حباب نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

رفتار نمایش خطوط رهبری برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر خطوط رهبری نمایش داده شوند، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

رفتار نمایش خطوط رهبری برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر خطوط رهبری نمایش داده شوند، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

تعیین می‌کند که برچسب دادهٔ نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

تعیین می‌کند که برچسب دادهٔ نمودار مشخص به صورت فراخوانی داده یا به صورت برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

رفتار نمایش مقدار سلول برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار سلول نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

رفتار نمایش مقدار سلول برچسب داده برای نمودار مشخص را نشان می‌دهد. اگر مقدار سلول نمایش داده شود، true؛ برای پنهان‌کردن false. خواندن/نوشتن بولی.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

یک Variant را تنظیم یا برمی‌گرداند که جداکنندهٔ استفاده‌شده برای برچسب‌های داده روی نمودار را نشان می‌دهد. خواندن/نوشتن رشته.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).

**بازگشت:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

یک Variant را تنظیم یا برمی‌گرداند که جداکنندهٔ استفاده‌شده برای برچسب‌های داده روی نمودار را نشان می‌دهد. خواندن/نوشتن رشته.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، این مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (به عنوان مثال «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |