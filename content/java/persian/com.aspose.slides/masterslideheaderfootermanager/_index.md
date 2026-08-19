---
title: MasterSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای Java
description: نمایش‌دهنده مدیری است که رفتار فوتر اسلاید اصلی، تاریخ-زمان، جای‌گذاری شماره صفحه و تمام جای‌گذاری‌های فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/masterslideheaderfootermanager/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)  
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

نماینده مدیری است که رفتار فوتر اسلاید اصلی، تاریخ-زمان، جای‌گذاری شماره صفحه و تمام جای‌گذاری‌های فرزند را در برمی‌گیرد. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.
## متدها

| متد | توضیح |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | تغییر وضعیت دیده شدن فوتر اسلاید اصلی و تمام فوترهای فرزند. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | تغییر وضعیت دیده شدن شماره صفحه اسلاید اصلی و تمام شماره صفحه‌های فرزند. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | تغییر وضعیت دیده شدن تاریخ-زمان اسلاید اصلی و تمام تاریخ-زمان‌های فرزند. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | تنظیم متن برای فوتر اسلاید اصلی و تمام فوترهای فرزند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | تنظیم متن برای تاریخ-زمان اسلاید اصلی و تمام تاریخ-زمان‌های فرزند. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

تغییر وضعیت دیده شدن فوتر اسلاید اصلی و تمام فوترهای فرزند. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - placeholderهای فوتر را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

تغییر وضعیت دیده شدن شماره صفحه اسلاید اصلی و تمام شماره صفحه‌های فرزند. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - placeholderهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

تغییر وضعیت دیده شدن تاریخ-زمان اسلاید اصلی و تمام تاریخ-زمان‌های فرزند. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - placeholderهای تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

تنظیم متن برای فوتر اسلاید اصلی و تمام فوترهای فرزند. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

تنظیم متن برای تاریخ-زمان اسلاید اصلی و تمام تاریخ-زمان‌های فرزند. جای‌گذاری‌های فرزند به این معنی است که جای‌گذاری‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته نگهداری می‌شوند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |