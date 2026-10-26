---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مدیر را نمایندگی می‌کند که رفتار فوتر اسلاید طرح‌بندی، تاریخ-زمان، جای‌گیرهای شماره صفحه و تمام جای‌گیرهای فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/layoutslideheaderfootermanager/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

نمایش‌دهندهٔ مدیری است که رفتار فوتر اسلاید طرح‌بندی، تاریخ-زمان، جای‌گیرهای شماره صفحه و تمام جای‌گیرهای فرزند را در بر می‌گیرد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.
## متدها

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | قابلیت نمایش فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند را تغییر می‌دهد. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | قابلیت نمایش جای‌گیر شماره صفحه اسلاید طرح‌بندی و تمام جای‌گیرهای شماره صفحه فرزند را تغییر می‌دهد. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | قابلیت نمایش جای‌گیر تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گیرهای تاریخ-زمان فرزند را تغییر می‌دهد. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را به فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند اختصاص می‌دهد. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را به جای‌گیر تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گیرهای تاریخ-زمان فرزند اختصاص می‌دهد. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


قابلیت نمایش فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید مادر استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - فوترهای جای‌گیر را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


قابلیت نمایش جای‌گیر شماره صفحه اسلاید طرح‌بندی و تمام جای‌گیرهای شماره صفحه فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


قابلیت نمایش جای‌گیر تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گیرهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرهای تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


متن را به فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند اختصاص می‌دهد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


متن را به جای‌گیر تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گیرهای تاریخ-زمان فرزند اختصاص می‌دهد. جای‌گیرهای فرزند به این معنی‌اند که این جای‌گیرها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |