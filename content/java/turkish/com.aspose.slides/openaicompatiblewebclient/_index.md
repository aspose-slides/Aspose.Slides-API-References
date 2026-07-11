---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides için Java API Referansı
description: Belirtilen temel URL'de bir OpenAI uyumlu LLM sağlayıcısına bağlanan yerleşik bir uygulama.
type: docs
url: /tr/com.aspose.slides/openaicompatiblewebclient/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Belirtilen temel URL'de bir OpenAI uyumlu LLM sağlayıcısına bağlanan yerleşik bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI uyumlu web istemcisinin bir örneğini oluşturur. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Harici yönetilen bir HttpClient kullanan OpenAI uyumlu web istemcisinin bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
| [dispose()](#dispose--) | Bu örnek tarafından kullanılan kaynakları serbest bırakır. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI uyumlu web istemcisinin bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | LLM sağlayıcısı tarafından desteklenen model adı. |
| apiKey | java.lang.String | API anahtarı (token). |
| baseUrl | java.lang.String | OpenAI uyumlu LLM'nin temel URL'si. |
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

Harici olarak yönetilen bir HttpClient kullanan OpenAI uyumlu web istemcisinin bir örneğini oluşturur. Sağlanan HttpClient bu örnek tarafından yok edilmez ve çağıranın sorumluluğunda kalır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | LLM sağlayıcısı tarafından desteklenen model adı. |
| apiKey | java.lang.String | API anahtarı (token). |
| baseUrl | java.lang.String | OpenAI uyumlu LLM'nin temel URL'si. |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpClient örneği. |
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

Sağlanan HttpConnection örneği kullanılarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Döndürür:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.

**Döndürür:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Bir [IAIConversation](../../com.aspose.slides/iaiconversation) örneği.
### dispose() {#dispose--}
```
public final void dispose()
```

Bu örnek tarafından kullanılan kaynakları serbest bırakır.