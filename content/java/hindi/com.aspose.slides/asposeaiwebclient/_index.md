---
title: AsposeAIWebClient
second_title: Aspose.Slides के लिए Java API संदर्भ
description: Aspose के अपने LLM से जुड़ने वाला एक अंतर्निर्मित कार्यान्वयन।
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

Aspose के अपने LLM से जुड़ने वाला एक अंतर्निर्मित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन। यह पैरामीटररहित `SlidesAIAgent()` कन्स्ट्रक्टर द्वारा उपयोग किया जाने वाला डिफ़ॉल्ट क्लाइंट है।

## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | बाहरी रूप से प्रबंधित  HttpClient का उपयोग करके डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | कस्टम एंडपॉइंट URL से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | बाहरी रूप से प्रबंधित  HttpClient का उपयोग करके कस्टम एंडपॉइंट URL से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | एक वार्तालाप उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है। |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

डिफ़ॉल्ट Aspose LLM एंडपॉइंट से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। यह क्लाइंट पैरामीटररहित `SlidesAIAgent()` कन्स्ट्रक्टर द्वारा उपयोग किया जाता है, इसलिए इसे स्पष्ट रूप से बनाने की आवश्यकता केवल तब होती है जब क्लाइंट को सीधे `SlidesAIAgent(IAIWebClient)` कन्स्ट्रक्टर में पास किया जाए।

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

डिफ़ॉल्ट Aspose LLM एंडपॉइंट से बाहरी रूप से प्रबंधित  HttpClient का उपयोग करके जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। प्रदान किया गया  HttpClient  इस उदाहरण द्वारा नष्ट नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित  HttpClient  उदाहरण। |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

कस्टम एंडपॉइंट URL से जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो; अन्यथा डिफ़ॉल्ट URL के साथ `AsposeAIWebClient()` ओवरलोड का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, Aspose.Slides टीम द्वारा प्रदान किया गया। |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

कस्टम एंडपॉइंट URL से बाहरी रूप से प्रबंधित  HttpClient का उपयोग करके जुड़ने वाला Aspose AI वेब क्लाइंट का एक उदाहरण बनाता है। प्रदान किया गया  HttpClient  इस उदाहरण द्वारा नष्ट नहीं किया जाता और कॉलर के स्वामित्व में रहता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो और आप अपना स्वयं का  HttpClient  प्रदान करना चाहते हों; यदि आपको केवल अपना HttpClient डिफ़ॉल्ट URL के साथ चाहिए, तो `AsposeAIWebClient(HttpClient)` ओवरलोड का उपयोग करें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM का एंडपॉइंट URL, Aspose.Slides टीम द्वारा प्रदान किया गया। |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित  HttpClient  उदाहरण। |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

प्रदान किए गए HttpConnection उदाहरण का उपयोग करके AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String |  |
**रिटर्न:**  
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक वार्तालाप उदाहरण बनाता है। सामान्य AI कॉलों के विपरीत, वार्तालाप पूरे संदर्भ को बनाए रखते हैं।

**रिटर्न:**  
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है।