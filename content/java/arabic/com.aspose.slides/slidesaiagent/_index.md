---
title: SlidesAIAgent
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يوفر ميزات مدعومة بالذكاء الاصطناعي لمعالجة العروض التقديمية.
type: docs
url: /ar/com.aspose.slides/slidesaiagent/
---
**الوراثة:**  
java.lang.Object  
```
public class SlidesAIAgent
```

يوفر ميزات مدعومة بالذكاء الاصطناعي لمعالجة العروض التقديمية.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | ينشئ مثيلاً جديداً من [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) باستخدام عميل ذكاء اصطناعي مخصص. |
| [SlidesAIAgent()](#SlidesAIAgent--) | ينشئ مثيلاً جديداً من [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) باستخدام [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) المدمج مع تكوينه الافتراضي. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | يترجم عرض تقديمي إلى اللغة المحددة باستخدام الذكاء الاصطناعي (النسخة المتزامنة). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | ينشئ مثيلاً من عرض تقديمي من وصف نصي. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | ينشئ مثيلاً من عرض تقديمي من وصف نصي. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

ينشئ مثيلاً جديداً من [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) باستخدام عميل ذكاء اصطناعي مخصص. استخدم هذا التحميل الزائد لتحديد موفر الذكاء الاصطناعي، أو توفير نموذج اللغة الكبير الخاص بك، أو تخصيص الاتصال (على سبيل المثال، عبر توفير java.net.HttpURLConnection الخاص بك). يمكن استخدام أي تنفيذ لـ [IAIWebClient](../../com.aspose.slides/iaiwebclient). لاستخدام [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) المدمج مع تكوينه الافتراضي، استخدم التحميل الزائد SlidesAIAgent() بدلاً من ذلك.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | مثيل عميل الذكاء الاصطناعي. يمكن استخدام أي تنفيذ لـ [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

ينشئ مثيلاً جديداً من [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) باستخدام [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) المدمج مع تكوينه الافتراضي. يتصل العميل بنموذج اللغة الكبير الخاص بـ Aspose ولا يتطلب أي تكوين إضافي. لاستخدام عميل ذكاء اصطناعي مختلف، استخدم التحميل الزائد SlidesAIAgent(IAIWebClient) بدلاً من ذلك.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

يترجم عرض تقديمي إلى اللغة المحددة باستخدام الذكاء الاصطناعي (النسخة المتزامنة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي المستهدف |
| language | java.lang.String | اللغة المستهدفة

--------------------

المثال أدناه يستخدم [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) الافتراضي، الذي يتم إنشاؤه بواسطة المُنشئ SlidesAIAgent() بدون معلمات ويتصل بنموذج اللغة الكبير الخاص بـ Aspose. لاستخدام موفر ذكاء اصطناعي مختلف، أو توفير نموذج لغة كبير خاص بك، أو تخصيص الاتصال (على سبيل المثال، عبر توفير java.net.HttpURLConnection الخاص بك)، مرّر تنفيذ [IAIWebClient](../../com.aspose.slides/iaiwebclient) إلى مُنشئ SlidesAIAgent(IAIWebClient).

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

ينشئ مثيلاً من عرض تقديمي من وصف نصي. قدم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| description | java.lang.String | الموضوع أو الأفكار أو الاقتباسات أو المقاطع النصية. |
| presentationContentAmount | int | كمية المحتوى في العرض التقديمي الناتج. |

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

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

ينشئ مثيلاً من عرض تقديمي من وصف نصي. قدم موضوعًا أو أفكارًا أو اقتباسات أو مقاطع نصية باللغة المطلوبة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| description | java.lang.String | الموضوع أو الأفكار أو الاقتباسات أو المقاطع النصية. |
| presentationContentAmount | int | كمية المحتوى في العرض التقديمي الناتج. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | عرض يُستخدم كقالب للتخطيط والتصميم، بدلاً من القالب الافتراضي. |

--------------------

المثال أدناه يستخدم [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) الافتراضي، الذي يتم إنشاؤه بواسطة المُنشئ SlidesAIAgent() بدون معلمات ويتصل بنموذج اللغة الكبير الخاص بـ Aspose. لاستخدام موفر ذكاء اصطناعي مختلف، أو توفير نموذج لغة كبير خاص بك، أو تخصيص الاتصال (على سبيل المثال، عبر توفير java.net.HttpURLConnection الخاص بك)، مرّر تنفيذ [IAIWebClient](../../com.aspose.slides/iaiwebclient) إلى مُنشئ SlidesAIAgent(IAIWebClient).

```java
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

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)