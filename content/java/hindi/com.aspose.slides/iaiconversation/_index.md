---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: एक वार्ता उदाहरण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

एक वार्ता उदाहरण का प्रतिनिधित्व करता है। नियमित AI कॉल्स के विपरीत, वार्तालाप पूरी संदर्भ को बरकरार रखते हैं।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | वार्तालाप अनुरोध संदेश पूरे संदर्भ सहित भेजता है और प्रतिक्रिया लौटाता है। |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

वार्तालाप अनुरोध संदेश पूरे संदर्भ सहित भेजता है और प्रतिक्रिया लौटाता है।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| instruction | java.lang.String | AI मॉडल द्वारा संसाधित किया जाने वाला निर्देश या संदेश। |

**वापसी मान:**
java.lang.String - वार्तालाप संदर्भ में दी गई निर्देश के उत्तर में AI मॉडल द्वारा उत्पन्न संदेश।