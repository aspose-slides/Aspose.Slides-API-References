---
title: OpenAIWebClient
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: عميل ويب OpenAI خفيف الوزن مدمج
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

عميل ويب OpenAI خفيف الوزن مدمج
## المُنشئون

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثيلاً لعميل ويب OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثيلاً لعميل ويب OpenAI. |
## الطرق

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام مثيل مُدار خارجيًا ويُرجع رسالة الاستجابة إلى التعليمات المعطاة. |
| [createConversation()](#createConversation--) | ينشئ مثيلاً لمحادثة. |
| [close()](#close--) | يطلق الموارد المستخدمة بواسطة هذا المثيل. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

ينشئ مثيلاً لعميل ويب OpenAI.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم الممكنة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح API الخاص بـ OpenAI |
| organizationId | java.lang.String | معرّف المؤسسة (اختياري) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

ينشئ مثيلاً لعميل ويب OpenAI.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | نموذج لغة OpenAI. القيم الممكنة: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | مفتاح API الخاص بـ OpenAI |
| organizationId | java.lang.String | معرّف المؤسسة (اختياري) |
| httpClient | java.net.HttpURLConnection | مثيل HttpURLConnection مُدار خارجيًا. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام مثيل مُدار خارجيًا ويُرجع رسالة الاستجابة إلى التعليمات المعطاة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | التعليمات أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي |

**القيمة المرجعة:**
java.lang.String - الرسالة التي يولدها نموذج الذكاء الاصطناعي استجابةً للتعليمات المعطاة.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثيلاً لمحادثة. على عكس استدعاءات الذكاء الاصطناعي العادية، تحتفظ المحادثات بالسياق بالكامل.

**القيمة المرجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation)

### close() {#close--}
```
public final void close()
```

يطلق الموارد المستخدمة بواسطة هذا المثيل.