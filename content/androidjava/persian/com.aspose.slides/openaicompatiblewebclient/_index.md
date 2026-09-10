---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک پیاده‌سازی داخلی که به یک ارائه‌دهنده LLM سازگار با OpenAI در URL پایه مشخص متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IIAWebClient, System.IDisposable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به یک ارائه‌دهنده LLM سازگار با OpenAI در URL پایه مشخص متصل می‌شود.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از مشتری وب سازگار با OpenAI ایجاد می‌کند. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از مشتری وب سازگار با OpenAI که از HttpURLConnection مدیریت‌شده به‌صورت خارجی استفاده می‌کند، ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | دستور گفت‌وگو را به مدل هوش مصنوعی با استفاده از یک نمونه HttpURLConnection مدیریت‌شده به‌صورت خارجی ارسال می‌کند و پیام پاسخ به دستور داده‌شده را برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونه گفتگو ایجاد می‌کند. برخلاف تماس‌های هوش مصنوعی معمولی، گفتگوها تمام زمینه را نگه می‌دارند. |
| [dispose()](#dispose--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

یک نمونه از مشتری وب سازگار با OpenAI ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط ارائه‌دهنده LLM. |
| apiKey | java.lang.String | کلید API (توکن). |
| baseUrl | java.lang.String | URL پایه LLM سازگار با OpenAI. |

```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

یک نمونه از مشتری وب سازگار با OpenAI که از HttpURLConnection مدیریت‌شده به‌صورت خارجی استفاده می‌کند، ایجاد می‌کند. HttpURLConnection ارائه‌شده توسط این نمونه آزاد نمی‌شود و متعلق به فراخواننده باقی می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط ارائه‌دهنده LLM. |
| apiKey | java.lang.String | کلید API (توکن). |
| baseUrl | java.lang.String | URL پایه LLM سازگار با OpenAI. |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpURLConnection مدیریت‌شده به‌صورت خارجی. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

دستور گفت‌وگو را به مدل هوش مصنوعی با استفاده از یک نمونه HttpURLConnection مدیریت‌شده به‌صورت خارجی ارسال می‌کند و پیام پاسخ به دستور داده‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیامی که باید توسط مدل هوش مصنوعی پردازش شود. |

**بازگشت:**
java.lang.String - پیام تولید شده توسط مدل هوش مصنوعی در پاسخ به دستور داده‌شده.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه گفتگو ایجاد می‌کند. برخلاف تماس‌های هوش مصنوعی معمولی، گفتگوها تمام زمینه را نگه می‌دارند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.