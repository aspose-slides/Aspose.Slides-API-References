---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشی را توصیف می‌کند که رفتار تمام placeholderهای پاورقی، تاریخ-زمان و شماره صفحه ارائه را در خود دارد.
type: docs
url: /fa/com.aspose.slides/ipresentationheaderfootermanager/
---
**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

نمایشی را توصیف می‌کند که رفتار تمام نگهدارنده‌های پاورقی، تاریخ-زمان و شماره صفحه ارائه را در خود دارد.
## متدها

| متد | توضیح |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides and slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides and slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides and slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides and slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides and slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

تغییر وضعیت قابل مشاهده بودن همهٔ placeholderهای هدر، شامل notes master، notes slides و handout master.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک placeholder هدر را قابل مشاهده می‌کند، در غیر این صورت آن را پنهان می‌کند. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

تغییر وضعیت قابل مشاهده بودن همهٔ placeholderهای پاورقی، شامل master slides، layout slides و slides.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک placeholder پاورقی را قابل مشاهده می‌کند، در غیر این صورت آن را پنهان می‌کند. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

تغییر وضعیت قابل مشاهده بودن همهٔ placeholderهای شماره صفحه، شامل master slides، layout slides و slides.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک placeholder شماره صفحه را قابل مشاهده می‌کند، در غیر این صورت آن را پنهان می‌کند. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

تغییر وضعیت قابل مشاهده بودن همهٔ placeholderهای تاریخ-زمان، شامل master slides، layout slides و slides.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک placeholder تاریخ-زمان را قابل مشاهده می‌کند، در غیر این صورت آن را پنهان می‌کند. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

تنظیم متن برای همهٔ placeholderهای هدر، شامل notes master، notes slides و handout master.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

تنظیم متن برای همهٔ placeholderهای پاورقی، شامل master slides، layout slides و slides.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

تنظیم متن برای همهٔ placeholderهای تاریخ-زمان، شامل master slides، layout slides و slides.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

تغییر وضعیت قابل مشاهده بودن placeholderهای پاورقی، تاریخ-زمان و شماره صفحه برای همهٔ اسلایدهای عنوان و برای اولین اسلاید چیدمان. اسلایدهای عنوان — اسلایدهایی که بر پایهٔ اولین اسلاید چیدمان ساخته شده‌اند (صرف‌نظر از نوع این اولین چیدمان).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - placeholderها را قابل مشاهده می‌کند، در غیر این صورت آن‌ها را پنهان می‌کند. |