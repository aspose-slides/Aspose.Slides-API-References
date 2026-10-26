---
title: OpenAIWebClient
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक अंतर्निहित कार्यान्वयन जो OpenAI API से जुड़ता है।
type: docs
url: /hi/com.aspose.slides/openaiwebclient/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

एक अंतर्निहित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो OpenAI API से जुड़ता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है। |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है जो बाहरी रूप से प्रबंधित  HttpClient  का उपयोग करता है। |
## मेथड

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | एक वार्तालाप इंस्टेंस बनाता है। |
| [close()](#close--) | इस इंस्टेंस द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है। |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभावित मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी। |
| organizationId | java.lang.String | संगठन ID (वैकल्पिक)। |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है जो बाहरी रूप से प्रबंधित  HttpClient  का उपयोग करता है। प्रदान किया गया  HttpClient  इस इंस्टेंस द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभावित मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी |
| organizationId | java.lang.String | संगठन ID (वैकल्पिक) |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित HttpClient इंस्टेंस |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

प्रदान किए गए HttpConnection इंस्टेंस का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| instruction | java.lang.String |  |

**रिटर्न:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक वार्तालाप इंस्टेंस बनाता है। सामान्य AI कॉलों के विपरीत, वार्तालाप पूरी संदर्भ को बनाए रखते हैं।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) इंस्टेंस।
### close() {#close--}
```
public final void close()
```

इस इंस्टेंस द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है।