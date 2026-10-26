---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API संदर्भ
description: प्रेज़ेंटेशन प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/slidesaiagent/
---
**विरासत:**  
java.lang.Object  
```
public class SlidesAIAgent
```

प्रेजेंटेशन को प्रोसेस करने के लिए AI-संचालित सुविधाएँ प्रदान करता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | एक कस्टम AI क्लाइंट के साथ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का एक नया इंस्टेंस प्रारंभ करता है। |
| [SlidesAIAgent()](#SlidesAIAgent--) | डिफ़ॉल्ट कॉन्फ़िगरेशन वाले बिल्ट-इन [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) का उपयोग करके [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का एक नया इंस्टेंस प्रारंभ करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI (सिंक्रोनस संस्करण) का उपयोग करके प्रेजेंटेशन को निर्दिष्ट भाषा में अनुवाद करता है। |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | पाठ विवरण से प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | पाठ विवरण से प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

एक कस्टम AI क्लाइंट के साथ [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया इंस्टेंस प्रारंभ करता है। इस ओवरलोड का उपयोग AI प्रोवाइडर निर्दिष्ट करने, अपना स्वयं का LLM प्रदान करने, या कनेक्शन को कस्टमाइज़ करने (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके) के लिए करें। [IAIWebClient](../../com.aspose.slides/iaiwebclient) का कोई भी कार्यान्वयन उपयोग किया जा सकता है। बिल्ट-इन [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) को उसके डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ उपयोग करने के लिए, इसके बजाय SlidesAIAgent() ओवरलोड का प्रयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI क्लाइंट इंस्टेंस। [IAIWebClient](../../com.aspose.slides/iaiwebclient) का कोई भी कार्यान्वयन उपयोग किया जा सकता है। |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

बिल्ट-इन [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) को उसके डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ उपयोग करके [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) का नया इंस्टेंस प्रारंभ करता है। क्लाइंट Aspose के स्वयं के LLM से कनेक्ट होता है और कोई अतिरिक्त कॉन्फ़िगरेशन नहीं चाहिए। अलग AI क्लाइंट का उपयोग करने के लिए, इसके बजाय SlidesAIAgent(IAIWebClient) ओवरलोड का प्रयोग करें।

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

AI (सिंक्रोनस संस्करण) का उपयोग करके प्रेजेंटेशन को निर्दिष्ट भाषा में अनुवाद करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | लक्ष्य प्रेजेंटेशन |
| language | java.lang.String | लक्ष्य भाषा |

--------------------

नीचे दिया गया उदाहरण डिफ़ॉल्ट [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) का उपयोग करता है, जिसे पैरामीटरलेस SlidesAIAgent() कन्स्ट्रक्टर द्वारा बनाया जाता है और Aspose के स्वयं के LLM से कनेक्ट होता है। अलग AI प्रोवाइडर का उपयोग करने, अपना स्वयं का LLM प्रदान करने, या कनेक्शन को कस्टमाइज़ करने (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके) के लिए, SlidesAIAgent(IAIWebClient) कन्स्ट्रक्टर को एक [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन पास करें।

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

पाठ विवरण से प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। आवश्यक भाषा में विषय, विचार, उद्धरण, या पाठ अंश प्रदान करें।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण, या पाठ अंश। |
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

**वापसी मान:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

पाठ विवरण से प्रेजेंटेशन इंस्टेंस उत्पन्न करता है। आवश्यक भाषा में विषय, विचार, उद्धरण, या पाठ अंश प्रदान करें।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| description | java.lang.String | विषय, विचार, उद्धरण, या पाठ अंश। |
| presentationContentAmount | int | परिणामी प्रेजेंटेशन में सामग्री की मात्रा। |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | लेआउट और डिज़ाइन के लिए टेम्प्लेट के रूप में उपयोग करने हेतु प्रेजेंटेशन, जो डिफ़ॉल्ट टेम्प्लेट को बदलता है। |

--------------------

नीचे दिया गया उदाहरण डिफ़ॉल्ट [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) का उपयोग करता है, जिसे पैरामीटरलेस SlidesAIAgent() कन्स्ट्रक्टर द्वारा बनाया जाता है और Aspose के स्वयं के LLM से कनेक्ट होता है। अलग AI प्रोवाइडर का उपयोग करने, अपना स्वयं का LLM प्रदान करने, या कनेक्शन को कस्टमाइज़ करने (उदाहरण के लिए, अपना स्वयं का java.net.HttpURLConnection प्रदान करके) के लिए, SlidesAIAgent(IAIWebClient) कन्स्ट्रक्टर को एक [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन पास करें।

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

**वापसी मान:**  
[IPresentation](../../com.aspose.slides/ipresentation)