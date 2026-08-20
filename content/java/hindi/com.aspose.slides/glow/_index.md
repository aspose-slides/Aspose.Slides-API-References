---
title: Glow
second_title: Aspose.Slides for Java API संदर्भ
description: एक Glow प्रभाव को दर्शाता है, जिसमें वस्तु के किनारों के बाहर रंगीन धुंधला रूपरेखा जोड़ी जाती है।
type: docs
url: /hi/com.aspose.slides/glow/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```java
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

एक Glow प्रभाव का प्रतिनिधित्व करता है, जिसमें वस्तु के किनारों के बाहर रंगीन धुंधला रूपरेखा जोड़ी जाती है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | त्रिज्या। |
| [setRadius(double value)](#setRadius-double-) | त्रिज्या। |
| [getColor()](#getColor--) | रंग प्रारूप। |
| [getEffective()](#getEffective--) | विरासत लागू होने पर प्रभावी Glow प्रभाव डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [Glow](../../com.aspose.slides/glow) वर्तमान [Glow](../../com.aspose.slides/glow) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

त्रिज्या। पढ़ने/लिखने योग्य  double ।

**वापसी:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

त्रिज्या। पढ़ने/लिखने योग्य  double ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

रंग प्रारूप। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

विरासत लागू होने पर प्रभावी Glow प्रभाव डेटा प्राप्त करता है।

**वापसी:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - एक [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [Glow](../../com.aspose.slides/glow) वर्तमान [Glow](../../com.aspose.slides/glow) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Glow](../../com.aspose.slides/glow)। |

**वापसी:**
boolean - यदि वस्तुएँ समान हैं तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान वस्तु के लिए एक हैश कोड।