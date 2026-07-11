---
title: OpenAICompatibleWebClient
second_title: مرجع API Aspose.Slides برای جاوا
description: یک پیاده‌سازی داخلی که به یک ارائه‌دهنده LLM سازگار با OpenAI در URL پایه مشخص‌شده متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/openaicompatiblewebclient/
---
**ارث‌برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

یک پیاده‌سازی داخلی [IAIWebClient](../../com.aspose.slides/iaiwebclient) که به یک فراهم‌کننده LLM سازگار با OpenAI در URL پایه مشخص‌شده متصل می‌شود.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از کلاینت وب سازگار با OpenAI ایجاد می‌کند. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از کلاینت وب سازگار با OpenAI ایجاد می‌کند که از یک HttpClient مدیریت‌شده به‌صورت خارجی استفاده می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | یک نمونه مکالمه ایجاد می‌کند. |
| [dispose()](#dispose--) | منابع استفاده شده توسط این نمونه را آزاد می‌کند. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

یک نمونه از کلاینت وب سازگار با OpenAI ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط فراهم‌کننده LLM. |
| apiKey | java.lang.String | کلید API (توکن). |
| baseUrl | java.lang.String | URL پایه LLM سازگار با OpenAI. |
```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

یک نمونه از کلاینت وب سازگار با OpenAI ایجاد می‌کند که از یک HttpClient مدیریت‌شده به‌صورت خارجی استفاده می‌کند. HttpClient ارائه‌شده توسط این نمونه آزاد نمی‌شود و مدیریت آن به عهدهٔ فراخوانی‌کننده می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط فراهم‌کننده LLM. |
| apiKey | java.lang.String | کلید API (توکن). |
| baseUrl | java.lang.String | URL پایه LLM سازگار با OpenAI. |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpClient که به‌صورت خارجی مدیریت می‌شود. |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

دستور چت را به مدل AI می‌فرستد با استفاده از یک نمونه HttpConnection ارائه‌شده و پیام پاسخ را به دستور داده شده برمی‌گرداند.

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

یک نمونه مکالمه ایجاد می‌کند. برخلاف فراخوانی‌های عادی AI، مکالمه‌ها کل زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده شده توسط این نمونه را آزاد می‌کند.