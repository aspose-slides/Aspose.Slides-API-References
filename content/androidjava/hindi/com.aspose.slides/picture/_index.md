---
title: Picture
second_title: Android के लिए Aspose.Slides का Java API रेफ़रेंस
description: एक प्रस्तुति में चित्र का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/picture/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)  
```
public final class Picture implements IPVIObject, ISlidesPicture
```

एक प्रस्तुति में चित्र को दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | एंबेडेड इमेज को प्राप्त करता है या सेट करता है। |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | एंबेडेड इमेज को प्राप्त करता है या सेट करता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड इमेज के URL को प्राप्त करता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | लिंक्ड इमेज के URL को प्राप्त करता है या सेट करता है। |
| [getImageTransform()](#getImageTransform--) | इमेज ट्रांसफ़ॉर्म इफ़ेक्ट्स का संग्रह प्राप्त करता है। |
| [getPresentation()](#getPresentation--) | प्रस्तुति को प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [hashCode()](#hashCode--) | हैश को प्राप्त करता है। |
| [getSlide()](#getSlide--) | चित्र की पैरेंट स्लाइड को प्राप्त करता है। |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को प्राप्त करता है। केवल-पढ़ने योग्य IDOMObject।

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

IPresentationComponent पैरेंट को प्राप्त करता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

एम्बेडेड इमेज को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [IPPImage](../../com.aspose.slides/ippimage)।

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

एम्बेडेड इमेज को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [IPPImage](../../com.aspose.slides/ippimage)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

लिंक्ड इमेज के URL को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य String।

**वापसी:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

लिंक्ड इमेज के URL को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

इमेज ट्रांसफ़ॉर्म इफ़ेक्ट्स का संग्रह प्राप्त करता है। केवल-पढ़ने योग्य [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)।

**वापसी:**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

प्रस्तुति को प्राप्त करता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**  
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए ऑब्जेक्ट। |

**वापसी:**  
boolean - यदि ऑब्जेक्ट समान हैं तो True, अन्यथा False.
### hashCode() {#hashCode--}
```
public int hashCode()
```

हैश को प्राप्त करता है।

**वापसी:**  
int - हैश।
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

चित्र की पैरेंट स्लाइड को प्राप्त करता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)