---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده‌ای که رفتار فوتر اسلاید اصلی، جای‌گیرنده تاریخ-زمان، شماره صفحه و تمام جای‌گیرنده‌های فرزند را نگه می‌دارد.
type: docs
url: /fa/com.aspose.slides/imasterslideheaderfootermanager/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

نمایندهٔ مدیری است که رفتار فوتر اسلاید اصلی، جای‌گیرندهٔ تاریخ-زمان، شمارهٔ صفحه و تمام جای‌گیرنده‌های فرزند را نگه می‌دارد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.
## متدها

| متد | توضیح |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | وضعیت نمایش‌پذیری جای‌گیرندهٔ فوتر اسلاید اصلی و تمام جای‌گیرنده‌های فوتر فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | وضعیت نمایش‌پذیری جای‌گیرندهٔ شمارهٔ صفحه اسلاید اصلی و تمام جای‌گیرنده‌های شمارهٔ صفحه فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | وضعیت نمایش‌پذیری جای‌گیرندهٔ تاریخ-زمان اسلاید اصلی و تمام جای‌گیرنده‌های تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را به فوتر اسلاید اصلی و تمام فوترهای فرزند تنظیم می‌کند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را به جای‌گیرندهٔ تاریخ-زمان اسلاید اصلی و تمام جای‌گیرنده‌های تاریخ-زمان فرزند تنظیم می‌کند. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


وضعیت نمایش‌پذیری جای‌گیرندهٔ فوتر اسلاید اصلی و تمام جای‌گیرنده‌های فوتر فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرنده‌های فوتر را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


وضعیت نمایش‌پذیری جای‌گیرندهٔ شمارهٔ صفحه اسلاید اصلی و تمام جای‌گیرنده‌های شمارهٔ صفحه فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرنده‌های شمارهٔ صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


وضعیت نمایش‌پذیری جای‌گیرندهٔ تاریخ-زمان اسلاید اصلی و تمام جای‌گیرنده‌های تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌گیرنده‌های تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


متن را به فوتر اسلاید اصلی و تمام فوترهای فرزند تنظیم می‌کند. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


متن را به جای‌گیرندهٔ تاریخ-زمان اسلاید اصلی و تمام جای‌گیرنده‌های تاریخ-زمان فرزند تنظیم می‌کند. جای‌گیرنده‌های فرزند به این معنی هستند که جای‌گیرنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای تنظیم. |