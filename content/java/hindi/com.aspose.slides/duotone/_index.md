---
title: Duotone
second_title: Aspose.Slides for Java API संदर्भ
description: एक ड्युटोन प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/duotone/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू किए गए इंटरफेस:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

एक ड्युटोन इफ़ेक्ट को दर्शाता है। प्रत्येक पिक्सेल के लिए, Color1 और Color2 को रैखिक अंतःस्थापन के माध्यम से मिलाकर उस पिक्सेल का नया रंग निर्धारित करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColor1()](#getColor1--) | डार्क पिक्सेल्स के लिए लक्ष्य रंग फ़ॉर्मेट लौटाता है। |
| [getColor2()](#getColor2--) | लाइट पिक्सेल्स के लिए लक्ष्य रंग फ़ॉर्मेट लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी ड्युटोन इफ़ेक्ट डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Duotone](../../com.aspose.slides/duotone) वर्तमान [Duotone](../../com.aspose.slides/duotone) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


डार्क पिक्सेल्स के लिए लक्ष्य रंग फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


लाइट पिक्सेल्स के लिए लक्ष्य रंग फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


विरासत लागू करके प्रभावी ड्युटोन इफ़ेक्ट डेटा प्राप्त करता है।

**वापसी:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट [Duotone](../../com.aspose.slides/duotone) वर्तमान [Duotone](../../com.aspose.slides/duotone) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) को तुलना करने के लिए। |

**वापसी:**
boolean - यदि ऑब्जेक्ट समान हैं तो true; अन्यथा false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।