---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक बिल्ट-इन इम्प्लीमेंटेशन जो निर्दिष्ट बेस URL पर OpenAI-संगत LLM प्रदाता से कनेक्ट होता है।
type: docs
url: /hi/com.aspose.slides/openaicompatiblewebclient/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

एक बिल्ट-इन [IAIWebClient](../../com.aspose.slides/iaiwebclient) इम्प्लीमेंटेशन जो निर्दिष्ट बेस URL पर OpenAI-संगत LLM प्रदाता से कनेक्ट करता है।  

## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | वर्णन |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है। |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | बाहरी रूप से प्रबंधित HttpClient का उपयोग करने वाला OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है। |

## मेथड्स

| मेथड | वर्णन |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | एक वार्ता (conversation) का उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है। |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल का नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-संगत LLM का बेस URL। |
```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

बाहरी रूप से प्रबंधित HttpClient का उपयोग करने वाला OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है। प्रदान किया गया HttpClient इस उदाहरण द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल का नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-संगत LLM का बेस URL। |
| httpClient | java.net.HttpURLConnection | बाहरी रूप से प्रबंधित HttpClient उदाहरण। |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| instruction | java.lang.String |  |
**रिटर्न:**  
java.lang.String

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

एक वार्ता (conversation) का उदाहरण बनाता है। नियमित AI कॉलों के विपरीत, वार्ताएँ पूरे संदर्भ को बरकरार रखती हैं।

**रिटर्न:**  
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है।