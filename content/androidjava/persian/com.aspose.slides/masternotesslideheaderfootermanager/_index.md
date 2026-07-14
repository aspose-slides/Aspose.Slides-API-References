---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: مدیری را نمایندگی می‌کند که رفتار فوتر اسلاید یادداشت‌های اصلی، تاریخ-زمان، شماره صفحه و تمام جای‌نگهدارهای فرزند را در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/masternotesslideheaderfootermanager/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

مدیری را نمایندگی می‌کند که رفتار فوتر اسلاید یادداشت‌های اصلی، تاریخ-زمان، صفحه‌شماره‌ جای‌نگهدارها و تمام جای‌نگهدارهای فرزند را در بر می‌گیرد. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.
## متدها

| متد | توضیح |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | قابلیت نمایش‌پذیری جای‌نگهدار سرعنوان اسلاید یادداشت‌های اصلی و تمام جای‌نگهدارهای سرعنوان فرزند را تغییر می‌دهد. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | متن را به جای‌نگهدار سرعنوان اسلاید یادداشت‌های اصلی و تمام جای‌نگهدارهای سرعنوان فرزند تنظیم می‌کند. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | قابلیت نمایش‌پذیری جای‌نگهدار پابرگ اسلاید اصلی و تمام جای‌نگهدارهای پابرگ فرزند را تغییر می‌دهد. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | قابلیت نمایش‌پذیری جای‌نگهدار شماره صفحه اسلاید اصلی و تمام جای‌نگهدارهای شماره صفحه فرزند را تغییر می‌دهد. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | قابلیت نمایش‌پذیری جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند را تغییر می‌دهد. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | متن را به جای‌نگهدار پابرگ اسلاید اصلی و تمام جای‌نگهدارهای پابرگ فرزند تنظیم می‌کند. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | متن را به جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند تنظیم می‌کند. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

قابلیت نمایش‌پذیری جای‌نگهدار سرعنوان اسلاید یادداشت‌های اصلی و تمام جای‌نگهدارهای سرعنوان فرزند را تغییر می‌دهد. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسل slid یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌نگهدارهای سرعنوان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را پنهان می‌سازد. |

### setHeaderAndChildHeadersText(java.lang.String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

متن را به جای‌نگهدار سرعنوان اسلاید یادداشت‌های اصلی و تمام جای‌نگهدارهای سرعنوان فرزند تنظیم می‌کند. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

قابلیت نمایش‌پذیری جای‌نگهدار پابرگ اسلاید اصلی و تمام جای‌نگهدارهای پابرگ فرزند را تغییر می‌دهد. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌نگهدارهای پابرگ را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را پنهان می‌سازد. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

قابلیت نمایش‌پذیری جای‌نگهدار شماره صفحه اسلاید اصلی و تمام جای‌نگهدارهای شماره صفحه فرزند را تغییر می‌دهد. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌نگهدارهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را پنهان می‌سازد. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

قابلیت نمایش‌پذیری جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌نگهدارهای تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را پنهان می‌سازد. |

### setFooterAndChildFootersText(java.lang.String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

متن را به جای‌نگهدار پابرگ اسلاید اصلی و تمام جای‌نگهدارهای پابرگ فرزند تنظیم می‌کند. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setDateTimeAndChildDateTimesText(java.lang.String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

متن را به جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند تنظیم می‌کند. جای‌نگهدارهای فرزند به این معنی‌اند که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |