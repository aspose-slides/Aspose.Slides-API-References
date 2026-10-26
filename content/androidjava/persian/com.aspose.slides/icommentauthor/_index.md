---
title: ICommentAuthor
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نماینده یک نویسندهٔ نظرات.
type: docs
url: /fa/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

نماینده یک نویسندهٔ نظرات.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | برمی‌گرداند یا تنظیم می‌کند نام نویسنده. |
| [setName(String value)](#setName-java.lang.String-) | برمی‌گرداند یا تنظیم می‌کند نام نویسنده. |
| [getInitials()](#getInitials--) | برمی‌گرداند یا تنظیم می‌کند حروف اولیه نویسنده. |
| [setInitials(String value)](#setInitials-java.lang.String-) | برمی‌گرداند یا تنظیم می‌کند حروف اولیه نویسنده. |
| [getComments()](#getComments--) | مجموعهٔ نظرات ساخته‌شده توسط این نویسنده را برمی‌گرداند. |
| [remove()](#remove--) | نویسنده را از مجموعهٔ والد حذف می‌کند. |
### getName() {#getName--}
```
public abstract String getName()
```

برمی‌گرداند یا تنظیم می‌کند نام نویسنده. خواندنی/نوشتنی String.

**بازگشت:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

برمی‌گرداند یا تنظیم می‌کند نام نویسنده. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

برمی‌گرداند یا تنظیم می‌کند حروف اولیه نویسنده. خواندنی/نوشتنی String.

**بازگشت:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

برمی‌گرداند یا تنظیم می‌کند حروف اولیه نویسنده. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

مجموعهٔ نظرات ساخته‌شده توسط این نویسنده را برمی‌گرداند. فقط خواندنی [ICommentCollection](../../com.aspose.slides/icommentcollection).

**بازگشت:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

نویسنده را از مجموعهٔ والد حذف می‌کند.