---
title: ILayoutSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای جاوا
description: مدیری را نشان می‌دهد که رفتار جای‌گیرهای پاورقی اسلاید چیدمان، تاریخ-زمان، شماره صفحه و تمام جای‌گیرهای فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

این مدیر رفتار جای‌گیرهای پاورقی اسلاید چیدمان، تاریخ-زمان، شماره صفحه و تمام جای‌گیرهای فرزند را در بر می‌گیرد. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید چیدمان استفاده می‌کنند و به آن وابسته هستند.
## متدها

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | وضعیت قابل مشاهده جای‌گیر پاورقی اسلاید چیدمان و تمام جای‌گیرهای پاورقی فرزند را تغییر می‌دهد. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | وضعیت قابل مشاهده جای‌گیر شماره صفحه اسلاید چیدمان و تمام جای‌گیرهای شماره صفحه فرزند را تغییر می‌دهد. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | وضعیت قابل مشاهده جای‌گیر تاریخ-زمان اسلاید چیدمان و تمام جای‌گیرهای تاریخ-زمان فرزند را تغییر می‌دهد. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را به جای‌گیر پاورقی اسلاید چیدمان و تمام جای‌گیرهای پاورقی فرزند تنظیم می‌کند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را به جای‌گیر تاریخ-زمان اسلاید چیدمان و تمام جای‌گیرهای تاریخ-زمان فرزند تنظیم می‌کند. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

وضعیت قابل مشاهده جای‌گیر پاورقی اسلاید چیدمان و تمام جای‌گیرهای پاورقی فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید مادر استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرهای پاورقی را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌سازد. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

وضعیت قابل مشاهده جای‌گیر شماره صفحه اسلاید چیدمان و تمام جای‌گیرهای شماره صفحه فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید چیدمان استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌سازد. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

وضعیت قابل مشاهده جای‌گیر تاریخ-زمان اسلاید چیدمان و تمام جای‌گیرهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید چیدمان استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرهای تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌سازد. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

متن را به جای‌گیر پاورقی اسلاید چیدمان و تمام جای‌گیرهای پاورقی فرزند تنظیم می‌کند. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید چیدمان استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که تنظیم می‌شود. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

متن را به جای‌گیر تاریخ-زمان اسلاید چیدمان و تمام جای‌گیرهای تاریخ-زمان فرزند تنظیم می‌کند. جای‌گیرهای فرزند به این معناست که جای‌گیرها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید چیدمان استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که تنظیم می‌شود. |