---
title: SlidesAIAgent
second_title: Aspose.Slides for Android via Java API Referansı
description: Sunumları işlemek için AI destekli özellikler sağlar.
type: docs
url: /tr/com.aspose.slides/slidesaiagent/
---
**Kalıtım:**
java.lang.Object
```
public class SlidesAIAgent
```

Sunumları işlemek için AI destekli özellikler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) yeni bir örnek, özel bir AI istemcisiyle başlatır. |
| [SlidesAIAgent()](#SlidesAIAgent--) | [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) yeni bir örnek, yerleşik [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) varsayılan yapılandırmasıyla başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI kullanarak bir sunumu belirtilen dile çevirir (eşzamanlı sürüm). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Metin açıklamasından bir sunum örneği oluşturur. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Metin açıklamasından bir sunum örneği oluşturur. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Özel bir AI istemcisiyle [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) yeni bir örnek başlatır. Bu aşırı yüklemeyi AI sağlayıcısını belirtmek, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak) için kullanın. Herhangi bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması kullanılabilir. Yerleşik [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) varsayılan yapılandırmasıyla kullanmak için SlidesAIAgent() aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI istemci örneği. Herhangi bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması kullanılabilir. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Yerleşik [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) kullanarak [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) yeni bir örnek başlatır ve varsayılan yapılandırmasını kullanır. İstemci, Aspose'un kendi LLM'sine bağlanır ve ek yapılandırma gerektirmez. Farklı bir AI istemcisi kullanmak için SlidesAIAgent(IAIWebClient) aşırı yüklemesini kullanın.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

AI kullanarak bir sunumu belirtilen dile çevirir (eşzamanlı sürüm).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Hedef sunum |
| language | java.lang.String | Hedef dil

--------------------

Aşağıdaki örnek varsayılan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)'yu kullanır; bu, parametresiz SlidesAIAgent() yapıcı tarafından oluşturulur ve Aspose'un kendi LLM'sine bağlanır. Farklı bir AI sağlayıcısı kullanmak, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak) için SlidesAIAgent(IAIWebClient) yapıcısına bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması gönderin.

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
| presentationContentAmount | int | Sonuç sunumdaki içerik miktarı.

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
| presentationContentAmount | int | Sonuç sunumdaki içerik miktarı. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Düzen ve tasarım için şablon olarak kullanılacak bir sunum, varsayılan şablonun yerine geçer.

--------------------

Aşağıdaki örnek varsayılan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)'yi kullanır; bu, parametresiz SlidesAIAgent() yapıcı tarafından oluşturulur ve Aspose'un kendi LLM'sine bağlanır. Farklı bir AI sağlayıcısı kullanmak, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak) için SlidesAIAgent(IAIWebClient) yapıcısına bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulaması gönderin.

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