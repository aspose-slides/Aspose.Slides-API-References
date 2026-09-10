---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Implementasi bawaan yang menghubungkan ke penyedia LLM yang kompatibel dengan OpenAI pada URL dasar yang ditentukan.
type: docs
url: /id/com.aspose.slides/openaicompatiblewebclient/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Implementasi bawaan [IAIWebClient](../../com.aspose.slides/iaiwebclient) yang menghubungkan ke penyedia LLM yang kompatibel dengan OpenAI pada URL dasar yang ditentukan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Membuat sebuah instance dari klien web yang kompatibel dengan OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Membuat sebuah instance dari klien web yang kompatibel dengan OpenAI yang menggunakan HttpURLConnection yang dikelola secara eksternal. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Mengirim instruksi obrolan ke model AI menggunakan instance HttpURLConnection yang dikelola secara eksternal dan mengembalikan pesan respons ke instruksi yang diberikan. |
| [createConversation()](#createConversation--) | Membuat sebuah instance percakapan. |
| [dispose()](#dispose--) | Melepaskan sumber daya yang digunakan oleh instance ini. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Membuat sebuah instance dari klien web yang kompatibel dengan OpenAI.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Nama model yang didukung oleh penyedia LLM. |
| apiKey | java.lang.String | Kunci API (token). |
| baseUrl | java.lang.String | URL dasar dari LLM yang kompatibel dengan OpenAI. |
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

Membuat sebuah instance dari klien web yang kompatibel dengan OpenAI yang menggunakan HttpURLConnection yang dikelola secara eksternal. HttpURLConnection yang disediakan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Nama model yang didukung oleh penyedia LLM. |
| apiKey | java.lang.String | Kunci API (token). |
| baseUrl | java.lang.String | URL dasar dari LLM yang kompatibel dengan OpenAI. |
| httpClient | java.net.HttpURLConnection | Instance HttpURLConnection yang dikelola secara eksternal. |
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

Mengirim instruksi obrolan ke model AI menggunakan instance HttpURLConnection yang dikelola secara eksternal dan mengembalikan pesan respons ke instruksi yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String | Instruksi atau pesan yang akan diproses oleh model AI. |

**Mengembalikan:**
java.lang.String - Pesan yang dihasilkan oleh model AI sebagai respons terhadap instruksi yang diberikan.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Membuat sebuah instance percakapan. Tidak seperti panggilan AI biasa, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### dispose() {#dispose--}
```
public final void dispose()
```

Melepaskan sumber daya yang digunakan oleh instance ini.