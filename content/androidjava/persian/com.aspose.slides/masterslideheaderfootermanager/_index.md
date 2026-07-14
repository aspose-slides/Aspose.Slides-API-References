---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نماینده‌ای است که رفتار فوتر اسلاید اصلی، مکان‌دارهای تاریخ-زمان، مکان‌دارهای شماره-صفحه و تمام مکان‌دارهای فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/masterslideheaderfootermanager/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

نمایندهٔ مدیری است که رفتار فوتر اسلاید اصلی، مکان‌دار تاریخ-زمان، شماره-صفحه و تمام مکان‌دارهای فرزند را در بر می‌گیرد. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.
## متدها

| متد | توضیح |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | وضعیت نمایش مکان‌دار فوتر اسلاید اصلی و تمام مکان‌دارهای فوتر فرزند را تغییر می‌دهد. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | وضعیت نمایش مکان‌دار شماره-صفحه اسلاید اصلی و تمام مکان‌دارهای شماره-صفحه فرزند را تغییر می‌دهد. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | وضعیت نمایش مکان‌دار تاریخ-زمان اسلاید اصلی و تمام مکان‌دارهای تاریخ-زمان فرزند را تغییر می‌دهد. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را در فوتر اسلاید اصلی و تمام فوترهای فرزند تنظیم می‌کند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را در مکان‌دار تاریخ-زمان اسلاید اصلی و تمام مکان‌دارهای تاریخ-زمان فرزند تنظیم می‌کند. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

وضعیت نمایش مکان‌دار فوتر اسلاید اصلی و تمام فوترهای فرزند را تغییر می‌دهد. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - فوترها را قابل نمایش می‌کند، در غیر این صورت آن‌ها را پنهان می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

وضعیت نمایش مکان‌دار شماره-صفحه اسلاید اصلی و تمام شماره-صفحه‌های فرزند را تغییر می‌دهد. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - شماره-صفحه‌ها را قابل نمایش می‌کند، در غیر این صورت آن‌ها را پنهان می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

وضعیت نمایش مکان‌دار تاریخ-زمان اسلاید اصلی و تمام مکان‌دارهای تاریخ-زمان فرزند را تغییر می‌دهد. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - مکان‌دارهای تاریخ-زمان را قابل نمایش می‌کند، در غیر این صورت آن‌ها را پنهان می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

متن را در فوتر اسلاید اصلی و تمام فوترهای فرزند تنظیم می‌کند. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

متن را در مکان‌دار تاریخ-زمان اسلاید اصلی و تمام مکان‌دارهای تاریخ-زمان فرزند تنظیم می‌کند. مکان‌دارهای فرزند به این معنا هستند که مکان‌دارها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |