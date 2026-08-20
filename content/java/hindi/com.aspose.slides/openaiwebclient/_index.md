---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API संदर्भ
description: एक अंतर्निहित कार्यान्वयन जो OpenAI API से जुड़ता है।
type: docs
url: /hi/com.aspose.slides/openaiwebclient/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

एक अंतर्निहित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो OpenAI API से जुड़ता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है। |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | एक बाहरी रूप से प्रबंधित HttpClient का उपयोग करने वाला OpenAI वेब क्लाइंट का इंस्टेंस बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | एक वार्तालाप इंस्टेंस बनाता है। |
| [close()](#close--) | इस इंस्टैंस द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है। |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI वेब क्लाइंट का एक इंस्टेंस बनाता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
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
``` 

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

एक बाहरी रूप से प्रबंधित HttpClient का उपयोग करने वाला OpenAI वेब क्लाइंट का इंस्टेंस बनाता है। प्रदान किया गया HttpClient इस इंस्टैंस द्वारा डिस्पोज़ नहीं किया जाता और कॉलर के द्वारा मालिकाना बना रहता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
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
``` 

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

एक प्रदान किए गए HttpConnection इंस्टेंस का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String |  |

**रिटर्न:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक वार्तालाप इंस्टेंस बनाता है। नियमित AI कॉल्स के विपरीत, वार्तालाप पूरी संदर्भ को रखता है।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) इंस्टेंस।

### close() {#close--}
```
public final void close()
```

इस इंस्टैंस द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है।