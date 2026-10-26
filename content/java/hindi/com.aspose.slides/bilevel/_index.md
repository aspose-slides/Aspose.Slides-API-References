---
title: BiLevel
second_title: Java के लिए Aspose.Slides API संदर्भ
description: एक बाय-लेवल काला/सफ़ेद प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/bilevel/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

एक बाय-लेवल (काला/सफ़ेद) प्रभाव का प्रतिनिधित्व करता है। इनपुट रंग जिनकी चमक निर्दिष्ट थ्रेशहोल्ड मान से कम है, उन्हें काले में बदल दिया जाता है। जिन इनपुट रंगों की चमक निर्दिष्ट मान के बराबर या अधिक है, उन्हें सफेद सेट किया जाता है। अल्फा प्रभाव मान इस प्रभाव से प्रभावित नहीं होते।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत लागू किए गए प्रभावी बाय-लेवल डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [BiLevel](../../com.aspose.slides/bilevel) वर्तमान [BiLevel](../../com.aspose.slides/bilevel) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

विरासत लागू किए गए प्रभावी बाय-लेवल डेटा प्राप्त करता है।

**वापसी:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - एक [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [BiLevel](../../com.aspose.slides/bilevel) वर्तमान [BiLevel](../../com.aspose.slides/bilevel) के बराबर है या नहीं।

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [BiLevel](../../com.aspose.slides/bilevel)। |

**वापसी:**
boolean - true यदि वस्तुएँ समान हैं; अन्यथा, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - एक हैश कोड वर्तमान वस्तु के लिए।