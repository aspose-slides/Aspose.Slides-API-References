---
title: AsposeAIWebClient
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: تنفيذ مدمج يتصل بـ LLM الخاص بـ Aspose.
type: docs
url: /ar/com.aspose.slides/asposeaiwebclient/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفّذة:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

تنفيذ مدمج [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بـ LLM الخاص بـ Aspose. هذا هو العميل الافتراضي المستخدم بواسطة المُنشئ SlidesAIAgent() بدون معلمات.  

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed  HttpURLConnection . |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

ينشئ مثلاً من عميل ويب Aspose AI يتصل بنقطة وصول Aspose LLM الافتراضية. هذا هو العميل المستخدم بواسطة المُنشئ SlidesAIAgent() بدون معلمات، لذا لا يُحتاج إلى إنشائه صراحةً إلا عند تمريره إلى المُنشئ SlidesAIAgent(IAIWebClient) مباشرةً.

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

ينشئ مثلاً من عميل ويب Aspose AI يتصل بنقطة وصول Aspose LLM الافتراضية باستخدام HttpURLConnection مُدار خارجيًا. لا يتم التخلص من كائن HttpURLConnection المقدم بواسطة هذه المثلة ويظل مملوكًا للمتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpURLConnection  instance.

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

ينشئ مثلاً من عميل ويب Aspose AI يتصل بعنوان نقطة وصول مخصص. استخدم هذه overload عندما تحصل على عنوان URL يقدمه فريق Aspose.Slides؛ وإلا استخدم overload  AsposeAIWebClient()  مع عنوان URL الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team.

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

ينشئ مثلاً من عميل ويب Aspose AI يتصل بعنوان نقطة وصول مخصص باستخدام HttpURLConnection مُدار خارجيًا. لا يتم التخلص من كائن HttpURLConnection المقدم بواسطة هذه المثلة ويظل مملوكًا للمتصل. استخدم هذه overload عندما تحصل على عنوان URL يقدمه فريق Aspose.Slides وتريد تزويد HttpURLConnection الخاص بك؛ إذا كنت تحتاج فقط إلى HttpURLConnection الخاص بك مع العنوان الافتراضي، استخدم overload  AsposeAIWebClient(HttpURLConnection)  بدلاً من ذلك.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpURLConnection  instance.

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

يرسل تعليمًا للدردشة إلى نموذج AI ويعيد رسالة الرد على التعليم المقدم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | The instruction or message to be processed by the AI model. |

**القيمة المرتجعة:**
java.lang.String - The message generated by the AI model in response to the given instruction.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

ينشئ مثلاً من محادثة. على عكس استدعاءات AI العادية، تحتفظ المحادثات بسياق كامل.

**القيمة المرتجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

يطلق الموارد المستخدمة بواسطة هذه المثلة.