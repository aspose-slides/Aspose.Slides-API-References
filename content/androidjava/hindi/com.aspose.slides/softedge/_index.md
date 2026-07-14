---
title: SoftEdge
second_title: Android के लिए Aspose.Slides, Java API संदर्भ के माध्यम से
description: एक सॉफ्ट एज प्रभाव को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/softedge/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

एक सॉफ्ट एज इफ़ेक्ट को दर्शाता है। आकार के किनारे धुंधले होते हैं, जबकि फॉर्म भराव पर प्रभाव नहीं पड़ता।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | किनारों पर लागू करने के लिए धुंधलापन त्रिज्या निर्दिष्ट करता है। |
| [setRadius(double value)](#setRadius-double-) | किनारों पर लागू करने के लिए धुंधलापन त्रिज्या निर्दिष्ट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी Soft Edge इफ़ेक्ट डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [SoftEdge](../../com.aspose.slides/softedge) वर्तमान [SoftEdge](../../com.aspose.slides/softedge) के समान है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए एक हैश फ़ंक्शन के रूप में कार्य करता है। |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


किनारों पर लागू करने के लिए धुंधलापन त्रिज्या निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


किनारों पर लागू करने के लिए धुंधलापन त्रिज्या निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी Soft Edge इफ़ेक्ट डेटा प्राप्त करता है।

**रिटर्न:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - एक [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate वस्तु लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


parent IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट [SoftEdge](../../com.aspose.slides/softedge) वर्तमान [SoftEdge](../../com.aspose.slides/softedge) के समान है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [SoftEdge](../../com.aspose.slides/softedge)। |

**रिटर्न:**
boolean - true यदि वस्तुएँ समान हों; अन्यथा false।
### hashCode() {#hashCode--}
```
public int hashCode()
```


किसी विशेष प्रकार के लिए एक हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान वस्तु के लिए एक हैश कोड।