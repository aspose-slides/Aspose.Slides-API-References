---
title: AsposeAIWebClient
second_title: Aspose.Slides لمرجع API لجافا
description: تنفيذ مدمج يتصل بـ LLM الخاص بـ Aspose.
type: docs
url: /ar/com.aspose.slides/asposeaiwebclient/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بـ LLM الخاص بـ Aspose. هذا هو العميل الافتراضي المستخدم بواسطة المُنشئ SlidesAIAgent() غير المعتمد على المعاملات.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية Aspose LLM باستخدام HttpURLConnection تم إدارته خارجيًا. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية باستخدام HttpURLConnection تم إدارته خارجيًا. |

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي ويعيد رسالة الاستجابة للتعليمات المعطاة. |
| [createConversation()](#createConversation--) | ينشئ مثلاً لمحادثة. |
| [dispose()](#dispose--) | يطلق الموارد المستخدمة بواسطة هذا المثيل. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية Aspose LLM. هذا هو العميل المستخدم بواسطة المُنشئ SlidesAIAgent() غير المعتمد على المعاملات، لذا لا يلزم إنشاءه صراحةً إلا عند تمرير العميل إلى المُنشئ SlidesAIAgent(IAIWebClient) مباشرةً.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية Aspose LLM باستخدام HttpURLConnection تم إدارته خارجيًا. لا يتم تحرير HttpURLConnection المقدم بواسطة هذه المثيلة ويظل مملوكًا للمتصل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | مثيل HttpURLConnection تم إدارته خارجيًا. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية. استخدم هذه النسخة عندما يكون لديك عنوان URL موفر من فريق Aspose.Slides؛ وإلا، استخدم النسخة AsposeAIWebClient() مع عنوان URL الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL لنقطة النهاية Aspose LLM، موفر من فريق Aspose.Slides. |
```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية باستخدام HttpURLConnection تم إدارته خارجيًا. لا يتم تحرير HttpURLConnection المقدم بواسطة هذه المثيلة ويظل مملوكًا للمتصل. استخدم هذه النسخة عندما يكون لديك عنوان URL موفر من فريق Aspose.Slides وتريد تزويد HttpURLConnection خاصتك؛ إذا كنت تحتاج فقط HttpURLConnection الخاص بك مع عنوان URL الافتراضي، استخدم النسخة AsposeAIWebClient(HttpURLConnection) بدلاً من ذلك.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL لنقطة النهاية Aspose LLM، موفر من فريق Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | مثيل HttpURLConnection تم إدارته خارجيًا. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي ويعيد رسالة الاستجابة للتعليمات المعطاة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليم أو الرسالة التي يجب معالجتها بواسطة نموذج الذكاء الاصطناعي. |

**الإرجاع:**
java.lang.String - الرسالة التي يولدها نموذج الذكاء الاصطناعي استجابة للتعليم المعطى.

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

ينشئ مثلاً لمحادثة. على عكس استدعاءات AI العادية، تحتفظ المحادثات بكل السياق.

**الإرجاع:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

يطلق الموارد المستخدمة بواسطة هذا المثيل.