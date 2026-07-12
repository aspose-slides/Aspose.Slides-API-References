---
title: OpenAIWebClient
second_title: Aspose.Slides for Android Java API Referansı
description: Yerleşik hafif OpenAI web istemcisi
type: docs
url: /tr/com.aspose.slides/openaiwebclient/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Yerleşik hafif OpenAI web istemcisi
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI Web istemcisinin bir örneğini oluşturur. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI Web istemcisinin bir örneğini oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Harici olarak yönetilen bir örnek kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür. |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
| [close()](#close--) | Bu örnek tarafından kullanılan kaynakları serbest bırakır. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI Web istemcisinin bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | OpenAI dil modeli. Olası değerler: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API anahtarı |
| organizationId | java.lang.String | Organization ID (isteğe bağlı) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

OpenAI Web istemcisinin bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | OpenAI dil modeli. Olası değerler: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API anahtarı |
| organizationId | java.lang.String | Organization ID (isteğe bağlı) |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpURLConnection örneği. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Harici olarak yönetilen bir örnek kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj |

**Döndürür:**
java.lang.String - AI modeli tarafından verilen talimata yanıt olarak oluşturulan mesaj
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