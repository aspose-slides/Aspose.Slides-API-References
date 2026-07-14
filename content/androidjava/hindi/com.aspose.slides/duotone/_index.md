---
title: Duotone
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक डुओटोन प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/duotone/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफेस:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

एक डुओटोन प्रभाव का प्रतिनिधित्व करता है। प्रत्येक पिक्सेल के लिए, Color1 और Color2 को रैखिक इंटरपोलेशन के माध्यम से मिलाकर उस पिक्सेल के लिए नया रंग निर्धारित करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getColor1()](#getColor1--) | गहरे पिक्सेल के लिए लक्ष्य रंग प्रारूप लौटाता है। |
| [getColor2()](#getColor2--) | हल्के पिक्सेल के लिए लक्ष्य रंग प्रारूप लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी डुओटोन प्रभाव डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Duotone](../../com.aspose.slides/duotone) वर्तमान [Duotone](../../com.aspose.slides/duotone) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

गहरे पिक्सेल के लिए लक्ष्य रंग प्रारूप लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

हल्के पिक्सेल के लिए लक्ष्य रंग प्रारूप लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी डुओटोन प्रभाव डेटा प्राप्त करता है।

**रिटर्न:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - एक [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata)।

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Duotone](../../com.aspose.slides/duotone) वर्तमान [Duotone](../../com.aspose.slides/duotone) के बराबर है या नहीं।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Duotone](../../com.aspose.slides/duotone)। |

**रिटर्न:**  
boolean - true यदि वस्तुएँ समान हैं; अन्यथा, false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**  
int - वर्तमान वस्तु के लिए एक हैश कोड।