---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API Referansı
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Yeni bir [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) örneğini özel bir AI istemcisiyle başlatır. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Yeni bir [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) örneğini dahili [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) kullanarak varsayılan yapılandırmasıyla başlatır. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Bir sunumu belirlenen dile AI kullanarak çevirir (senkron sürüm). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Metin açıklamasından bir sunum örneği oluşturur. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Metin açıklamasından bir sunum örneği oluşturur. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Yeni bir [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) örneğini özel bir AI istemcisiyle başlatır. Bu aşırı yüklemeyi AI sağlayıcısını belirtmek, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek için kullanın (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak). [IAIWebClient](../../com.aspose.slides/iaiwebclient)‘nin herhangi bir uygulaması kullanılabilir. Dahili [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)'yi varsayılan yapılandırmasıyla kullanmak için SlidesAIAgent() aşırı yüklemesini kullanın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI istemci örneği. [IAIWebClient](../../com.aspose.slides/iaiwebclient)‘nin herhangi bir uygulaması kullanılabilir. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Yeni bir [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) örneğini dahili [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) kullanarak varsayılan yapılandırmasıyla başlatır. İstemci Aspose'un kendi LLM'sine bağlanır ve ek yapılandırma gerektirmez. Farklı bir AI istemcisi kullanmak için SlidesAIAgent(IAIWebClient) aşırı yüklemesini kullanın.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Bir sunumu belirlenen dile AI kullanarak çevirir (senkron sürüm).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Hedef sunum |
| language | java.lang.String | Hedef dil |

--------------------

Aşağıdaki örnek, parametresiz SlidesAIAgent() yapıcısı tarafından oluşturulan ve Aspose'un kendi LLM'sine bağlanan varsayılan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)‘yi kullanır. Farklı bir AI sağlayıcısı kullanmak, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak) için bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulamasını SlidesAIAgent(IAIWebClient) yapıcısına geçirin.

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

Metin açıklamasından bir sunum örneği oluşturur. Gereken dilde bir konu, fikir, alıntı ya da metin parçacığı sağlayın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| description | java.lang.String | Konu, fikirler, alıntılar veya metin parçacıkları. |
| presentationContentAmount | int | Ortaya çıkan sunumdaki içerik miktarı. |

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

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Metin açıklamasından bir sunum örneği oluşturur. Gereken dilde bir konu, fikir, alıntı ya da metin parçacığı sağlayın.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| description | java.lang.String | Konu, fikirler, alıntılar veya metin parçacıkları. |
| presentationContentAmount | int | Ortaya çıkan sunumdaki içerik miktarı. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Düzen ve tasarım için bir şablon olarak kullanılacak sunum, varsayılan şablonun yerine geçer. |

--------------------

Aşağıdaki örnek, parametresiz SlidesAIAgent() yapıcısı tarafından oluşturulan ve Aspose'un kendi LLM'sine bağlanan varsayılan [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)‘yi kullanır. Farklı bir AI sağlayıcısı kullanmak, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi java.net.HttpURLConnection'ınızı sağlayarak) için bir [IAIWebClient](../../com.aspose.slides/iaiwebclient) uygulamasını SlidesAIAgent(IAIWebClient) yapıcısına geçirin.

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

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)