---
title: IMasterSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای جاوا
description: مدیری را نشان می‌دهد که رفتار جای‌دارهای پایین‌نویس، تاریخ-زمان، شماره صفحه اسلاید اصلی و تمام جای‌دارهای فرزند را نگه می‌دارد.
type: docs
url: /fa/com.aspose.slides/imasterslideheaderfootermanager/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

مدیری را نشان می‌دهد که رفتار جای‌دارهای پایین‌نویس اسلاید اصلی، تاریخ-زمان، شماره صفحه و تمام جای‌دارهای فرزند را نگه می‌دارد. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.
## متدها

| متد | توضیح |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


وضعیت قابل مشاهده‌ی جای‌دار پایین‌نویس اسلاید اصلی و تمام جای‌دارهای پایین‌نویس فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای پایین‌نویس را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


وضعیت قابل مشاهده‌ی جای‌دار شماره صفحه اسلاید اصلی و تمام جای‌دارهای شماره صفحه فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


وضعیت قابل مشاهده‌ی جای‌دار تاریخ-زمان اسلاید اصلی و تمام جای‌دارهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


متن را به جای‌دار پایین‌نویس اسلاید اصلی و تمام جای‌دارهای پایین‌نویس فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


متن را به جای‌دار تاریخ-زمان اسلاید اصلی و تمام جای‌دارهای تاریخ-زمان فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی است که جای‌دارها در اسلایدهای چیدمان وابسته و اسلایدهای وابسته قرار گرفته‌اند. اسلایدهای چیدمان وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |