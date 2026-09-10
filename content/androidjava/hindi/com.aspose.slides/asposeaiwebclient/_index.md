---
title: AsposeAIWebClient
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
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

एक अंतर्निहित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो Aspose के अपने LLM से जुड़ता है। यह वह डिफ़ॉल्ट क्लाइंट है जिसका उपयोग पैरामीटर-रहित SlidesAIAgent() कन्स्ट्रक्टर द्वारा किया जाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करके डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो कस्टम एंडपॉइंट URL से जुड़ता है। |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करके कस्टम एंडपॉइंट URL से जुड़ता है। |

## विधियां

| विधि | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक बातचीत का उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है। |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। यह वह क्लाइंट है जिसका उपयोग पैरामीटर-रहित SlidesAIAgent() कन्स्ट्रक्टर द्वारा किया जाता है, इसलिए इसे स्पष्ट रूप से बनाना केवल तब आवश्यक है जब क्लाइंट को सीधे SlidesAIAgent(IAIWebClient) कन्स्ट्रक्टर को पास किया जाता है।

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

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करके डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ता है। प्रदान किया गया HttpURLConnection इस उदाहरण द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**परामी터:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | बाहरी रूप से प्रबंधित HttpURLConnection उदाहरण. |

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

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो कस्टम एंडपॉइंट URL से जुड़ता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो; अन्यथा, डिफ़ॉल्ट URL के साथ AsposeAIWebClient() ओवरलोड का उपयोग करें।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, जो Aspose.Slides टीम द्वारा प्रदान किया गया है। |

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

Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करके कस्टम एंडपॉइंट URL से जुड़ता है। प्रदान किया गया HttpURLConnection इस उदाहरण द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो और आप अपना स्वयं का HttpURLConnection प्रदान करना चाहते हैं; यदि आपको केवल डिफ़ॉल्ट URL के साथ अपना स्वयं का HttpURLConnection चाहिए, तो इसके बजाय AsposeAIWebClient(HttpURLConnection) ओवरलोड का उपयोग करें।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, जो Aspose.Slides टीम द्वारा प्रदान किया गया है। |
| httpClient | java.net.HttpURLConnection | बाहरी रूप से प्रबंधित HttpURLConnection उदाहरण. |

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

AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किया जाने वाला निर्देश या संदेश। |

**वापसी:**
java.lang.String - दिए गए निर्देश के उत्तर में AI मॉडल द्वारा उत्पन्न संदेश।

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक बातचीत का उदाहरण बनाता है। नियमित AI कॉल्स के विपरीत, वार्तालाप संपूर्ण संदर्भ को बरकरार रखता है।

**वापसी:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है।