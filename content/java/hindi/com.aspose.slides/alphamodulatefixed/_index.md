---
title: AlphaModulateFixed
second_title: Aspose.Slides for Java API संदर्भ
description: एक Alpha Modulate Fixed इफ़ेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/alphamodulatefixed/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफेस:**  
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect  
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

एक Alpha Modulate Fixed इफ़ेक्ट का प्रतिनिधित्व करता है। इफ़ेक्ट अल्फा (अपारदर्शिता) मान को एक निश्चित प्रतिशत से गुणा किया जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAmount()](#getAmount--) | Returns an amount of effect in percents. |
| [setAmount(float value)](#setAmount-float-) | Returns an amount of effect in percents. |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate Fixed effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) is equal to the current [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getAmount() {#getAmount--}
```
public final float getAmount()
```

प्रति शतांश में इफ़ेक्ट की मात्रा लौटाता है। पढ़ने/लिखने योग्य फ्लोट।

**रिटर्न:**
float

### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

प्रति शतांश में इफ़ेक्ट की मात्रा लौटाता है। पढ़ने/लिखने योग्य फ्लोट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

विरासत लागू होने पर प्रभावी Alpha Modulate Fixed इफ़ेक्ट डेटा प्राप्त करता है।

**रिटर्न:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - एक [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata)।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) वर्तमान [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)। |

**रिटर्न:**
boolean - true यदि ऑब्जेक्ट समान हैं; अन्यथा, false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।