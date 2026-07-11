---
title: OpenAICompatibleWebClient
second_title: Referensi API Aspose.Slides untuk Java
description: Implementasi bawaan yang menghubungkan ke penyedia LLM yang kompatibel dengan OpenAI pada URL dasar yang ditentukan.
type: docs
url: /id/com.aspose.slides/openaicompatiblewebclient/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Implementasi bawaan [IAIWebClient](../../com.aspose.slides/iaiwebclient) yang terhubung ke penyedia LLM yang kompatibel dengan OpenAI pada URL dasar yang ditentukan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Membuat instance klien web yang kompatibel dengan OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Membuat instance klien web yang kompatibel dengan OpenAI yang menggunakan HttpClient yang dikelola secara eksternal. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Membuat instance percakapan. |
| [dispose()](#dispose--) | Melepaskan sumber daya yang digunakan oleh instance ini. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Membuat instance klien web yang kompatibel dengan OpenAI.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Nama model yang didukung oleh penyedia LLM. |
| apiKey | java.lang.String | Kunci API (token). |
| baseUrl | java.lang.String | URL dasar LLM yang kompatibel dengan OpenAI. |
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

Membuat instance klien web yang kompatibel dengan OpenAI yang menggunakan HttpClient yang dikelola secara eksternal. HttpClient yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Nama model yang didukung oleh penyedia LLM. |
| apiKey | java.lang.String | Kunci API (token). |
| baseUrl | java.lang.String | URL dasar LLM yang kompatibel dengan OpenAI. |
| httpClient | java.net.HttpURLConnection | Sebuah instance HttpClient yang dikelola secara eksternal. |
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

Mengirimkan instruksi chat ke model AI menggunakan instance HttpConnection yang disediakan dan mengembalikan pesan respons ke instruksi yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Mengembalikan:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Membuat instance percakapan. Tidak seperti panggilan AI reguler, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Melepaskan sumber daya yang digunakan oleh instance ini.