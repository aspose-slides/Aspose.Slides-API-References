---
title: ILayoutSlideHeaderFooterManager
second_title: مرجع API جاوا Aspose.Slides برای Android
description: نمایشی است که رفتار فوتر اسلاید قالب، جای‌گزین‌های تاریخ-زمان، شماره صفحه و تمام جای‌گزین‌های فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

نمایش‌دهنده‌ی مدیری است که رفتار فوتر اسلاید قالب، جای‌گزین تاریخ-زمان، جای‌گزین شماره صفحه و تمام جای‌گزین‌های فرزند را در بر می‌گیرد. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید قالب استفاده می‌کنند و به آن وابسته‌اند.

## متدها

| متد | توضیح |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | قابلیت نمایش فوتر اسلاید قالب و تمام فوترهای فرزند را تغییر می‌دهد. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | قابلیت نمایش شماره صفحه اسلاید قالب و تمام شماره صفحه‌های فرزند را تغییر می‌دهد. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | قابلیت نمایش جای‌گزین تاریخ-زمان اسلاید قالب و تمام جای‌گزین‌های تاریخ-زمان فرزند را تغییر می‌دهد. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را برای فوتر اسلاید قالب و تمام فوترهای فرزند تنظیم می‌کند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را برای جای‌گزین تاریخ-زمان اسلاید قالب و تمام جای‌گزین‌های تاریخ-زمان فرزند تنظیم می‌کند. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

قابلیت نمایش فوتر اسلاید قالب و تمام فوترهای فرزند را تغییر می‌دهد. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - فوترهای جای‌گزین را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

قابلیت نمایش شماره صفحه اسلاید قالب و تمام شماره صفحه‌های فرزند را تغییر می‌دهد. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید قالب استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - شماره‌صفحه‌های جای‌گزین را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

قابلیت نمایش جای‌گزین تاریخ-زمان اسلاید قالب و تمام جای‌گزین‌های تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید قالب استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گزین‌های تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

متن را برای فوتر اسلاید قالب و تمام فوترهای فرزند تنظیم می‌کند. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید قالب استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

متن را برای جای‌گزین تاریخ-زمان اسلاید قالب و تمام جای‌گزین‌های تاریخ-زمان فرزند تنظیم می‌کند. جای‌گزین‌های فرزند به این معنی هستند که جای‌گزین‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید قالب استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |