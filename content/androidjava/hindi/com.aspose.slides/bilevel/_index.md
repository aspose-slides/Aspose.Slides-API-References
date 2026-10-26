---
title: BiLevel
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

एक बाय-लेवल (काला/सफ़ेद) प्रभाव को दर्शाता है। उन इनपुट रंगों जिनकी चमक निर्दिष्ट थ्रेशोल्ड मान से कम है, उन्हें काले में बदल दिया जाता है। जिन इनपुट रंगों की चमक निर्दिष्ट मान से अधिक या बराबर है, उन्हें सफेद में सेट किया जाता है। इस प्रभाव द्वारा अल्फा मान अपरिवर्तित रहते हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | निष्कर्षण लागू करके प्रभावी बाय-लेवल प्रभाव डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [BiLevel](../../com.aspose.slides/bilevel) वर्तमान [BiLevel](../../com.aspose.slides/bilevel) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | विशिष्ट प्रकार के लिए एक हैश फ़ंक्शन के रूप में कार्य करता है। |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

निष्कर्षण लागू करके प्रभावी बाय-लेवल प्रभाव डेटा प्राप्त करता है।

**रिटर्न:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - एक [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata)।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [BiLevel](../../com.aspose.slides/bilevel) वर्तमान [BiLevel](../../com.aspose.slides/bilevel) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [BiLevel](../../com.aspose.slides/bilevel)। |

**रिटर्न:**
boolean - यदि वस्तुएँ समान हों तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

विशिष्ट प्रकार के लिए एक हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान वस्तु के लिए एक हैश कोड।