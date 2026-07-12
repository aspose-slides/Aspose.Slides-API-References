---
title: SlidesAIAgent
second_title: Aspose.Slides for Android Java API Referansı aracılığıyla
description: Sunumları işlemek için yapay zeka destekli özellikler sağlar.
type: docs
url: /tr/com.aspose.slides/slidesaiagent/
---
**Kalıtım:**
java.lang.Object
```
public class SlidesAIAgent
```

Sunumları işlemek için yapay zeka destekli özellikler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent yapıcı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Bir sunumu, AI kullanarak belirtilen dile çevirir (eşzamanlı sürüm). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Metin açıklamasından bir sunum örneği oluşturur. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Metin açıklamasından bir sunum örneği oluşturur. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent yapıcı

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI istemci örneği |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Bir sunumu, AI kullanarak belirtilen dile çevirir (eşzamanlı sürüm).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Hedef sunum |
| language | java.lang.String | Hedef dil

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


Metin açıklamasından bir sunum örneği oluşturur. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| description | java.lang.String | Konu, fikir, alıntı veya metin parçacıkları. |
| presentationContentAmount | int | Oluşturulan sunumdaki içerik miktarı.

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

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Metin açıklamasından bir sunum örneği oluşturur. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| description | java.lang.String | Konu, fikir, alıntı veya metin parçacıkları. |
| presentationContentAmount | int | Oluşturulan sunumdaki içerik miktarı. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Düzen ve tasarım için şablon olarak kullanılacak, varsayılan şablonu değiştiren bir sunum.

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

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)