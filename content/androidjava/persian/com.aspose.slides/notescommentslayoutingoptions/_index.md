---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که ظاهر چیدمان یادداشت‌ها و نظرات را در سند صادر شده کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/notescommentslayoutingoptions/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)  
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

گزینه‌هایی را فراهم می‌کند که ظاهر چیدمان یادداشت‌ها و نظرات را در سند صادرشده کنترل می‌کند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | سازنده پیش‌فرض. |

## متدها

| متد | توضیح |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | دریافت یا تنظیم قابلیت مشاهده نظراتی که نویسنده‌ای ندارند. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | دریافت یا تنظیم قابلیت مشاهده نظراتی که نویسنده‌ای ندارند. |
| [getNotesPosition()](#getNotesPosition--) | دریافت یا تنظیم موقعیت یادداشت‌ها در صفحه. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | دریافت یا تنظیم موقعیت یادداشت‌ها در صفحه. |
| [getCommentsPosition()](#getCommentsPosition--) | دریافت یا تنظیم موقعیت نظرات در صفحه. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | دریافت یا تنظیم موقعیت نظرات در صفحه. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | دریافت یا تنظیم رنگ ناحیه نظرات (فقط در صورتی که نظرات در سمت راست نمایش داده شوند). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | دریافت یا تنظیم رنگ ناحیه نظرات (فقط در صورتی که نظرات در سمت راست نمایش داده شوند). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | دریافت یا تنظیم عرض ناحیه خروجی نظر بر حسب پیکسل (فقط در صورتی که نظرات در سمت راست نمایش داده شوند). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | دریافت یا تنظیم عرض ناحیه خروجی نظر بر حسب پیکسل (فقط در صورتی که نظرات در سمت راست نمایش داده شوند). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

سازنده پیش‌فرض.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

دریافت یا تنظیم قابلیت مشاهده نظراتی که نویسنده‌ای ندارند. اگر مقدار **true** باشد، نظرات نمایش داده می‌شوند. (فقط در صورتی که نظرات نمایش داده شوند).

--------------------

مقدار پیش‌فرض **false** است.

**بازگشت:**  
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

دریافت یا تنظیم قابلیت مشاهده نظراتی که نویسنده‌ای ندارند. اگر مقدار **true** باشد، نظرات نمایش داده می‌شوند. (فقط در صورتی که نظرات نمایش داده شوند).

--------------------

مقدار پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

دریافت یا تنظیم موقعیت یادداشت‌ها در صفحه.

--------------------

مقدار پیش‌فرض **NotesPositions.None** است.

**بازگشت:**  
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

دریافت یا تنظیم موقعیت یادداشت‌ها در صفحه.

--------------------

مقدار پیش‌فرض **NotesPositions.None** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

دریافت یا تنظیم موقعیت نظرات در صفحه.

--------------------

مقدار پیش‌فرض **CommentsPositions.None** است.

**بازگشت:**  
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

دریافت یا تنظیم موقعیت نظرات در صفحه.

--------------------

مقدار پیش‌فرض **CommentsPositions.None** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

دریافت یا تنظیم رنگ ناحیه نظرات (فقط در صورتی که نظرات در سمت راست نمایش داده شوند).

--------------------

مقدار پیش‌فرض **SkyBlue** است.

**بازگشت:**  
java.lang.Integer

### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

دریافت یا تنظیم رنگ ناحیه نظرات (فقط در صورتی که نظرات در سمت راست نمایش داده شوند).

--------------------

مقدار پیش‌فرض **SkyBlue** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

دریافت یا تنظیم عرض ناحیه خروجی نظر بر حسب پیکسل (فقط در صورتی که نظرات در سمت راست نمایش داده شوند).

--------------------

کمینه و مقدار پیش‌فرض **150** است.

**بازگشت:**  
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

دریافت یا تنظیم عرض ناحیه خروجی نظر بر حسب پیکسل (فقط در صورتی که نظرات در سمت راست نمایش داده شوند).

--------------------

کمینه و مقدار پیش‌فرض **150** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |