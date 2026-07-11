---
title: AsposeAIWebClient
second_title: مرجع API لـ Aspose.Slides للـ Java
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

تنفيذ مدمج من نوع [IAIWebClient](../../com.aspose.slides/iaiwebclient) يتصل بـ LLM الخاص بشركة Aspose. هذا هو العميل الافتراضي المستخدم في منشئ  SlidesAIAgent()  بدون معلمات.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية لـ Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية لـ Aspose LLM باستخدام  HttpClient  يتم إدارته خارجيًا. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية باستخدام  HttpClient  يتم إدارته خارجيًا. |
## الدوال

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | ينشئ مثلاً لمحادثة. |
| [dispose()](#dispose--) | يحرر الموارد المستخدمة بواسطة هذا الكائن. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية لـ Aspose LLM. هذا هو العميل المستخدم في منشئ  SlidesAIAgent()  بدون معلمات، لذا لا يكون إنشاءه صراحةً مطلوبًا إلا عند تمريره مباشرةً إلى منشئ  SlidesAIAgent(IAIWebClient) .
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية لـ Aspose LLM باستخدام  HttpClient  يتم إدارته خارجيًا. لا يتم إتلاف  HttpClient  المقدم بواسطة هذه الحالة ويبقى مالكًا للمتصل.
**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | مثيل  HttpClient  يتم إدارته خارجيًا. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية. استخدم هذا التحميل عندما يكون لديك عنوان URL مقدم من فريق Aspose.Slides؛ وإلا، استخدم التحميل  AsposeAIWebClient()  مع العنوان الافتراضي.
**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL لنقطة النهاية لـ Aspose LLM، مقدَّم من فريق Aspose.Slides. |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

ينشئ مثلاً لعميل الويب Aspose AI الذي يتصل بعنوان URL مخصص لنقطة النهاية باستخدام  HttpClient  يتم إدارته خارجيًا. لا يتم إتلاف  HttpClient  المقدم بواسطة هذه الحالة ويبقى مالكًا للمتصل. استخدم هذا التحميل عندما يكون لديك عنوان URL مقدم من فريق Aspose.Slides وتريد توفير  HttpClient  الخاص بك؛ إذا كنت تحتاج فقط إلى  HttpClient  الخاص بك مع العنوان الافتراضي، فاستخدم التحميل  AsposeAIWebClient(HttpClient)  بدلاً من ذلك.
**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| url | java.lang.String | عنوان URL لنقطة النهاية لـ Aspose LLM، مقدَّم من فريق Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | مثيل  HttpClient  يتم إدارته خارجيًا. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

يرسل تعليمًا للدردشة إلى نموذج الذكاء الاصطناعي باستخدام مثيل HttpConnection المقدم ويعيد رسالة الاستجابة للتعليم المقدم.
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

ينشئ مثلاً لمحادثة. على عكس الطلبات العادية للذكاء الاصطناعي، تحتفظ المحادثات بجميع السياقات.
**الإرجاع:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثال على مثيل [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

يحرر الموارد المستخدمة بواسطة هذا الكائن.