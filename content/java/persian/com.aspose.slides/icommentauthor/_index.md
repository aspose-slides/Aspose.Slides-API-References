---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: نمایانگر نویسنده‌ای از نظرات.
type: docs
url: /fa/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

نمایانگر نویسنده‌ای از نظرات.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | مقدار یا تنظیم نام نویسنده. |
| [setName(String value)](#setName-java.lang.String-) | مقدار یا تنظیم نام نویسنده. |
| [getInitials()](#getInitials--) | مقدار یا تنظیم حروف اولیه نویسنده. |
| [setInitials(String value)](#setInitials-java.lang.String-) | مقدار یا تنظیم حروف اولیه نویسنده. |
| [getComments()](#getComments--) | مجموعه نظراتی که توسط این نویسنده ایجاد شده است را برمی‌گرداند. |
| [remove()](#remove--) | نویسنده را از مجموعه والد حذف می‌کند. |
### getName() {#getName--}
```
public abstract String getName()
```

مقدار یا تنظیم نام نویسنده. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

مقدار یا تنظیم نام نویسنده. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

مقدار یا تنظیم حروف اولیه نویسنده. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

مقدار یا تنظیم حروف اولیه نویسنده. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

مجموعه نظراتی که توسط این نویسنده ایجاد شده است را برمی‌گرداند. فقط-خواندنی [ICommentCollection](../../com.aspose.slides/icommentcollection).

**بازگرداندن:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

نویسنده را از مجموعه والد حذف می‌کند.