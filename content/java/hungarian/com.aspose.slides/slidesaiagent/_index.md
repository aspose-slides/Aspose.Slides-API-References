---
title: SlidesAIAgent
second_title: Aspose.Slides Java API hivatkozás
description: AI-alapú funkciókat biztosít a prezentációk feldolgozásához.
type: docs
url: /hu/com.aspose.slides/slidesaiagent/
---
**Öröklés:**
java.lang.Object
```
public class SlidesAIAgent
```

AI-alapú funkciókat biztosít prezentációk feldolgozásához.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Egy új [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) példányt inicializál egyedi AI klienssel. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Egy új [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) példányt inicializál a beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) alapértelmezett konfigurációjával. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Egy prezentációt a megadott nyelvre fordít AI segítségével (szinkron verzió). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Egy prezentációpéldányt generál egy szöveges leírásból. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Egy prezentációpéldányt generál egy szöveges leírásból. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Egy új [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) példányt inicializál egyedi AI klienssel. Ezt a túlterhelést használja az AI szolgáltató megadásához, saját LLM biztosításához vagy a kapcsolat testreszabásához (például saját java.net.HttpURLConnection megadásával). Bármely [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás használható. A beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) alapértelmezett konfigurációjával való használathoz használja a SlidesAIAgent() túlterhelést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI kliens példány. Bármely [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás használható. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Egy új [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) példányt inicializál a beépített [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) alapértelmezett konfigurációjával. A kliens az Aspose saját LLM-jéhez csatlakozik, és nem igényel további konfigurációt. Egy másik AI kliens használatához használja a SlidesAIAgent(IAIWebClient) túlterhelést.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Egy prezentációt a megadott nyelvre fordít AI segítségével (szinkron verzió).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Célprezentáció |
| language | java.lang.String | Cél nyelv

--------------------

Az alábbi példa az alapértelmezett [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)-t használja, amelyet a paraméter nélküli SlidesAIAgent() konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Egy másik AI szolgáltató, saját LLM vagy a kapcsolat testreszabásához (például saját java.net.HttpURLConnection megadásával) adjon meg egy [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítást a SlidesAIAgent(IAIWebClient) konstruktorhoz.

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

Egy prezentációpéldányt generál egy szöveges leírásból. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A tartalom mennyisége a létrehozandó prezentációban.

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

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Egy prezentációpéldányt generál egy szöveges leírásból. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| description | java.lang.String | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentationContentAmount | int | A tartalom mennyisége a létrehozandó prezentációban. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Egy prezentáció, amelyet sablonként használ a layout és a dizájn számára, lecserélve az alapértelmezett sablont.

--------------------

Az alábbi példa az alapértelmezett [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)-t használja, amelyet a paraméter nélküli SlidesAIAgent() konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Egy másik AI szolgáltató, saját LLM vagy a kapcsolat testreszabásához (például saját java.net.HttpURLConnection megadásával) adjon meg egy [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítást a SlidesAIAgent(IAIWebClient) konstruktorhoz.

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

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)