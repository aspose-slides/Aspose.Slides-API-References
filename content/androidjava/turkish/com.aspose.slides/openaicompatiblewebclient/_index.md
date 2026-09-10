---
title: OpenAICompatibleWebClient
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Belirtilen temel URL'de bir OpenAI uyumlu LLM sağlayıcısına bağlanan yerleşik  bir uygulama.
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
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Harici olarak yönetilen bir HttpURLConnection kullanan OpenAI uyumlu web istemcisinin bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Harici olarak yönetilen bir HttpURLConnection örneğini kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür. |
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
| baseUrl | java.lang.String | OpenAI uyumlu LLM'nin temel URL'si.

```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```


Harici olarak yönetilen bir HttpURLConnection kullanan OpenAI uyumlu web istemcisinin bir örneğini oluşturur. Sağlanan HttpURLConnection bu örnek tarafından serbest bırakılmaz ve çağıran tarafından yönetilmeye devam eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| model | java.lang.String | LLM sağlayıcısı tarafından desteklenen model adı. |
| apiKey | java.lang.String | API anahtarı (token). |
| baseUrl | java.lang.String | OpenAI uyumlu LLM'nin temel URL'si. |
| httpClient | java.net.HttpURLConnection | Harici olarak yönetilen bir HttpURLConnection örneği.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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


Harici olarak yönetilen bir HttpURLConnection örneğini kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj. |

**Döndürür:**
java.lang.String - Verilen talimata yanıt olarak AI modeli tarafından oluşturulan mesaj.
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