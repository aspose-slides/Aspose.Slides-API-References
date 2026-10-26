---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: رابط کلاینت وب هوش مصنوعی.
type: docs
url: /fa/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

رابط کلاینت وب AI. این رابط امکان تعویض مدل‌های زبان AI مختلف را فراهم می‌کند. کلاس‌هایی که این رابط را پیاده‌سازی می‌کنند، باید همراه با SlidesAIAgent استفاده شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | دستور چت را به مدل AI با استفاده از یک نمونه HttpConnection ارائه شده ارسال می‌کند و پیام پاسخ را به دستور داده‌شده بر می‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونه گفت‌وگو ایجاد می‌کند. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

دستور چت را به مدل AI با استفاده از یک نمونه HttpConnection ارائه شده ارسال می‌کند و پیام پاسخ را به دستور داده‌شده بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام برای پردازش توسط مدل AI. |

**بازگشت:**
java.lang.String - پیامی که توسط مدل AI در پاسخ به دستور داده‌شده تولید می‌شود.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

یک نمونه گفت‌وگو ایجاد می‌کند. برخلاف فراخوانی‌های معمول AI، گفت‌وگوها کل زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک [IAIConversation](../../com.aspose.slides/iaiconversation) نمونه.