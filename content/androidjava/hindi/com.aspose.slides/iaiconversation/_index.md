---
title: IAIConversation
second_title: Aspose.Slides के लिए Android via Java API रेफ़रेंस
description: एक वार्तालाप उदाहरण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

एक वार्तालाप उदाहरण का प्रतिनिधित्व करता है। सामान्य AI कॉल्स के विपरीत, वार्तालाप पूरे संदर्भ को बनाए रखते हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | पूरे संदर्भ को शामिल करते हुए वार्तालाप अनुरोध संदेश भेजता है और प्रतिक्रिया लौटाता है। |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

पूरे संदर्भ को शामिल करते हुए वार्तालाप अनुरोध संदेश भेजता है और प्रतिक्रिया लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा संसाधित करने के लिए निर्देश या संदेश। |

**वापसी:**  
java.lang.String - AI मॉडल द्वारा दिए गए निर्देश के प्रति प्रतिक्रिया में वार्तालाप संदर्भ के भीतर उत्पन्न संदेश।