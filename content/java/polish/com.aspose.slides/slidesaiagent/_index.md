---
title: SlidesAIAgent
second_title: Aspose.Slides dla Java – Dokumentacja API
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Inicjalizuje nową instancję [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) z niestandardowym klientem AI. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Inicjalizuje nową instancję [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) przy użyciu wbudowanego [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) z domyślną konfiguracją. |
## Metody

| Metoda | Opis |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generuje instancję prezentacji na podstawie opisu tekstowego. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generuje instancję prezentacji na podstawie opisu tekstowego. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inicjalizuje nową instancję [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) z niestandardowym klientem AI. Użyj tego przeciążenia, aby określić dostawcę AI, dostarczyć własny LLM lub dostosować połączenie (na przykład, podając własny java.net.HttpURLConnection). Można użyć dowolnej implementacji [IAIWebClient](../../com.aspose.slides/iaiwebclient). Aby użyć wbudowanego [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) z domyślną konfiguracją, użyj przeciążenia SlidesAIAgent() zamiast tego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instancja klienta AI. Można użyć dowolnej implementacji [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inicjalizuje nową instancję [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) przy użyciu wbudowanego [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) z domyślną konfiguracją. Klient łączy się z własnym LLM firmy Aspose i nie wymaga dodatkowej konfiguracji. Aby użyć innego klienta AI, użyj przeciążenia SlidesAIAgent(IAIWebClient) zamiast tego.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Docelowa prezentacja |
| language | java.lang.String | Docelowy język

--------------------

Poniższy przykład używa domyślnego [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), który jest tworzony przez konstruktor SlidesAIAgent() bez parametrów i łączy się z własnym LLM firmy Aspose. Aby użyć innego dostawcy AI, dostarczyć własny LLM lub dostosować połączenie (na przykład, podając własny java.net.HttpURLConnection), przekaż implementację [IAIWebClient](../../com.aspose.slides/iaiwebclient) do konstruktora SlidesAIAgent(IAIWebClient).

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

Generuje instancję prezentacji na podstawie opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| description | java.lang.String | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentationContentAmount | int | Ilość treści w powstałej prezentacji.

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

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Generuje instancję prezentacji na podstawie opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| description | java.lang.String | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentationContentAmount | int | Ilość treści w powstałej prezentacji. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja używana jako szablon układu i projektu, zastępująca domyślny szablon.

--------------------

Poniższy przykład używa domyślnego [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), który jest tworzony przez konstruktor SlidesAIAgent() bez parametrów i łączy się z własnym LLM firmy Aspose. Aby użyć innego dostawcy AI, dostarczyć własny LLM lub dostosować połączenie (na przykład, podając własny java.net.HttpURLConnection), przekaż implementację [IAIWebClient](../../com.aspose.slides/iaiwebclient) do konstruktora SlidesAIAgent(IAIWebClient).

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

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)