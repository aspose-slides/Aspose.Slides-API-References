---
title: OpenAIWebClient
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: کلاینت وب سبک وزن OpenAI داخلی
type: docs
url: /fa/com.aspose.slides/openaiwebclient/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

کلاینت وب سبک وزن OpenAI داخلی
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از OpenAI Web client ایجاد می‌کند. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از OpenAI Web client ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | یک دستور chat را به مدل AI ارسال می‌کند با استفاده از یک نمونه مدیریت‌شده خارجی و پیام پاسخ را برای دستور داده‌شده برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونه گفتگو ایجاد می‌کند. |
| [close()](#close--) | منابع مورد استفاده توسط این نمونه را آزاد می‌کند. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

یک نمونه از OpenAI Web client ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | مدل زبانی OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | کلید API OpenAI |
| organizationId | java.lang.String | شناسه سازمان (اختیاری) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

یک نمونه از OpenAI Web client ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | مدل زبانی OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | کلید API OpenAI |
| organizationId | java.lang.String | شناسه سازمان (اختیاری) |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpURLConnection مدیریت‌شده خارجی. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

یک دستور chat را به مدل AI ارسال می‌کند با استفاده از یک نمونه مدیریت‌شده خارجی و پیام پاسخ را برای دستور داده‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام برای پردازش توسط مدل AI |

**بازگشت:**
java.lang.String - پیام تولید شده توسط مدل AI در پاسخ به دستور داده‌شده.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه گفتگو ایجاد می‌کند. بر خلاف فراخوانی‌های معمولی AI، گفتگوها کل زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

منابع مورد استفاده توسط این نمونه را آزاد می‌کند.