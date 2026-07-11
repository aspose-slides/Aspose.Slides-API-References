---
title: OpenAIWebClient
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक अंतर्निहित कार्यान्वयन जो OpenAI API से जुड़ता है।
type: docs
url: /hi/com.aspose.slides/openaiwebclient/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफेस:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

एक अंतर्निहित [IAIWebClient](../../com.aspose.slides/iaiwebclient) कार्यान्वयन जो OpenAI API से जुड़ता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI वेब क्लाइंट का एक उदाहरण बनाता है। |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpClient का उपयोग करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | एक वार्तालाप उदाहरण बनाता है। |
| [close()](#close--) | इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है। |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI वेब क्लाइंट का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभव मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी। |
| organizationId | java.lang.String | संस्था ID (वैकल्पिक)। |

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

OpenAI वेब क्लाइंट का एक उदाहरण बनाता है जो बाहरी रूप से प्रबंधित HttpClient का उपयोग करता है। प्रदान किया गया HttpClient इस उदाहरण द्वारा नष्ट नहीं किया जाता और कॉलर के स्वामित्व में रहता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभव मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी |
| organizationId | java.lang.String | संस्था ID (वैकल्पिक) |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित HttpClient उदाहरण |

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

प्रदान किए गए HttpConnection उदाहरण का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String |  |

**वापसी:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

एक वार्तालाप उदाहरण बनाता है। नियमित AI कॉलों के विपरीत, वार्तालाप पूरे संदर्भ को बनाए रखते हैं।

**वापसी:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) उदाहरण।

### close() {#close--}
```
public final void close()
```

इस उदाहरण द्वारा उपयोग किए गए संसाधनों को मुक्त करता है।