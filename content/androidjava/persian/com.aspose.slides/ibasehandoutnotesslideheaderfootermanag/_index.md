---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده‌ای که رفتار جای‌نگهدارها را شامل جای‌نگهدار سرصفحه برای تمام انواع اسلایدهای جزئیات و یادداشت‌ها نگه می‌دارد.
type: docs
url: /fa/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

نماینده‌ی مدیری است که رفتار جای‌نگهدارها را دربرمی‌گیرد، از جمله جای‌نگهدار عنوان سرصفحه برای تمام انواع اسلایدهای جزئیات و یادداشت‌ها.

--------------------

نام اصلی رابط "IBaseHandoutNotesSlideHeaderFooterManager" به "IBaseHandoutNotesSlideHeaderFooterManag" برای سازگاری COM کوتاه شده است (طول نام نوع نباید بیش از ۳۹ باشد).
## متدها

| متد | توضیح |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | مقدار را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار عنوان سرصفحه وجود دارد. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | قابلیت مشاهده‌پذیری جای‌نگهدار عنوان سرصفحه اسلاید را تغییر می‌دهد. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | متن را به جای‌نگهدار عنوان سرصفحه اسلاید تنظیم می‌کند. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار عنوان سرصفحه وجود دارد. خواندن بولی.

**بازگرداندن:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

قابلیت مشاهده‌پذیری جای‌نگهدار عنوان سرصفحه اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک جای‌نگهدار عنوان سرصفحه را قابل مشاهده می‌کند، در غیر این صورت آن را مخفی می‌کند. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

متن را به جای‌نگهدار عنوان سرصفحه اسلاید تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |