---
title: ISlidesPicture
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रस्तुति में एक चित्र का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/islidespicture/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

प्रस्तुति में एक चित्र का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImage()](#getImage--) | एम्बेडेड छवि को प्राप्त करता है या सेट करता है। |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | एम्बेडेड छवि को प्राप्त करता है या सेट करता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड छवि के URL को प्राप्त करता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | लिंक्ड छवि के URL को प्राप्त करता है या सेट करता है। |
| [getImageTransform()](#getImageTransform--) | छवि ट्रांसफ़ॉर्म इफ़ेक्ट्स का संग्रह लौटाता है। |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

एम्बेडेड छवि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage).

**रिटर्न्स:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

एम्बेडेड छवि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

लिंक्ड छवि के URL को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न्स:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

लिंक्ड छवि के URL को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

छवि ट्रांसफ़ॉर्म इफ़ेक्ट्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**रिटर्न्स:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)