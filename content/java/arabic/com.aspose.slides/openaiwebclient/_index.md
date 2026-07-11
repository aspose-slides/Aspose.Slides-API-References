---
title: OpenAIWebClient
second_title: مرجع API Aspose.Slides للغة Java
description: تنفيذ مدمج يتصل بواجهة برمجة تطبيقات OpenAI.
type: docs
url: /ar/com.aspose.slides/openaiwebclient/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بواجهة برمجة تطبيقات OpenAI.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثيلاً لعميل الويب OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثيلاً لعميل الويب OpenAI يستخدم HttpClient مدار خارجيًا. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | ينشئ مثيلاً لمحادثة. |
| [close()](#close--) | يحرّر الموارد المستخدمة بواسطة هذا المثيل. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

ينشئ مثيلاً لعميل الويب OpenAI.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم المحتملة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح واجهة برمجة تطبيقات OpenAI. |
| organizationId | java.lang.String | معرف المؤسسة (اختياري). |
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

ينشئ مثيلاً لعميل الويب OpenAI يستخدم HttpClient مدار خارجيًا. لا يتم تحرير HttpClient المقدم بواسطة هذا المثيل ويظل مملوكًا للمتصل.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم المحتملة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح واجهة برمجة تطبيقات OpenAI |
| organizationId | java.lang.String | معرف المؤسسة (اختياري) |
| httpClient | java.net.HttpURLConnection | مثيل HttpClient مدار خارجيًا |
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

يرسل توجيه محادثة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpConnection مقدم ويعيد رسالة الاستجابة إلى التوجيه المقدم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String |  |

**الإرجاع:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثيلاً لمحادثة. على عكس الاستدعاءات العادية للذكاء الاصطناعي، تحتفظ المحادثات بالسياق بالكامل.

**الإرجاع:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).

### close() {#close--}
```
public final void close()
```

يحرّر الموارد المستخدمة بواسطة هذا المثيل.