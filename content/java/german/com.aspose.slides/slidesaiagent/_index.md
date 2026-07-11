---
title: SlidesAIAgent
second_title: Aspose.Slides für Java API-Referenz
description: Bietet KI-gestützte Funktionen zur Verarbeitung von Präsentationen.
type: docs
url: /de/com.aspose.slides/slidesaiagent/
---
**Vererbung:**
java.lang.Object
```
public class SlidesAIAgent
```

Bietet KI-gestützte Funktionen zur Verarbeitung von Präsentationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initialisiert eine neue Instanz von [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) mit einem benutzerdefinierten KI-Client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initialisiert eine neue Instanz von [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) mit dem integrierten [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) und seiner Standardkonfiguration. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Übersetzt eine Präsentation in die angegebene Sprache mithilfe von KI (synchron). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Initialisiert eine neue Instanz von [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) mit einem benutzerdefinierten KI-Client. Verwenden Sie diese Überladung, um den KI-Anbieter anzugeben, Ihr eigenes LLM bereitzustellen oder die Verbindung anzupassen (z. B. durch Bereitstellung Ihres eigenen java.net.HttpURLConnection). Jede Implementierung von [IAIWebClient](../../com.aspose.slides/iaiwebclient) kann verwendet werden. Um das integrierte [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) mit seiner Standardkonfiguration zu nutzen, verwenden Sie stattdessen die Überladung SlidesAIAgent().

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | KI-Client-Instanz. Jede Implementierung von [IAIWebClient](../../com.aspose.slides/iaiwebclient) kann verwendet werden. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Initialisiert eine neue Instanz von [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) mit dem integrierten [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) und seiner Standardkonfiguration. Der Client verbindet sich mit Asposes eigenem LLM und erfordert keine zusätzliche Konfiguration. Um einen anderen KI-Client zu verwenden, nutzen Sie die Überladung SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Übersetzt eine Präsentation in die angegebene Sprache mithilfe von KI (synchron).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Zielpräsentation |
| language | java.lang.String | Zielsprache

--------------------

Das nachfolgende Beispiel verwendet das Standard-[AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), das durch den parameterlosen SlidesAIAgent()-Konstruktor erstellt wird und sich mit Asposes eigenem LLM verbindet. Um einen anderen KI-Anbieter zu nutzen, Ihr eigenes LLM bereitzustellen oder die Verbindung anzupassen (z. B. durch Bereitstellung Ihres eigenen java.net.HttpURLConnection), übergeben Sie eine [IAIWebClient](../../com.aspose.slides/iaiwebclient)-Implementierung an den SlidesAIAgent(IAIWebClient)-Konstruktor.

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

Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| description | java.lang.String | Das Thema, die Ideen, Zitate oder Textausschnitte. |
| presentationContentAmount | int | Die Menge des Inhalts in der resultierenden Präsentation.

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

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| description | java.lang.String | Das Thema, die Ideen, Zitate oder Textausschnitte. |
| presentationContentAmount | int | Die Menge des Inhalts in der resultierenden Präsentation. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Eine Präsentation, die als Vorlage für Layout und Design verwendet wird und die Standardvorlage ersetzt.

--------------------

Das nachfolgende Beispiel verwendet das Standard-[AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), das durch den parameterlosen SlidesAIAgent()-Konstruktor erstellt wird und sich mit Asposes eigenem LLM verbindet. Um einen anderen KI-Anbieter zu nutzen, Ihr eigenes LLM bereitzustellen oder die Verbindung anzupassen (z. B. durch Bereitstellung Ihres eigenen java.net.HttpURLConnection), übergeben Sie eine [IAIWebClient](../../com.aspose.slides/iaiwebclient)-Implementierung an den SlidesAIAgent(IAIWebClient)-Konstruktor.

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

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)