---
title: SlidesAIAgent
second_title: Aspose.Slides untuk Android via Referensi API Java
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI (synchronous version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation instance from a text description. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation instance from a text description. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Konstruktor SlidesAIAgent

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI client instance |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

Menerjemahkan presentasi ke bahasa yang ditentukan menggunakan AI (versi sinkron).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi target |
| language | java.lang.String | Bahasa target

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

Menghasilkan instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau potongan teks dalam bahasa yang diperlukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| description | java.lang.String | Topik, ide, kutipan, atau potongan teks. |
| presentationContentAmount | int | Jumlah konten dalam presentasi yang dihasilkan.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

Menghasilkan instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau potongan teks dalam bahasa yang diperlukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| description | java.lang.String | Topik, ide, kutipan, atau potongan teks. |
| presentationContentAmount | int | Jumlah konten dalam presentasi yang dihasilkan. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang digunakan sebagai templat untuk tata letak dan desain, menggantikan templat default.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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