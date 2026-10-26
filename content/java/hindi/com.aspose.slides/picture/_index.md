---
title: Picture
second_title: Aspose.Slides के लिए जावा API संदर्भ
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

एक प्रस्तुति में चित्र का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | एम्बेडेड छवि को लौटाता है या सेट करता है। |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | एम्बेडेड छवि को लौटाता है या सेट करता है। |
| [getLinkPathLong()](#getLinkPathLong--) | जुड़ी हुई छवि के URL को लौटाता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | जुड़ी हुई छवि के URL को लौटाता है या सेट करता है। |
| [getImageTransform()](#getImageTransform--) | इमेज ट्रांसफ़ॉर्म प्रभावों का संग्रह लौटाता है। |
| [getPresentation()](#getPresentation--) | प्रेज़ेंटेशन लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [hashCode()](#hashCode--) | हैश लौटाता है। |
| [getSlide()](#getSlide--) | चित्र की पैरेंट स्लाइड लौटाता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**रिटर्न:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent पैरेंट लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**रिटर्न:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

एम्बेडेड छवि को लौटाता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

**रिटर्न:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

एम्बेडेड छवि को लौटाता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

जुड़ी हुई छवि के URL को लौटाता है या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

जुड़ी हुई छवि के URL को लौटाता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

इमेज ट्रांसफ़ॉर्म प्रभावों का संग्रह लौटाता है। केवल पढ़ने योग्य [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)।

**रिटर्न:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
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

**रिटर्न:**
boolean - यदि ऑब्जेक्ट समान हैं तो true, अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

हैश लौटाता है।

**रिटर्न:**
int - हैश।

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

चित्र की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)