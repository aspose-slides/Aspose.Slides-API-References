---
title: AsposeAIWebClient
second_title: Referensi API Aspose.Slides untuk Java
description: Implementasi bawaan yang terhubung ke LLM milik Aspose.
type: docs
url: /id/com.aspose.slides/asposeaiwebclient/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Implementasi [IAIWebClient](../../com.aspose.slides/iaiwebclient) bawaan yang terhubung ke LLM milik Aspose. Ini adalah klien default yang digunakan oleh konstruktor  SlidesAIAgent()  tanpa parameter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default menggunakan  HttpURLConnection  yang dikelola secara eksternal. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus menggunakan  HttpURLConnection  yang dikelola secara eksternal. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Mengirimkan instruksi obrolan ke model AI dan mengembalikan pesan respons untuk instruksi yang diberikan. |
| [createConversation()](#createConversation--) | Membuat sebuah instance percakapan. |
| [dispose()](#dispose--) | Membebaskan sumber daya yang digunakan oleh instance ini. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default. Ini adalah klien yang digunakan oleh konstruktor  SlidesAIAgent()  tanpa parameter, jadi membuatnya secara eksplisit hanya diperlukan ketika mengirimkan klien ke konstruktor  SlidesAIAgent(IAIWebClient)  secara langsung.

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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default menggunakan  HttpURLConnection  yang dikelola secara eksternal.  HttpURLConnection  yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Instance  HttpURLConnection  yang dikelola secara eksternal. |
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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus. Gunakan overload ini ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides; jika tidak, gunakan overload  AsposeAIWebClient()  dengan URL default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL endpoint LLM Aspose, yang disediakan oleh tim Aspose.Slides. |
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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus menggunakan  HttpURLConnection  yang dikelola secara eksternal.  HttpURLConnection  yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil. Gunakan overload ini ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides dan ingin menyediakan  HttpURLConnection  Anda sendiri; jika Anda hanya membutuhkan  HttpURLConnection  Anda dengan URL default, gunakan overload  AsposeAIWebClient(HttpURLConnection)  sebagai gantinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL endpoint LLM Aspose, yang disediakan oleh tim Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Instance  HttpURLConnection  yang dikelola secara eksternal. |
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

Mengirimkan instruksi obrolan ke model AI dan mengembalikan pesan respons untuk instruksi yang diberikan.

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

Membuat sebuah instance percakapan. Berbeda dengan panggilan AI biasa, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Membebaskan sumber daya yang digunakan oleh instance ini.