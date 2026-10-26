---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /fa/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

رابط کاربری وب AI. این رابط امکان جایگزینی مدل‌های مختلف زبان AI را فراهم می‌کند. کلاس‌هایی که این رابط را پیاده‌سازی می‌کنند، باید همراه با SlidesAIAgent مورد استفاده قرار گیرند.

## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | یک دستور چت را به مدل AI با استفاده از یک نمونه HttpConnection فراهم شده می‌فرستد و پیام پاسخ را به دستور داده شده برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونه گفتگویی ایجاد می‌کند. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

یک دستور چت را به مدل AI با استفاده از یک نمونه HttpConnection فراهم شده می‌فرستد و پیام پاسخ را به دستور داده شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیامی که توسط مدل AI پردازش می‌شود. |

**بازگشت:**
java.lang.String - پیامی که توسط مدل AI در پاسخ به دستور داده شده تولید می‌شود.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

یک نمونه گفتگویی ایجاد می‌کند. برخلاف فراخوانی‌های معمول AI، گفتگوها تمام زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).