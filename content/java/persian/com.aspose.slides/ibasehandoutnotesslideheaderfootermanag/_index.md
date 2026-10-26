---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ مدیری است که رفتار جای‌نگهدارها را نگه می‌دارد، از جمله جای‌نگهدار سرصفحه برای تمام انواع اسلایدهای جزوات و یادداشت‌ها.
type: docs
url: /fa/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

نماینده مدیر است که رفتار جای‌نگهدارها را نگه می‌دارد، شامل جای‌نگهدار سرصفحه برای تمام انواع اسلایدهای جزوات و یادداشت‌ها.

--------------------

Original interface name "IBaseHandoutNotesSlideHeaderFooterManager" is trancuted to "IBaseHandoutNotesSlideHeaderFooterManag" for COM compatibility (type name length must be not more than 39).

## روش‌ها

| روش | توضیح |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار سرصفحه موجود است. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | وضعیت نمایش جای‌نگهدار سرصفحه اسلاید را تغییر می‌دهد. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | متنی را به جای‌نگهدار سرصفحه اسلاید تنظیم می‌کند. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار سرصفحه موجود است. خواندن boolean.

**بازمی‌گرداند:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

وضعیت نمایش جای‌نگهدار سرصفحه اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - جای‌نگهدار سرصفحه را قابل مشاهده می‌کند، در غیر این صورت آن را مخفی می‌کند. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

متنی را به جای‌نگهدار سرصفحه اسلاید تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |