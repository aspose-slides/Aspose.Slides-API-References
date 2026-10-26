---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /fa/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

نماد یک نمونه مکالمه است. بر خلاف تماس‌های معمولی هوش مصنوعی، مکالمات تمام زمینه را حفظ می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | پیغام درخواست مکالمه را به‌همراه تمام زمینه ارسال می‌کند و پاسخ را برمی‌گرداند. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


پیام درخواست مکالمه را به‌همراه تمام زمینه ارسال می‌کند و پاسخ را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام‌ای که باید توسط مدل هوش مصنوعی پردازش شود. |

**بازگشت:**
java.lang.String - پیام تولید شده توسط مدل هوش مصنوعی به‌عنوان پاسخ به دستور داده‌شده در زمینه مکالمه.