---
title: SlidesAIAgent
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रेजेंटेशन को प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/slidesaiagent/
---
**विरासत:**
java.lang.Object
```
public class SlidesAIAgent
```

प्रेजेंटेशन को प्रोसेस करने के लिए AI-समर्थित सुविधाएँ प्रदान करता है।
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent निर्माता |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI (सिंक्रोनस संस्करण) का उपयोग करके एक प्रेजेंटेशन को निर्दिष्ट भाषा में अनुवादित करता है। |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | पाठ विवरण से एक प्रेजेंटेशन उदाहरण उत्पन्न करता है। |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | पाठ विवरण से एक प्रेजेंटेशन उदाहरण उत्पन्न करता है। |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent निर्माता

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI क्लाइंट इंस्टेंस |
### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

AI (सिंक्रोनस संस्करण) का उपयोग करके एक प्रेजेंटेशन को निर्दिष्ट भाषा में अनुवादित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | लक्षित प्रेजेंटेशन |
| language | java.lang.String | लक्षित भाषा

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

पाठ विवरण से एक प्रेजेंटेशन उदाहरण उत्पन्न करता है। आवश्यक भाषा में एक विषय, विचार, उद्धरण, या पाठ अंश प्रदान करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण, या पाठ अंश। |
| presentationContentAmount | int | परिणामी प्रेजेंटेशन में सामग्री की मात्रा। |

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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

पाठ विवरण से एक प्रेजेंटेशन उदाहरण उत्पन्न करता है। आवश्यक भाषा में एक विषय, विचार, उद्धरण, या पाठ अंश प्रदान करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण, या पाठ अंश। |
| presentationContentAmount | int | परिणामी प्रेजेंटेशन में सामग्री की मात्रा। |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | लेआउट और डिजाइन के लिए टेम्प्लेट के रूप में उपयोग करने हेतु एक प्रेजेंटेशन, डिफ़ॉल्ट टेम्प्लेट को बदलते हुए। |

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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)