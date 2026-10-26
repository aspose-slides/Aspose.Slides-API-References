---
title: NotesCommentsLayoutingOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌هایی را فراهم می‌کند که ظاهر چینش یادداشت‌ها و نظرات را در سند صادره کنترل می‌کند.
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

گزینه‌هایی را فراهم می‌کند که ظاهر چینش یادداشت‌ها و نظرات را در سند صادرشده کنترل می‌کند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | سازنده پیش‌فرض. |

## متدها

| متد | توضیح |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | دسترس‌پذیری نظراتی که نویسنده ندارند را دریافت یا تنظیم می‌کند. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | دسترس‌پذیری نظراتی که نویسنده ندارند را دریافت یا تنظیم می‌کند. |
| [getNotesPosition()](#getNotesPosition--) | موقعیت یادداشت‌ها در صفحه را دریافت یا تنظیم می‌کند. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | موقعیت یادداشت‌ها در صفحه را دریافت یا تنظیم می‌کند. |
| [getCommentsPosition()](#getCommentsPosition--) | موقعیت نظرات در صفحه را دریافت یا تنظیم می‌کند. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | موقعیت نظرات در صفحه را دریافت یا تنظیم می‌کند. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | رنگ ناحیه نظرات را دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | رنگ ناحیه نظرات را دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | عرض ناحیه خروجی نظر را بر حسب پیکسل دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | عرض ناحیه خروجی نظر را بر حسب پیکسل دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

سازنده پیش‌فرض.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

دسترس‌پذیری نظراتی که نویسنده ندارند را دریافت یا تنظیم می‌کند. اگر **true** باشد، نظرات نمایش داده می‌شوند. (فقط زمانی که نظرات نمایش داده شوند اعمال می‌شود).

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

دسترس‌پذیری نظراتی که نویسنده ندارند را دریافت یا تنظیم می‌کند. اگر **true** باشد، نظرات نمایش داده می‌شوند. (فقط زمانی که نظرات نمایش داده شوند اعمال می‌شود).

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

موقعیت یادداشت‌ها در صفحه را دریافت یا تنظیم می‌کند.

--------------------

مقدار پیش‌فرض **NotesPositions.None** است.

**بازگشت:**
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

موقعیت یادداشت‌ها در صفحه را دریافت یا تنظیم می‌کند.

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

موقعیت نظرات در صفحه را دریافت یا تنظیم می‌کند.

--------------------

مقدار پیش‌فرض **CommentsPositions.None** است.

**بازگشت:**
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

موقعیت نظرات در صفحه را دریافت یا تنظیم می‌کند.

--------------------

مقدار پیش‌فرض **CommentsPositions.None** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

رنگ ناحیه نظرات را دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود).

--------------------

مقدار پیش‌فرض **Color.SkyBlue** است.

**بازگشت:**
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

رنگ ناحیه نظرات را دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود).

--------------------

مقدار پیش‌فرض **Color.SkyBlue** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

عرض ناحیه خروجی نظر را بر حسب پیکسل دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود).

--------------------

حداقل و مقدار پیش‌فرض **150** است.

**بازگشت:**
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

عرض ناحیه خروجی نظر را بر حسب پیکسل دریافت یا تنظیم می‌کند (فقط زمانی که نظرات در سمت راست نمایش داده شوند اعمال می‌شود).

--------------------

حداقل و مقدار پیش‌فرض **150** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |