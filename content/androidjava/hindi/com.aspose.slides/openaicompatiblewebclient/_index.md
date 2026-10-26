---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक निर्मित कार्यान्वयन जो निर्दिष्ट बेस URL पर OpenAI-संगत LLM प्रदाता से कनेक्ट करता है।
type: docs
url: /hi/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

एक निर्मित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो निर्दिष्ट बेस URL पर OpenAI-संगत LLM प्रदाता से कनेक्ट करता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है। |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | एक ऐसा OpenAI-संगत वेब क्लाइंट का उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | बाहरी रूप से प्रबंधित HttpURLConnection इंस्टेंस का उपयोग करके AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक वार्तालाप उदाहरण बनाता है। |
| [dispose()](#dispose--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है। |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI-संगत वेब क्लाइंट का एक उदाहरण बनाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-संगत LLM का बेस URL। |
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

एक ऐसा OpenAI-संगत वेब क्लाइंट का उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpURLConnection का उपयोग करता है। प्रदान किया गया HttpURLConnection इस उदाहरण द्वारा नष्ट नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | LLM प्रदाता द्वारा समर्थित मॉडल नाम। |
| apiKey | java.lang.String | API कुंजी (टोकन)। |
| baseUrl | java.lang.String | OpenAI-संगत LLM का बेस URL। |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित HttpURLConnection इंस्टेंस। |
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

बाहरी रूप से प्रबंधित HttpURLConnection इंस्टेंस का उपयोग करके AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किए जाने वाला निर्देश या संदेश। |

**वापसी:**
java.lang.String - दिए गए निर्देश के उत्तर में AI मॉडल द्वारा उत्पन्न संदेश।

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

एक वार्तालाप उदाहरण बनाता है। सामान्य AI कॉल्स के विपरीत, वार्तालाप पूरी संदर्भ को बनाए रखता है।

**वापसी:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### dispose() {#dispose--}
```
public final void dispose()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है।