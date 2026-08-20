---
title: AsposeAIWebClient
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक अंतर्निहित कार्यान्वयन जो Asposes के अपने LLM से जुड़ता है।
type: docs
url: /hi/com.aspose.slides/asposeaiwebclient/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

एक अंतर्निहित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो Aspose के अपने LLM से जुड़ता है। यह डिफ़ॉल्ट क्लाइंट है जो पैरामीटर रहित  SlidesAIAgent()  कंस्ट्रक्टर द्वारा उपयोग किया जाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है, एक बाहरी प्रबंधित  HttpURLConnection  का उपयोग करके। |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो एक कस्टम एंडपॉइंट URL से जुड़ता है। |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो एक कस्टम एंडपॉइंट URL से जुड़ता है, एक बाहरी प्रबंधित  HttpURLConnection  का उपयोग करके। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक वार्तालाप उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है। |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। यह क्लाइंट पैरामीटर रहित  SlidesAIAgent()  कंस्ट्रक्टर द्वारा उपयोग किया जाता है, इसलिए इसे स्पष्ट रूप से बनाना केवल तब आवश्यक होता है जब क्लाइंट को सीधे  SlidesAIAgent(IAIWebClient)  कंस्ट्रक्टर में पास किया जाए।

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है, एक बाहरी प्रबंधित  HttpURLConnection  का उपयोग करके। प्रदान किया गया  HttpURLConnection  इस उदाहरण द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | एक बाहरी प्रबंधित  HttpURLConnection  उदाहरण।

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो एक कस्टम एंडपॉइंट URL से जुड़ता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो; अन्यथा, डिफ़ॉल्ट URL वाले  AsposeAIWebClient()  ओवरलोड का उपयोग करें।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, Aspose.Slides टीम द्वारा प्रदान किया गया।

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो एक कस्टम एंडपॉइंट URL से जुड़ता है, एक बाहरी प्रबंधित  HttpURLConnection  का उपयोग करके। प्रदान किया गया  HttpURLConnection  इस उदाहरण द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो और आप अपना स्वयं का  HttpURLConnection  प्रदान करना चाहते हों; यदि आप केवल अपना HttpURLConnection डिफ़ॉल्ट URL के साथ चाहते हैं, तो  AsposeAIWebClient(HttpURLConnection)  ओवरलोड का उपयोग करें।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, Aspose.Slides टीम द्वारा प्रदान किया गया। |
| httpClient | java.net.HttpURLConnection | एक बाहरी प्रबंधित  HttpURLConnection  उदाहरण।

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किया जाने वाला निर्देश या संदेश।

**रिटर्न:**
java.lang.String - दी गई निर्देश के जवाब में AI मॉडल द्वारा उत्पन्न संदेश।

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक वार्तालाप उदाहरण बनाता है। सामान्य AI कॉल्स के विपरीत, वार्तालाप संपूर्ण संदर्भ को बनाए रखते हैं।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है।