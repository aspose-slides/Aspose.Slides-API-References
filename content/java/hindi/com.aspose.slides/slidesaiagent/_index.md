---
title: SlidesAIAgent
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रेजेंटेशन प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/slidesaiagent/
---
**Inheritance:**  
java.lang.Object  
```
public class SlidesAIAgent
```

प्रेजेंटेशन प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।

## निर्माता

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | कस्टम AI क्लाइंट के साथ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया उदाहरण आरम्भ करता है। |
| [SlidesAIAgent()](#SlidesAIAgent--) | अंतर्निर्मित [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) को उसकी डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ उपयोग करते हुए [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया उदाहरण आरम्भ करता है। |

## विधियां

| मेथड | विवरण |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI का उपयोग करके निर्दिष्ट भाषा में प्रेजेंटेशन का अनुवाद करता है (सिंक्रोनस संस्करण)। |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | पाठ विवरण से एक प्रेजेंटेशन उदाहरण बनाता है। |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | पाठ विवरण से एक प्रेजेंटेशन उदाहरण बनाता है। |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

कस्टम AI क्लाइंट के साथ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया उदाहरण आरम्भ करता है। इस ओवरलोड का उपयोग AI प्रदाता निर्दिष्ट करने, अपना स्वयं का LLM आपूर्ति करने, या कनेक्शन को कस्टमाइज़ करने के लिए किया जा सकता है (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके)। कोई भी [IAIWebClient](../../com.aspose.slides/iaiwebclient) लागू किया जा सकता है। अंतर्निर्मित [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) को उसकी डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ उपयोग करने के लिए, SlidesAIAgent() ओवरलोड का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI क्लाइंट इंस्टेंस। कोई भी [IAIWebClient](../../com.aspose.slides/iaiwebclient) लागू किया जा सकता है। |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

[SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया उदाहरण अंतर्निर्मित [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) को उसकी डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ उपयोग करके आरम्भ करता है। क्लाइंट Aspose के अपने LLM से जुड़ता है और कोई अतिरिक्त कॉन्फ़िगरेशन आवश्यक नहीं है। अलग AI क्लाइंट उपयोग करने के लिए, SlidesAIAgent(IAIWebClient) ओवरलोड का उपयोग करें।

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

AI का उपयोग करके निर्दिष्ट भाषा में प्रेजेंटेशन का अनुवाद करता है (सिंक्रोनस संस्करण)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | लक्षित प्रेजेंटेशन |
| language | java.lang.String | लक्षित भाषा |

--------------------

नीचे दिया गया उदाहरण डिफ़ॉल्ट [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) का उपयोग करता है, जो पैरामीटरलेस SlidesAIAgent() कंस्ट्रक्टर द्वारा बनाया गया है और Aspose के अपने LLM से कनेक्ट होता है। अलग AI प्रदाता उपयोग करने, अपना स्वयं का LLM आपूर्ति करने, या कनेक्शन को कस्टमाइज़ करने के लिए (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके), SlidesAIAgent(IAIWebClient) कंस्ट्रक्टर में एक [IAIWebClient](../../com.aspose.slides/iaiwebclient) लागू पास करें।

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

पाठ विवरण से एक प्रेजेंटेशन उदाहरण बनाता है। आवश्यक भाषा में विषय, विचार, उद्धरण या पाठ अंश प्रदान करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण या पाठ अंश। |
| presentationContentAmount | int | परिणामी प्रेजेंटेशन में सामग्री की मात्रा। |

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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

पाठ विवरण से एक प्रेजेंटेशन उदाहरण बनाता है। आवश्यक भाषा में विषय, विचार, उद्धरण या पाठ अंश प्रदान करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण या पाठ अंश। |
| presentationContentAmount | int | परिणामी प्रेजेंटेशन में सामग्री की मात्रा। |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | लेआउट और डिज़ाइन के लिए टेम्पलेट के रूप में उपयोग किया जाने वाला प्रेजेंटेशन, जो डिफ़ॉल्ट टेम्पलेट को बदलता है। |

--------------------

नीचे दिया गया उदाहरण डिफ़ॉल्ट [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) का उपयोग करता है, जो पैरामीटरलेस SlidesAIAgent() कंस्ट्रक्टर द्वारा बनाया गया है और Aspose के अपने LLM से कनेक्ट होता है। अलग AI प्रदाता उपयोग करने, अपना स्वयं का LLM आपूर्ति करने, या कनेक्शन को कस्टमाइज़ करने के लिए (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके), SlidesAIAgent(IAIWebClient) कंस्ट्रक्टर में एक [IAIWebClient](../../com.aspose.slides/iaiwebclient) लागू पास करें।

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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)