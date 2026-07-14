---
title: IBaseSlideHeaderFooterManager
second_title: مرجع API جاوا برای Aspose.Slides در اندروید
description: نمایندهٔ مدیری است که رفتار جای‌نگهدارهای پاورقی، تاریخ-زمان و شماره صفحه را برای تمام انواع اسلایدها نگه می‌دارد.
type: docs
url: /fa/com.aspose.slides/ibaseslideheaderfootermanager/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

نمایندهٔ مدیری است که رفتار جای‌نگهدارهای پاورقی، تاریخ-زمان و شماره صفحه را برای تمام انواع اسلایدها نگه می‌دارد.
## متدها

| متد | توضیح |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | مقدار را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار پاورقی وجود دارد. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | مقدار را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار شماره صفحه وجود دارد. |
| [isDateTimeVisible()](#isDateTimeVisible--) | مقدار را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار تاریخ-زمان وجود دارد. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | قابلیت نمایش جای‌نگهدار پاورقی اسلاید را تغییر می‌دهد. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | قابلیت نمایش جای‌نگهدار شماره صفحه اسلاید را تغییر می‌دهد. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | قابلیت نمایش جای‌نگهدار تاریخ-زمان اسلاید را تغییر می‌دهد. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | متن را در جای‌نگهدار پاورقی اسلاید تنظیم می‌کند. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | متن را در جای‌نگهدار تاریخ-زمان اسلاید تنظیم می‌کند. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار پاورقی وجود دارد. خواندنی boolean.

**بازمی‌گرداند:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار شماره صفحه وجود دارد. خواندنی boolean.

**بازمی‌گرداند:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار تاریخ-زمان وجود دارد. خواندنی boolean.

**بازمی‌گرداند:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

قابلیت نمایش جای‌نگهدار پاورقی اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک جای‌نگهدار پاورقی را قابل‌مشاهده می‌کند، در غیر این صورت آن را مخفی می‌کند. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

قابلیت نمایش جای‌نگهدار شماره صفحه اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک جای‌نگهدار شماره صفحه را قابل‌مشاهده می‌کند، در غیر این صورت آن را مخفی می‌کند. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

قابلیت نمایش جای‌نگهدار تاریخ-زمان اسلاید را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| isVisible | boolean | true - یک جای‌نگهدار تاریخ-زمان را قابل‌مشاهده می‌کند، در غیر این صورت آن را مخفی می‌کند. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

متن را در جای‌نگهدار پاورقی اسلاید تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

متن را در جای‌نگهدار تاریخ-زمان اسلاید تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید تنظیم شود. |