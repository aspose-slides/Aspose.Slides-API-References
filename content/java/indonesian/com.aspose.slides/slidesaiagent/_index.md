---
title: SlidesAIAgent
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan fitur berbasis AI untuk memproses presentasi.
type: docs
url: /id/com.aspose.slides/slidesaiagent/
---
**Pewarisan:**
java.lang.Object
```
public class SlidesAIAgent
```

Menyediakan fitur berbasis AI untuk memproses presentasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Menginisialisasi instance baru dari [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) dengan klien AI khusus. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Menginisialisasi instance baru dari [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) menggunakan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) bawaan dengan konfigurasi standar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Menerjemahkan presentasi ke bahasa yang ditentukan menggunakan AI (versi sinkron). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Menghasilkan instance presentasi dari deskripsi teks. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Menghasilkan instance presentasi dari deskripsi teks. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


Menginisialisasi instance baru dari [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) dengan klien AI khusus. Gunakan overload ini untuk menentukan penyedia AI, menyediakan LLM Anda sendiri, atau menyesuaikan koneksi (misalnya, dengan menyediakan java.net.HttpURLConnection Anda sendiri). Implementasi apa pun dari [IAIWebClient](../../com.aspose.slides/iaiwebclient) dapat digunakan. Untuk menggunakan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) bawaan dengan konfigurasi standar, gunakan overload SlidesAIAgent() sebagai gantinya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instance klien AI. Implementasi apa pun dari [IAIWebClient](../../com.aspose.slides/iaiwebclient) dapat digunakan. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```


Menginisialisasi instance baru dari [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) menggunakan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) bawaan dengan konfigurasi standar. Klien terhubung ke LLM milik Aspose dan tidak memerlukan konfigurasi tambahan. Untuk menggunakan klien AI yang berbeda, gunakan overload SlidesAIAgent(IAIWebClient) sebagai gantinya.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```


Menerjemahkan presentasi ke bahasa yang ditentukan menggunakan AI (versi sinkron).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi target |
| language | java.lang.String | Bahasa target

--------------------

Contoh di bawah menggunakan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) default, yang dibuat oleh konstruktor SlidesAIAgent() tanpa parameter dan terhubung ke LLM milik Aspose. Untuk menggunakan penyedia AI yang berbeda, menyediakan LLM Anda sendiri, atau menyesuaikan koneksi (misalnya, dengan menyediakan java.net.HttpURLConnection Anda sendiri), berikan implementasi [IAIWebClient](../../com.aspose.slides/iaiwebclient) ke konstruktor SlidesAIAgent(IAIWebClient).

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```


Menghasilkan instance presentasi dari deskripsi teks. Sediakan topik, ide, kutipan, atau potongan teks dalam bahasa yang diminta.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| description | java.lang.String | Topik, ide, kutipan, atau potongan teks. |
| presentationContentAmount | int | Jumlah konten dalam presentasi yang dihasilkan.

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Menghasilkan instance presentasi dari deskripsi teks. Sediakan topik, ide, kutipan, atau potongan teks dalam bahasa yang diminta.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| description | java.lang.String | Topik, ide, kutipan, atau potongan teks. |
| presentationContentAmount | int | Jumlah konten dalam presentasi yang dihasilkan. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Sebuah presentasi yang akan digunakan sebagai template untuk tata letak dan desain, menggantikan template default.

--------------------

Contoh di bawah menggunakan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) default, yang dibuat oleh konstruktor SlidesAIAgent() tanpa parameter dan terhubung ke LLM milik Aspose. Untuk menggunakan penyedia AI yang berbeda, menyediakan LLM Anda sendiri, atau menyesuaikan koneksi (misalnya, dengan menyediakan java.net.HttpURLConnection Anda sendiri), berikan implementasi [IAIWebClient](../../com.aspose.slides/iaiwebclient) ke konstruktor SlidesAIAgent(IAIWebClient).

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)