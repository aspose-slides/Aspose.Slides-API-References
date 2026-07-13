---
title: SlidesAIAgent
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Udostępnia funkcje oparte na AI do przetwarzania prezentacji.
type: docs
url: /pl/com.aspose.slides/slidesaiagent/
---
**Dziedziczenie:**
java.lang.Object
```
public class SlidesAIAgent
```

Udostępnia funkcje oparte na AI do przetwarzania prezentacji.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Konstruktor SlidesAIAgent |
## Metody

| Metoda | Opis |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generuje instancję prezentacji z opisu tekstowego. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generuje instancję prezentacji z opisu tekstowego. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Konstruktor SlidesAIAgent

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instancja klienta AI |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Docelowa prezentacja |
| language | java.lang.String | Docelowy język

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

Generuje instancję prezentacji z opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| description | java.lang.String | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentationContentAmount | int | Ilość treści w powstałej prezentacji.

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

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Generuje instancję prezentacji z opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| description | java.lang.String | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentationContentAmount | int | Ilość treści w powstałej prezentacji. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja używana jako szablon układu i projektu, zastępująca domyślny szablon.

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

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)