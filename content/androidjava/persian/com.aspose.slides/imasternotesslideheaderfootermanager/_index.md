---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: مدیری را نمایان می‌کند که رفتار فوتر اسلاید یادداشت اصلی، جای‌دارهای تاریخ-ساعت، شماره صفحه و تمام جای‌دارهای فرزند را نگه می‌دارد.
type: docs
url: /fa/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

مدیری را نمایان می‌کند که رفتار فوتر اسلاید یادداشت‌های اصلی، تاریخ-ساعت، شماره صفحه و تمام جای‌دارهای فرزند را نگه می‌دارد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

## متدها

| متد | توضیح |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Changes master notes slide header placeholder and all child header placeholders visibility. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Sets text to master notes slide header placeholder and all child header placeholders. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master notes slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master notes slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master notes slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master notes slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master notes slide date-time placeholder and all child date-time placeholders. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

قابلیت مشاهده جای‌دار سرصفحه اسلاید یادداشت اصلی و تمام جای‌دارهای سرصفحهٔ فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای سرصفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

متن را به جای‌دار سرصفحه اسلاید یادداشت اصلی و تمام جای‌دارهای سرصفحهٔ فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

قابلیت مشاهده جای‌دار فوتر اسلاید یادداشت اصلی و تمام جای‌دارهای فوترٔ فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای فوتر را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

قابلیت مشاهده جای‌دار شماره صفحه اسلاید یادداشت اصلی و تمام جای‌دارهای شماره صفحهٔ فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

قابلیت مشاهده جای‌دار تاریخ-ساعت اسلاید یادداشت اصلی و تمام جای‌دارهای تاریخ-ساعتٔ فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌دارهای تاریخ-ساعت را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را مخفی می‌کند. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

متن را به جای‌دار فوتر اسلاید یادداشت اصلی و تمام جای‌دارهای فوترٔ فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

متن را به جای‌دار تاریخ-ساعت اسلاید یادداشت اصلی و تمام جای‌دارهای تاریخ-ساعتٔ فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته هستند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |