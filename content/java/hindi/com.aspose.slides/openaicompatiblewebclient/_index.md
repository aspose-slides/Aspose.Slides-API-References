---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API संदर्भ
description: एक अंतर्निर्मित कार्यान्वयन जो एक निर्दिष्ट बेस URL पर OpenAI-समर्थित LLM प्रदाता से जुड़ता है।
type: docs
url: /hi/com.aspose.slides/openaicompatiblewebclient/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

एक अंतर्निर्मित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो एक निर्दिष्ट बेस URL पर OpenAI-समर्थित LLM प्रदाता से जुड़ता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI-समर्थित वेब क्लाइंट का एक उदाहरण बनाता है। |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI-समर्थित वेब क्लाइंट का एक उदाहरण बनाता है जो एक बाहरी रूप से प्रबंधित  HttpURLConnection  का उपयोग करता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | बाहरी रूप से प्रबंधित HttpURLConnection उदाहरण का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक संवाद उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है। |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI-समर्थित वेब क्लाइंट का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल का नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-समर्थित LLM का बेस URL। |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

OpenAI-समर्थित वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित  HttpURLConnection  का उपयोग करता है। प्रदान किया गया HttpURLConnection इस उदाहरण द्वारा नष्ट नहीं किया जाता और कॉलर द्वारा ही स्वामित्व में रहता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल का नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-समर्थित LLM का बेस URL। |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित  HttpURLConnection  उदाहरण। |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

बाहरी रूप से प्रबंधित HttpURLConnection उदाहरण का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा संसाधित करने के लिए निर्देश या संदेश। |

**वापसी:**
java.lang.String - AI मॉडल द्वारा दिए गए निर्देश के उत्तर में उत्पन्न किया गया संदेश।

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक संवाद उदाहरण बनाता है। नियमित AI कॉल्स के विपरीत, संवाद संपूर्ण संदर्भ को बनाए रखते हैं।

**वापसी:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है।