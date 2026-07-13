---
title: OpenAIWebClient
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Klien web OpenAI ringan bawaan
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

Klien web OpenAI ringan bawaan
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Membuat instance Klien Web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Membuat instance Klien Web OpenAI. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Mengirim instruksi obrolan ke model AI menggunakan instance yang dikelola secara eksternal dan mengembalikan pesan respons ke instruksi yang diberikan. |
| [createConversation()](#createConversation--) | Membuat instance percakapan. |
| [close()](#close--) | Melepaskan sumber daya yang digunakan oleh instance ini. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Membuat instance Klien Web OpenAI.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Model bahasa OpenAI. Nilai yang mungkin: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Kunci API OpenAI |
| organizationId | java.lang.String | ID Organisasi (opsional) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Membuat instance Klien Web OpenAI.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| model | java.lang.String | Model bahasa OpenAI. Nilai yang mungkin: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Kunci API OpenAI |
| organizationId | java.lang.String | ID Organisasi (opsional) |
| httpClient | java.net.HttpURLConnection | Instance HttpURLConnection yang dikelola secara eksternal. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Mengirim instruksi obrolan ke model AI menggunakan instance yang dikelola secara eksternal dan mengembalikan pesan respons ke instruksi yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String | Instruksi atau pesan yang akan diproses oleh model AI |

**Mengembalikan:**
java.lang.String - Pesan yang dihasilkan oleh model AI sebagai respons terhadap instruksi yang diberikan.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Membuat instance percakapan. Tidak seperti panggilan AI biasa, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### close() {#close--}
```
public final void close()
```


Melepaskan sumber daya yang digunakan oleh instance ini.