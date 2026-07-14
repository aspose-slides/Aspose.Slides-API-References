---
title: DataLabelFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/datalabelformat/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

نمایانگر گزینه‌های قالب‌بندی برای DataLabel است.

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قابلیت خواندن/نوشتن boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قابلیت خواندن/نوشتن boolean. |
| [getNumberFormat()](#getNumberFormat--) | نمایانگر رشته فرمت برای شی DataLabels است. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | نمایانگر رشته فرمت برای شی DataLabels است. |
| [getFormat()](#getFormat--) | نمایانگر قالب برچسب داده است. |
| [getPosition()](#getPosition--) | نمایانگر موقعیت برچسب داده است. |
| [setPosition(int value)](#setPosition-int-) | نمایانگر موقعیت برچسب داده است. |
| [getShowLegendKey()](#getShowLegendKey--) | نمایانگر رفتار نمایش کلید افسانه برچسب داده در یک نمودار مشخص است. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | نمایانگر رفتار نمایش کلید افسانه برچسب داده در یک نمودار مشخص است. |
| [getShowValue()](#getShowValue--) | نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. |
| [getShowCategoryName()](#getShowCategoryName--) | نمایانگر رفتار نمایش نام دسته‌بندی برچسب داده در یک نمودار مشخص است. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | نمایانگر رفتار نمایش نام دسته‌بندی برچسب داده در یک نمودار مشخص است. |
| [getShowSeriesName()](#getShowSeriesName--) | مقدار Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | مقدار Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. |
| [getShowPercentage()](#getShowPercentage--) | نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. |
| [getShowBubbleSize()](#getShowBubbleSize--) | نمایانگر رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص است. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | نمایانگر رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص است. |
| [getShowLeaderLines()](#getShowLeaderLines--) | نمایانگر رفتار نمایش خطوط رهبری برچسب داده در یک نمودار مشخص است. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | نمایانگر رفتار نمایش خطوط رهبری برچسب داده در یک نمودار مشخص است. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | نمایانگر رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص است. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | نمایانگر رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص است. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | تعیین می‌کند که برچسب داده در یک نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | تعیین می‌کند که برچسب داده در یک نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود. |
| [getSeparator()](#getSeparator--) | یک Variant را که نشان‌دهنده جداکننده استفاده‌شده برای برچسب‌های داده در یک نمودار است، تنظیم یا برمی‌گرداند. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | یک Variant را که نشان‌دهنده جداکننده استفاده‌شده برای برچسب‌های داده در یک نمودار است، تنظیم یا برمی‌گرداند. |
| [getTextFormat()](#getTextFormat--) | قالب متن نمودار را برمی‌گرداند. |
| [getChart()](#getChart--) | نمودار را برمی‌گرداند. |

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

قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**بازگشت:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی IsNumberFormatLinkedToSource را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی IsNumberFormatLinkedToSource تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" باعث می‌شود تمام DataLabels.get_Item(i).isNumberFormatLinkedToSource() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

نمایانگر رشته فرمت برای شی DataLabels است. قابلیت خواندن/نوشتن String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. هنگام تنظیم این ویژگی با یک مقدار، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌شود (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**بازگشت:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

نمایانگر رشته فرمت برای شی DataLabels است. قابلیت خواندن/نوشتن String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. هنگام تنظیم این ویژگی با یک مقدار، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌شود (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" باعث می‌شود تمام DataLabels.get_Item(i).getNumberFormat() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

نمایانگر قالب برچسب داده است. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی قالب پیش‌فرض برای برچسب‌های داده جدید در مجموعه DataLabelCollection را نشان می‌دهد.

**بازگشت:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

نمایانگر موقعیت برچسب داده است. قابلیت خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. موقعیت برای اشیاء DataLabel را نشان می‌دهد. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**بازگشت:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

نمایانگر موقعیت برچسب داده است. قابلیت خواندن/نوشتن [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Position را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. موقعیت برای اشیاء DataLabel را نشان می‌دهد. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی Position تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" باعث می‌شود تمام DataLabels.get_Item(i).getPosition() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

نمایانگر رفتار نمایش کلید افسانه برچسب داده در یک نمودار مشخص است. اگر کلید افسانه برچسب داده قابل مشاهده باشد مقدار True است. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

نمایانگر رفتار نمایش کلید افسانه برچسب داده در یک نمودار مشخص است. اگر کلید افسانه برچسب داده قابل مشاهده باشد مقدار True است. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLegendKey را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLegendKey تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLegendKey() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار درصدی را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**بازگشت:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار درصدی را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowValue را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowValue تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowValue() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

نمایانگر رفتار نمایش نام دسته‌بندی برچسب داده در یک نمودار مشخص است. اگر True باشد نام دسته‌بندی برای برچسب‌های داده در نمودار نمایش داده می‌شود. اگر False باشد مخفی می‌شود. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**بازگشت:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

نمایانگر رفتار نمایش نام دسته‌بندی برچسب داده در یک نمودار مشخص است. اگر True باشد نام دسته‌بندی برای برچسب‌های داده در نمودار نمایش داده می‌شود. اگر False باشد مخفی می‌شود. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowCategoryName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowCategoryName() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. اگر True باشد نام سری نمایش داده می‌شود. اگر False باشد مخفی می‌شود. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**بازگشت:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. اگر True باشد نام سری نمایش داده می‌شود. اگر False باشد مخفی می‌شود. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowSeriesName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowSeriesName تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowSeriesName() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار درصدی را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**بازگشت:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

نمایانگر رفتار نمایش مقدار درصدی برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار درصدی را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowPercentage را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowPercentage تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowPercentage() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

نمایانگر رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار اندازه حباب را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**بازگشت:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

نمایانگر رفتار نمایش مقدار اندازه حباب برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار اندازه حباب را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowBubbleSize را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowBubbleSize تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowBubbleSize() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

نمایانگر رفتار نمایش خطوط رهبری برچسب داده در یک نمودار مشخص است. اگر True باشد خطوط رهبری را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

نمایانگر رفتار نمایش خطوط رهبری برچسب داده در یک نمودار مشخص است. اگر True باشد خطوط رهبری را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLeaderLines را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLeaderLines تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLeaderLines() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

نمایانگر رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار سلول را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

نمایانگر رفتار نمایش مقدار سلول برچسب داده در یک نمودار مشخص است. اگر True باشد مقدار سلول را نمایش می‌دهد. اگر False باشد مخفی می‌کند. قابلیت خواندن/نوشتن boolean.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelValueFromCell را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLabelValueFromCell تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelValueFromCell() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

تعیین می‌کند که برچسب داده در یک نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**بازگشت:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

تعیین می‌کند که برچسب داده در یک نمودار مشخص به‌عنوان فراخوانی داده یا به‌عنوان برچسب داده نمایش داده شود.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" باعث می‌شود تمام DataLabels.get_Item(i).getShowLabelAsDataCallout() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

یک Variant را که نشان‌دهنده جداکننده استفاده‌شده برای برچسب‌های داده در یک نمودار است، تنظیم یا برمی‌گرداند. قابلیت خواندن/نوشتن String.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).

**بازگشت:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

یک Variant را که نشان‌دهنده جداکننده استفاده‌شده برای برچسب‌های داده در یک نمودار است، تنظیم یا برمی‌گرداند. قابلیت خواندن/نوشتن String.

--------------------

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی Separator را برای برچسب‌های داده جدید در مجموعه DataLabelCollection برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی Separator تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" باعث می‌شود تمام DataLabels.get_Item(i).getSeparator() برابر با val باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن نمودار را برمی‌گرداند. فقط خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار را برمی‌گرداند. فقط خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart)