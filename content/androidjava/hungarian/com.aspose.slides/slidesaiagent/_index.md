---
title: SlidesAIAgent
second_title: Aspose.Slides for Android Java API hivatkozás
description: AI-alapú funkciókat biztosít a prezentációk feldolgozásához.
type: docs
url: /hu/com.aspose.slides/slidesaiagent/
---
**Öröklés:**
java.lang.Object
```
public class SlidesAIAgent
```

AI-alapú funkciókat biztosít a prezentációk feldolgozásához.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent konstruktor |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI segítségével lefordít egy prezentációt a megadott nyelvre (szinkron változat). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generál egy prezentáció példányt egy szöveges leírásból. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generál egy prezentáció példányt egy szöveges leírásból. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent konstruktor

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI kliens példány |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


AI segítségével lefordít egy prezentációt a megadott nyelvre (szinkron változat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Cél prezentáció |
| language | java.lang.String | Cél nyelv

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


Generál egy prezentáció példányt egy szöveges leírásból. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A tartalom mennyisége a létrehozott prezentációban.

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

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Generál egy prezentáció példányt egy szöveges leírásból. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A tartalom mennyisége a létrehozott prezentációban. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Egy prezentáció, amelyet sablonként használ az elrendezéshez és a tervezéshez, felváltva az alapértelmezett sablont.

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

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)