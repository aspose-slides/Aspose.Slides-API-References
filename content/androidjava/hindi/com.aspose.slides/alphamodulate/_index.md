---
title: AlphaModulate
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक Alpha Modulate प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/alphamodulate/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect  
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

एक Alpha Modulate प्रभाव का प्रतिनिधित्व करता है। प्रभाव अल्फा (अपारदर्शिता) मानों को निश्चित प्रतिशत से गुणा किया जाता है। प्रभाव कंटेनर एक ऐसा प्रभाव निर्दिष्ट करता है जिसमें अल्फा मानों को मोड्यूलेट किया जाता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी Alpha Modulate प्रभाव डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [AlphaModulate](../../com.aspose.slides/alphamodulate) वर्तमान [AlphaModulate](../../com.aspose.slides/alphamodulate) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी Alpha Modulate प्रभाव डेटा प्राप्त करता है।

**रिटर्न:**  
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - एक [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata)।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [AlphaModulate](../../com.aspose.slides/alphamodulate) वर्तमान [AlphaModulate](../../com.aspose.slides/alphamodulate) के बराबर है या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [AlphaModulate](../../com.aspose.slides/alphamodulate)। |

**रिटर्न:**  
boolean - true यदि वस्तुएँ समान हैं; अन्यथा, false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**  
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।