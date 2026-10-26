---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مدیری را نشان می‌دهد که رفتار placeholders را نگه می‌دارد، از جمله placeholder سرصفحه برای تمام انواع اسلایدهای handout و notes.
type: docs
url: /fa/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**ارث-بری:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

مدیری را نشان می‌دهد که رفتار placeholders را نگه می‌دارد، از جمله placeholder سرصفحه برای تمام انواع اسلایدهای handout و notes.
## متدها

| متد | توضیح |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | مقدار را برمی‌گرداند که نشان می‌دهد یک placeholder سرصفحه موجود است. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | قابلیت مشاهده placeholder سرصفحه اسلاید را تغییر می‌دهد. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | متن را برای placeholder سرصفحه اسلاید تنظیم می‌کند. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

مقدار را برمی‌گرداند که نشان می‌دهد یک placeholder سرصفحه موجود است. قابل خواندن به صورت boolean.

**بازگشت:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

قابلیت مشاهده placeholder سرصفحه اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - placeholder سرصفحه را قابل مشاهده می‌کند، در غیر این صورت آن را مخفی می‌نماید. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

متن را برای placeholder سرصفحه اسلاید تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |