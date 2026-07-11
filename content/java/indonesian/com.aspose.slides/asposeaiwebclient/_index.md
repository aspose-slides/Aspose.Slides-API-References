---
title: AsposeAIWebClient
second_title: Referensi API Aspose.Slides untuk Java
description: Implementasi bawaan yang terhubung ke LLM milik Aspose.
type: docs
url: /id/com.aspose.slides/asposeaiwebclient/
---
**Warisan:**  
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Implementasi bawaan [IAIWebClient](../../com.aspose.slides/iaiwebclient) yang terhubung ke LLM milik Aspose. Ini adalah klien default yang digunakan oleh konstruktor tanpa parameter  SlidesAIAgent() .

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default menggunakan  HttpClient  yang dikelola secara eksternal. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus menggunakan  HttpClient  yang dikelola secara eksternal. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Membuat sebuah instance percakapan. |
| [dispose()](#dispose--) | Melepaskan sumber daya yang digunakan oleh instance ini. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default. Ini adalah klien yang digunakan oleh konstruktor tanpa parameter  SlidesAIAgent() , sehingga membuatnya secara eksplisit hanya diperlukan ketika mengirimkan klien ke konstruktor  SlidesAIAgent(IAIWebClient)  secara langsung.

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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default menggunakan  HttpClient  yang dikelola secara eksternal.  HttpClient  yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Sebuah instance  HttpClient  yang dikelola secara eksternal. |

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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus. Gunakan overload ini ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides; jika tidak, gunakan overload  AsposeAIWebClient()  dengan URL default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL endpoint LLM Aspose, disediakan oleh tim Aspose.Slides. |

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

Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus menggunakan  HttpClient  yang dikelola secara eksternal.  HttpClient  yang diberikan tidak dibuang oleh instance ini dan tetap dimiliki oleh pemanggil. Gunakan overload ini ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides dan ingin menyediakan  HttpClient  Anda sendiri; jika Anda hanya memerlukan  HttpClient  Anda sendiri dengan URL default, gunakan overload  AsposeAIWebClient(HttpClient)  sebagai gantinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL endpoint LLM Aspose, disediakan oleh tim Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Sebuah instance  HttpClient  yang dikelola secara eksternal. |

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

Mengirimkan instruksi chat ke model AI menggunakan instance HttpConnection yang disediakan dan mengembalikan pesan respons untuk instruksi yang diberikan.

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

Membuat sebuah instance percakapan. Tidak seperti panggilan AI biasa, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Melepaskan sumber daya yang digunakan oleh instance ini.