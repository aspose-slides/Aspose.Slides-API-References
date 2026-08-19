---
title: OpenAICompatibleWebClient
second_title: مرجع API Aspose.Slides برای Java
description: یک پیاده‌سازی توکار که به ارائه‌گر LLM سازگار با OpenAI در URL پایه مشخصی متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

یک پیاده‌سازی توکار [IAIWebClient](../../com.aspose.slides/iaiwebclient) که به ارائه‌گر LLM سازگار با OpenAI در URL پایه مشخصی متصل می‌شود.

## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه از وب‌کلاینت سازگار با OpenAI ایجاد می‌کند. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از وب‌کلاینت سازگار با OpenAI که از HttpURLConnection مدیریت‌شده خارجی استفاده می‌کند ایجاد می‌کند. |

## متدها

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | یک دستور چت را به مدل هوش مصنوعی می‌فرستد با استفاده از نمونه HttpURLConnection مدیریت‌شده خارجی و پیام پاسخ را به دستور داده‌شده برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونه گفت‌وگو ایجاد می‌کند. |
| [dispose()](#dispose--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

یک نمونه از وب‌کلاینت سازگار با OpenAI ایجاد می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط ارائه‌گر LLM. |
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

یک نمونه از وب‌کلاینت سازگار با OpenAI که از HttpURLConnection مدیریت‌شده خارجی استفاده می‌کند ایجاد می‌کند. HttpURLConnection ارائه‌شده توسط این نمونه حذف نمی‌شود و مالکیت آن برای فراخواننده باقی می‌ماند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نام مدل پشتیبانی‌شده توسط ارائه‌گر LLM. |
| apiKey | java.lang.String | کلید API (توکن). |
| baseUrl | java.lang.String | URL پایه LLM سازگار با OpenAI. |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpURLConnection مدیریت‌شده خارجی. |
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

یک دستور چت را به مدل هوش مصنوعی می‌فرستد با استفاده از نمونه HttpURLConnection مدیریت‌شده خارجی و پیام پاسخ را به دستور داده‌شده برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیامی که توسط مدل هوش مصنوعی پردازش می‌شود. |

**Returns:**
java.lang.String - پیام تولید شده توسط مدل هوش مصنوعی در پاسخ به دستور داده‌شده.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه گفت‌وگو ایجاد می‌کند. برخلاف فراخوانی‌های معمولی هوش مصنوعی، گفت‌وگوها تمام متن را حفظ می‌کنند.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.