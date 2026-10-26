---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: تنفيذ مدمج يتصل بمزود LLM متوافق مع OpenAI عبر عنوان URL أساسي محدد.
type: docs
url: /ar/com.aspose.slides/openaicompatiblewebclient/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بمزود LLM متوافق مع OpenAI عبر عنوان URL أساسي محدد.

## المُنشئات

| البناء | الوصف |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثلاً لعميل ويب متوافق مع OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل ويب متوافق مع OpenAI يستخدم HttpURLConnection مُداراً خارجياً. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | يُرسِل توجيه دردشة إلى نموذج AI باستخدام مثيل HttpURLConnection المُدار خارجياً ويعيد رسالة الاستجابة للتوجيه المحدد. |
| [createConversation()](#createConversation--) | ينشئ مثلاً لمحاورة. |
| [dispose()](#dispose--) | يحرر الموارد المستخدمة بواسطة هذا المثيل. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

ينشئ مثلاً لعميل ويب متوافق مع OpenAI.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من مزود LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي لـ LLM المتوافق مع OpenAI. |

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

ينشئ مثلاً لعميل ويب متوافق مع OpenAI يستخدم HttpURLConnection مُداراً خارجياً. لا يتم تحرير HttpURLConnection المُقدم من قبل هذه المثيلة ويظل مملوكاً للمتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من مزود LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي لـ LLM المتوافق مع OpenAI. |
| httpClient | java.net.HttpURLConnection | مثيل HttpURLConnection مُدار خارجياً. |

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

يُرسِل توجيه دردشة إلى نموذج AI باستخدام مثيل HttpURLConnection مُدار خارجياً ويعيد رسالة الاستجابة للتوجيه المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التوجيه أو الرسالة التي يعالجها نموذج AI. |

**القيمة المرجعة:**
java.lang.String - الرسالة التي يولدها نموذج AI استجابةً للتوجيه المحدد.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثلاً لمحاورة. على عكس مكالمات AI العادية، تحتفظ المحاورات بالسياق كاملًا.

**القيمة المرجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثلاً من [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

يحرر الموارد المستخدمة بواسطة هذا المثيل.