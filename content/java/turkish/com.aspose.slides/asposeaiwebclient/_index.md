---
title: AsposeAIWebClient
second_title: Aspose.Slides için Java API Referansı
description: Aspose'un kendi LLM'sine bağlanan yerleşik bir uygulama.
type: docs
url: /tr/com.aspose.slides/asposeaiwebclient/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Aspose'un kendi LLM'sine bağlanan yerleşik bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması. Bu, parametresiz  SlidesAIAgent()  yapıcı tarafından kullanılan varsayılan istemcidir.

## Yapılandırıcılar

| Yapılandırıcı | Açıklama |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Dışarıdan yönetilen  HttpClient  kullanarak varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Dışarıdan yönetilen  HttpClient  kullanarak özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
| [dispose()](#dispose--) | Bu örnek tarafından kullanılan kaynakları serbest bırakır. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Bu, parametresiz  SlidesAIAgent()  yapıcı tarafından kullanılan istemcidir; bu nedenle, istemciyi  SlidesAIAgent(IAIWebClient)  yapıcısına doğrudan geçirdiğinizde açıkça oluşturmanız gerekir.

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

Dışarıdan yönetilen bir HttpClient kullanarak varsayılan Aspose LLM uç noktasına bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Sağlanan HttpClient bu örnek tarafından serbest bırakılmaz ve çağırıcı tarafından sahiplenilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Dışarıdan yönetilen bir HttpClient örneği.

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

Özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda bu aşırı yüklemeyi kullanın; aksi takdirde, varsayılan URL ile AsposeAIWebClient() aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM'nin uç nokta URL'si, Aspose.Slides ekibi tarafından sağlanır.

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

Dışarıdan yönetilen bir HttpClient kullanarak özel bir uç nokta URL'sine bağlanan Aspose AI web istemcisinin bir örneğini oluşturur. Sağlanan HttpClient bu örnek tarafından serbest bırakılmaz ve çağırıcı tarafından sahiplenilir. Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda ve kendi HttpClient'ınızı sağlamak istediğinizde bu aşırı yüklemeyi kullanın; yalnızca varsayılan URL ile kendi HttpClient'ınıza ihtiyacınız varsa, bunun yerine AsposeAIWebClient(HttpClient) aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM'nin uç nokta URL'si, Aspose.Slides ekibi tarafından sağlanır. |
| httpClient | java.net.HttpURLConnection | Dışarıdan yönetilen bir HttpClient örneği.

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

Sağlanan bir HttpConnection örneği kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Döndürür:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.

**Döndürür:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Bir [IAIConversation](../../com.aspose.slides/iaiconversation) örneği.

### dispose() {#dispose--}
```
public final void dispose()
```

Bu örnek tarafından kullanılan kaynakları serbest bırakır.