---
title: IAIWebClient
second_title: Aspose.Slides के लिए Java API संदर्भ
description: AI वेब क्लाइंट इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI वेब क्लाइंट इंटरफ़ेस। यह इंटरफ़ेस विभिन्न AI भाषा मॉडलों को बदलने में सक्षम बनाता है। इस इंटरफ़ेस को लागू करने वाली कक्षाओं का उपयोग SlidesAIAgent के साथ मिलकर किया जाना चाहिए।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


प्रदान किए गए HttpConnection इंस्टेंस का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किए जाने के लिए निर्देश या संदेश। |

**रिटर्न:**
java.lang.String - दिए गए निर्देश के जवाब में AI मॉडल द्वारा उत्पन्न संदेश।

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


एक संवाद इंस्टेंस बनाता है। नियमित AI कॉल्स के विपरीत, संवाद पूरी संदर्भ को बनाए रखता है।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - एक [IAIConversation](../../com.aspose.slides/iaiconversation) इंस्टेंस।