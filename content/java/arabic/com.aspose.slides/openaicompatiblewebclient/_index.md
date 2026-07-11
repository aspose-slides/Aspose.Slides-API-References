---
title: OpenAICompatibleWebClient
second_title: مرجع API Aspose.Slides للـ Java
description: تنفيذ مدمج يتصل بموفر LLM متوافق مع OpenAI عبر عنوان URL أساسي محدد.
type: docs
url: /ar/com.aspose.slides/openaicompatiblewebclient/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بموفر LLM متوافق مع OpenAI عبر عنوان URL أساسي محدد.

## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثلاً لعميل ويب متوافق مع OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل ويب متوافق مع OpenAI يستخدم HttpClient مدارً خارجياً. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | ينشئ مثلاً لمحادثة. |
| [dispose()](#dispose--) | يحرر الموارد المستخدمة بواسطة هذا المثيل. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

ينشئ مثلاً لعميل ويب متوافق مع OpenAI.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من موفر LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي للـ LLM المتوافق مع OpenAI. |
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

ينشئ مثلاً لعميل ويب متوافق مع OpenAI يستخدم HttpClient مدارً خارجياً. لا يتم إتلاف HttpClient المقدم بواسطة هذا المثيل ويظل مملوكاً للمتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | اسم النموذج المدعوم من موفر LLM. |
| apiKey | java.lang.String | مفتاح API (الرمز). |
| baseUrl | java.lang.String | عنوان URL الأساسي للـ LLM المتوافق مع OpenAI. |
| httpClient | java.net.HttpURLConnection | مثيل HttpClient مداراً خارجياً. |
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

يرسل تعليمات دردشة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpConnection مقدم ويعيد رسالة الاستجابة إلى التعليمات المعطاة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String |  |
**القيمة المرجعة:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

ينشئ مثلاً لمحادثة. على عكس الاستدعاءات العادية للذكاء الاصطناعي، تحتفظ المحادثات بكامل السياق.

**القيمة المرجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

يحرر الموارد المستخدمة بواسطة هذا المثيل.