---
title: ISlidesPicture
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: प्रस्तुति में एक चित्र का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/islidespicture/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

प्रस्तुति में एक तस्वीर का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImage()](#getImage--) | एंबेडेड इमेज को प्राप्त करता है या सेट करता है। |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | एंबेडेड इमेज को प्राप्त करता है या सेट करता है। |
| [getLinkPathLong()](#getLinkPathLong--) | जुड़ी हुई इमेज के URL को प्राप्त करता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | जुड़ी हुई इमेज के URL को प्राप्त करता है या सेट करता है। |
| [getImageTransform()](#getImageTransform--) | इमेज ट्रांसफ़ॉर्म इफ़ेक्ट्स के संग्रह को प्राप्त करता है। |

### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

एम्बेडेड इमेज को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

एम्बेडेड इमेज को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

जुड़ी हुई इमेज के URL को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**वापसी:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

जुड़ी हुई इमेज के URL को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

इमेज ट्रांसफ़ॉर्म इफ़ेक्ट्स के संग्रह को प्राप्त करता है। केवल-पढ़ने योग्य [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)।

**वापसी:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)