---
title: AsposeAIWebClient
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Aspose'un kendi LLM'sine bağlanan yerleşik bir uygulama.
type: docs
url: /tr/com.aspose.slides/asposeaiwebclient/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Aspose'un kendi LLM'sine bağlanan yerleşik bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması. Bu, parametresiz  SlidesAIAgent()  yapıcısı tarafından kullanılan varsayılan istemcidir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Harici olarak yönetilen bir  HttpURLConnection  kullanarak varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Harici olarak yönetilen bir  HttpURLConnection  kullanarak özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür. |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
| [dispose()](#dispose--) | Bu örnek tarafından kullanılan kaynakları serbest bırakır. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


Varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Bu, parametresiz  SlidesAIAgent()  yapıcısı tarafından kullanılan istemcidir; bu nedenle istemciyi doğrudan SlidesAIAgent(IAIWebClient) yapıcısına geçirirken açıkça oluşturulması yalnızca gerektiğinde yapılır.

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


Harici olarak yönetilen bir  HttpURLConnection  kullanarak varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Sağlanan  HttpURLConnection  bu örnek tarafından kapatılmaz ve çağıran tarafından sahiplenilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpURLConnection örneği.

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


Özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Bu aşırı yüklemeyi, Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda kullanın; aksi takdirde, varsayılan URL ile AsposeAIWebClient() aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM'nin uç nokta URL'si, Aspose.Slides ekibi tarafından sağlanmıştır.

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


Harici olarak yönetilen bir  HttpURLConnection  kullanarak özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Sağlanan  HttpURLConnection  bu örnek tarafından kapatılmaz ve çağıran tarafından sahiplenilir. Bu aşırı yüklemeyi, Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda ve kendi HttpURLConnection'ınızı sağlamak istediğinizde kullanın; yalnızca varsayılan URL ile kendi HttpURLConnection'ınıza ihtiyacınız varsa, bunun yerine AsposeAIWebClient(HttpURLConnection) aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM'nin uç nokta URL'si, Aspose.Slides ekibi tarafından sağlanmıştır. |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpURLConnection örneği.

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


AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj. |

**Dönüş Değeri:**
java.lang.String - Verilen talimata yanıt olarak AI modeli tarafından oluşturulan mesaj.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.

**Dönüş Değeri:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Bir [IAIConversation](../../com.aspose.slides/iaiconversation) örneği.
### dispose() {#dispose--}
```
public final void dispose()
```


Bu örnek tarafından kullanılan kaynakları serbest bırakır.