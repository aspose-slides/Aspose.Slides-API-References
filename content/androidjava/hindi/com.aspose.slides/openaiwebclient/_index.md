---
title: OpenAIWebClient
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: बिल्ट-इन हल्का OpenAI वेब क्लाइंट
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

बिल्ट-इन हल्का OpenAI वेब क्लाइंट
## कंस्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI Web client का एक उदाहरण बनाता है। |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI Web client का एक उदाहरण बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | बाहरी रूप से प्रबंधित  instance का उपयोग करके AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक वार्तालाप instance बनाता है। |
| [close()](#close--) | इस instance द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है। |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


OpenAI Web client का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभावित मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी |
| organizationId | java.lang.String | संगठन ID (वैकल्पिक) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


OpenAI Web client का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| model | java.lang.String | OpenAI भाषा मॉडल। संभावित मान: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API कुंजी |
| organizationId | java.lang.String | संगठन ID (वैकल्पिक) |
| httpClient | java.net.HttpURLConnection | एक बाहरी रूप से प्रबंधित HttpURLConnection instance। |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


बाहरी रूप से प्रबंधित  instance का उपयोग करके AI मॉडल को चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किए जाने वाला निर्देश या संदेश |

**रिटर्न:**
java.lang.String - दिए गए निर्देश के लिए AI मॉडल द्वारा उत्पन्न संदेश।

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


एक वार्तालाप instance बनाता है। नियमित AI कॉल्स के विपरीत, वार्तालाप पूरे संदर्भ को बनाए रखते हैं।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) instance।

### close() {#close--}
```
public final void close()
```


इस instance द्वारा उपयोग किए गए संसाधनों को रिलीज़ करता है।