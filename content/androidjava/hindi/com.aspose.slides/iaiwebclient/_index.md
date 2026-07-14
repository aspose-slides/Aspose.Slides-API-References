---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web क्लाइंट इंटरफ़ेस।
type: docs
url: /hi/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web क्लाइंट इंटरफ़ेस। यह इंटरफ़ेस विभिन्न AI भाषा मॉडल को बदलने में सक्षम बनाता है। ऐसी क्लासें जो इस इंटरफ़ेस को लागू करती हैं, उन्हें SlidesAIAgent के साथ उपयोग करने के लिए माना जाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | प्रदान की गई HttpConnection इंस्टेंस का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है। |
| [createConversation()](#createConversation--) | एक बातचीत इंस्टेंस बनाता है। |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

प्रदान की गई HttpConnection इंस्टेंस का उपयोग करके AI मॉडल को एक चैट निर्देश भेजता है और दिए गए निर्देश के लिए प्रतिक्रिया संदेश लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा प्रोसेस किए जाने वाला निर्देश या संदेश। |

**रिटर्न:**
java.lang.String - AI मॉडल द्वारा दिए गए निर्देश के जवाब में उत्पन्न किया गया संदेश।

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

एक बातचीत इंस्टेंस बनाता है। नियमित AI कॉल्स के विपरीत, वार्तालाप पूरी संदर्भ को बनाए रखते हैं।

**रिटर्न:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.