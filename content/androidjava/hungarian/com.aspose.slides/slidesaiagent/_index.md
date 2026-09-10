---
title: SlidesAIAgent
second_title: Aspose.Slides Android számára Java API hivatkozás
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Egy egyedi AI klienssel inicializál egy új példányt a(z) [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) osztályból. |
| [SlidesAIAgent()](#SlidesAIAgent--) | A beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) alapértelmezett konfigurációjával inicializál egy új példányt a(z) [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI-t használva lefordít egy prezentációt a megadott nyelvre (szinkron változat). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Szöveges leírás alapján generál egy prezentációs példányt. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Szöveges leírás alapján generál egy prezentációs példányt. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
``` 
public SlidesAIAgent(IAIWebClient aiClient)
```


Egy egyedi AI klienssel inicializál egy új példányt a(z) [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) osztályból. Ezzel a túlterheléssel megadhatja az AI szolgáltatót, saját LLM-et biztosíthat, vagy testreszabhatja a kapcsolatot (például saját java.net.HttpURLConnection megadásával). Bármely [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás használható. Az alapértelmezett konfigurációval ellátott beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) használatához helyette a SlidesAIAgent() túlterhelést kell használni.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI kliens példány. Bármely [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás használható. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```


A beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) alapértelmezett konfigurációjával inicializál egy új példányt a(z) [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) osztályból. A kliens az Aspose saját LLM-jéhez csatlakozik, és nem igényel további konfigurációt. Ha más AI klienst szeretne használni, akkor a SlidesAIAgent(IAIWebClient) túlterhelést kell használni.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```


Az AI-t használva lefordít egy prezentációt a megadott nyelvre (szinkron változat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Célprezentáció |
| language | java.lang.String | Célnyelv

--------------------

Az alábbi példa az alapértelmezett [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)-t használja, amelyet a paraméter nélküli SlidesAIAgent() konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Ha más AI szolgáltatót szeretne használni, saját LLM-et ad meg, vagy testreszabja a kapcsolatot (például saját java.net.HttpURLConnection megadásával), akkor egy [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítást kell átadni a SlidesAIAgent(IAIWebClient) konstruktorának.

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


Szöveges leírás alapján generál egy prezentációs példányt. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A létrejövő prezentáció tartalmának mennyisége. |

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


Szöveges leírás alapján generál egy prezentációs példányt. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A létrejövő prezentáció tartalmának mennyisége. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Egy prezentáció, amelyet elrendezés és tervezés sablonjaként használ, ezzel helyettesítve az alapértelmezett sablont. |

--------------------

Az alábbi példa az alapértelmezett [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)-t használja, amelyet a paraméter nélküli SlidesAIAgent() konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Ha más AI szolgáltatót szeretne használni, saját LLM-et ad meg, vagy testreszabja a kapcsolatot (például saját java.net.HttpURLConnection megadásával), akkor egy [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítást kell átadni a SlidesAIAgent(IAIWebClient) konstruktorának.

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