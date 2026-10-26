---
title: IAIConversation
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک نمونه مکالمه است.
type: docs
url: /fa/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

نمایانگر یک نمونه مکالمه است. برخلاف تماس‌های AI معمولی، مکالمات کل زمینه را حفظ می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | پیام درخواست مکالمه را شامل کل زمینه ارسال می‌کند و پاسخ را باز می‌گرداند. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

پیام درخواست مکالمه را شامل کل زمینه ارسال می‌کند و پاسخ را باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام مورد پردازش توسط مدل AI. |

**بازگشت:**
java.lang.String - پیامی که توسط مدل AI در پاسخ به دستور داده شده در زمینه مکالمه تولید می‌شود.