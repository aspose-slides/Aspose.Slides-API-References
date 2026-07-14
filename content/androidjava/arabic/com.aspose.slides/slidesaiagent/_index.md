---
title: SlidesAIAgent
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة جافا
description: يوفر ميزات مدعومة بالذكاء الاصطناعي لمعالجة العروض التقديمية.
type: docs
url: /ar/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
الوراثة:
java.lang.Object
```
public class SlidesAIAgent
```

يوفر ميزات مدعومة بالذكاء الاصطناعي لمعالجة العروض التقديمية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | يترجم عرضًا تقديميًا إلى اللغة المحددة باستخدام الذكاء الاصطناعي (الإصدار المتزامن). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | ينشئ نسخة عرض تقديمي من وصف نصي. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | ينشئ نسخة عرض تقديمي من وصف نصي. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

منشئ SlidesAIAgent

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | مثيل عميل الذكاء الاصطناعي |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

يترجم عرضًا تقديميًا إلى اللغة المحددة باستخدام الذكاء الاصطناعي (الإصدار المتزامن).

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الهدف |
| language | java.lang.String | اللغة الهدف

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

ينشئ نسخة عرض تقديمي من وصف نصي. قدِّم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| description | java.lang.String | الموضوع أو الأفكار أو الاقتباسات أو المقاطع النصية. |
| presentationContentAmount | int | كمية المحتوى في العرض التقديمي الناتج.

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

**Returns:**
القيمة المرجعة:
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

ينشئ نسخة عرض تقديمي من وصف نصي. قدِّم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| description | java.lang.String | الموضوع أو الأفكار أو الاقتباسات أو المقاطع النصية. |
| presentationContentAmount | int | كمية المحتوى في العرض التقديمي الناتج. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | عرض تقديمي لاستخدامه كقالب لتنسيق وتصميم الشرائح، بدلاً من القالب الافتراضي.

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

**Returns:**
القيمة المرجعة:
[IPresentation](../../com.aspose.slides/ipresentation)