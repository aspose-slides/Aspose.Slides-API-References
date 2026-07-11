---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API Referansı
description: OpenAI API'sine bağlanan yerleşik bir uygulama.
type: docs
url: /tr/com.aspose.slides/openaiwebclient/
---
**Kalıtım:**  
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

OpenAI API'sine bağlanan yerleşik [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI web istemcisinin bir örneğini oluşturur. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Harici olarak yönetilen bir HttpClient kullanan OpenAI web istemcisinin bir örneğini oluşturur. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
| [close()](#close--) | Bu örnek tarafından kullanılan kaynakları serbest bırakır. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI web istemcisinin bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | OpenAI dil modeli. Olası değerler: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API anahtarı. |
| organizationId | java.lang.String | Organizasyon Kimliği (isteğe bağlı). |
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

Harici olarak yönetilen bir HttpClient kullanan OpenAI web istemcisinin bir örneğini oluşturur. Sağlanan HttpClient bu örnek tarafından serbest bırakılmaz ve çağıran tarafından sahiplenilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | OpenAI dil modeli. Olası değerler: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API anahtarı |
| organizationId | java.lang.String | Organizasyon Kimliği (isteğe bağlı) |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpClient örneği |
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

Sağlanan HttpConnection örneğini kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

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

### close() {#close--}
```
public final void close()
```

Bu örnek tarafından kullanılan kaynakları serbest bırakır.