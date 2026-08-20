---
title: OpenAICompatibleWebClient
second_title: مرجع API Aspose.Slides للغة Java
description: تنفيذ مدمج يتصل بموفر LLM متوافق مع OpenAI عبر عنوان URL أساسي محدد.
type: docs
url: /ar/com.aspose.slides/openaicompatiblewebclient/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بموفر LLM متوافق مع OpenAI على عنوان URL أساسي محدد.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثيلاً لعميل ويب متوافق مع OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثيلاً لعميل ويب متوافق مع OpenAI يستخدم HttpURLConnection مدارًا خارجيًا. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpURLConnection مدارًا خارجيًا ويعيد رسالة الاستجابة للتعليمات المعطاة. |
| [createConversation()](#createConversation--) | ينشئ مثيلاً لمحادثة. |
| [dispose()](#dispose--) | يطلق الموارد المستخدمة بواسطة هذا المثيل. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

ينشئ مثيلاً لعميل ويب متوافق مع OpenAI.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من موفر LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي للـ LLM المتوافق مع OpenAI. |
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

ينشئ مثيلاً لعميل ويب متوافق مع OpenAI يستخدم HttpURLConnection مدارًا خارجيًا. لا يقوم هذا المثيل بتفريغ HttpURLConnection المزود ويظل مملوكًا للمتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من موفر LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي للـ LLM المتوافق مع OpenAI. |
| httpClient | java.net.HttpURLConnection | مثيل HttpURLConnection مدارًا خارجيًا. |
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

يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpURLConnection مدارًا خارجيًا ويعيد رسالة الاستجابة للتعليمات المعطاة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليمات أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي. |

**القيمة المرجعة:**
java.lang.String - الرسالة التي تم توليدها بواسطة نموذج الذكاء الاصطناعي استجابةً للتعليمات المعطاة.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثيلاً لمحادثة. على عكس المكالمات العادية للذكاء الاصطناعي، تحتفظ المحادثات بالسياق بالكامل.

**القيمة المرجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

يطلق الموارد المستخدمة بواسطة هذا المثيل.