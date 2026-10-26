---
title: OpenAIWebClient
second_title: مرجع API ل Aspose.Slides للغة Java
description: تنفيذ مدمج يتصل بواجهة برمجة تطبيقات OpenAI.
type: docs
url: /ar/com.aspose.slides/openaiwebclient/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بواجهة برمجة تطبيقات OpenAI.
## المُنشئات

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثيلاً لعميل ويب OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثيلاً لعميل ويب OpenAI يستخدم HttpClient مدار خارجيًا. |
## الطرق

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | ينشئ مثيلاً للمحادثة. |
| [close()](#close--) | يطلق الموارد المستخدمة من قبل هذا المثيل. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

ينشئ مثيلاً لعميل ويب OpenAI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم المحتملة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح API الخاص بـ OpenAI. |
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

ينشئ مثيلاً لعميل ويب OpenAI يستخدم HttpClient مدار خارجيًا. الـ HttpClient المقدم لا يتم التخلص منه بواسطة هذا المثيل ويبقى مملوكًا للمتصل.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم المحتملة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح API الخاص بـ OpenAI |
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

يرسل توجيه دردشة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpConnection مقدم ويعيد رسالة الاستجابة للتوجيه المعطى.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثيلاً للمحادثة. على عكس طلبات الذكاء الاصطناعي العادية، تحتفظ المحادثات بالسياق الكامل.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

يطلق الموارد المستخدمة من قبل هذه المثيلة.