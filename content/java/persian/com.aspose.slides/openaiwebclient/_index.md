---
title: OpenAIWebClient
second_title: Aspose.Slides برای مستندات API جاوا
description: یک پیاده‌سازی داخلی که به API OpenAI متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/openaiwebclient/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به API OpenAI متصل می‌شود.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از وب‌کلاینت OpenAI ایجاد می‌کند. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از وب‌کلاینت OpenAI ایجاد می‌کند که از HttpClient مدیریت‌شده خارجی استفاده می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | یک نمونه از گفتگو ایجاد می‌کند. |
| [close()](#close--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

یک نمونه از وب‌کلاینت OpenAI ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | مدل زبان OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | کلید API OpenAI. |
| organizationId | java.lang.String | شناسه سازمان (اختیاری). |
```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

یک نمونه از وب‌کلاینت OpenAI ایجاد می‌کند که از HttpClient مدیریت‌شده خارجی استفاده می‌کند. HttpClient ارائه‌شده توسط این نمونه حذف نمی‌شود و مالکیت آن برای فراخواننده می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | مدل زبان OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | کلید API OpenAI |
| organizationId | java.lang.String | شناسه سازمان (اختیاری) |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpClient که به‌صورت خارجی مدیریت می‌شود |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

یک دستور چت را به مدل هوش مصنوعی ارسال می‌کند با استفاده از یک نمونه HttpConnection فراهم‌شده و پیام پاسخ را برای دستور داده‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String |  |
**بازگشت:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه از گفتگو ایجاد می‌کند. برخلاف تماس‌های معمولی هوش مصنوعی، گفتگوها تمام زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).

### close() {#close--}
```
public final void close()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.