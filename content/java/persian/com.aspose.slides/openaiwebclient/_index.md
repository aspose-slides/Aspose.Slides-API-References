---
title: OpenAIWebClient
second_title: مستندات API Aspose.Slides برای جاوا
description: یک پیاده‌سازی داخلی که به API OpenAI متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/openaiwebclient/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به API OpenAI متصل می‌شود.

## سازندگان

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از سرویس‌گیرنده وب OpenAI ایجاد می‌کند. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از سرویس‌گیرنده وب OpenAI ایجاد می‌کند که از HttpClient مدیریت‌شده به‌صورت خارجی استفاده می‌کند. |

## متدها

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | یک نمونه مکالمه ایجاد می‌کند. |
| [close()](#close--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

یک نمونه از سرویس‌گیرنده وب OpenAI ایجاد می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | مدل زبانی OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
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

یک نمونه از سرویس‌گیرنده وب OpenAI ایجاد می‌کند که از HttpClient مدیریت‌شده به‌صورت خارجی استفاده می‌کند. HttpClient ارائه‌شده توسط این نمونه آزاد (dispose) نمی‌شود و مالکیت آن برای فراخواننده باقی می‌ماند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | مدل زبانی OpenAI. مقادیر ممکن: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | کلید API OpenAI |
| organizationId | java.lang.String | شناسه سازمان (اختیاری) |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpClient مدیریت‌شده به‌صورت خارجی |

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

یک دستور چت را به مدل هوش مصنوعی با استفاده از یک نمونه HttpConnection ارائه‌شده می‌فرستد و پیام پاسخ را به دستور داده‌شده برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**بازگشت:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه مکالمه ایجاد می‌کند. برخلاف تماس‌های معمولی هوش مصنوعی، مکالمات تمام زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).

### close() {#close--}
```
public final void close()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.