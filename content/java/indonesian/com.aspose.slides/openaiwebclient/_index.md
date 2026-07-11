---
title: OpenAIWebClient
second_title: Referensi API Aspose.Slides untuk Java
description: Implementasi bawaan yang terhubung ke API OpenAI.
type: docs
url: /id/com.aspose.slides/openaiwebclient/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Implementasi bawaan [IAIWebClient](../../com.aspose.slides/iaiwebclient) yang terhubung ke API OpenAI.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Membuat sebuah instance klien web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Membuat sebuah instance klien web OpenAI yang menggunakan HttpClient yang dikelola secara eksternal. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Membuat sebuah instance percakapan. |
| [close()](#close--) | Membebaskan sumber daya yang digunakan oleh instance ini. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Membuat sebuah instance klien web OpenAI.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Model bahasa OpenAI. Nilai yang mungkin: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Kunci API OpenAI. |
| organizationId | java.lang.String | ID organisasi (opsional). |
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

Membuat sebuah instance klien web OpenAI yang menggunakan HttpClient yang dikelola secara eksternal. HttpClient yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Model bahasa OpenAI. Nilai yang mungkin: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Kunci API OpenAI |
| organizationId | java.lang.String | ID organisasi (opsional) |
| httpClient | java.net.HttpURLConnection | Sebuah instance HttpClient yang dikelola secara eksternal |
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

Mengirim instruksi obrolan ke model AI menggunakan instance HttpConnection yang disediakan dan mengembalikan pesan respons terhadap instruksi tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Mengembalikan:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Membuat sebuah instance percakapan. Tidak seperti panggilan AI biasa, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Membebaskan sumber daya yang digunakan oleh instance ini.