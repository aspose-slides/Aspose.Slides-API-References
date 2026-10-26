---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: प्रस्तुति में एक छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

प्रेजेंटेशन में एक छवि का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | छवि डेटा की एक प्रति लौटाता है। |
| [getImage()](#getImage--) | छवि की एक प्रति लौटाता है। |
| [getSvgImage()](#getSvgImage--) | ISvgImage ऑब्जेक्ट को लौटाता है या सेट करता है [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage ऑब्जेक्ट को लौटाता है या सेट करता है [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | छवि डेटा को बदलता है। |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | छवि को बदलता है। |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | छवि को बदलता है। |
| [getContentType()](#getContentType--) | छवि का MIME टाइप लौटाता है, जो \#getBinaryData.getBinaryData में एन्कोड किया गया है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई लौटाता है। |
| [getX()](#getX--) | छवि का X-ऑफ़सेट लौटाता है। |
| [getY()](#getY--) | छवि का Y-ऑफ़सेट लौटाता है। |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

छवि डेटा की एक प्रति लौटाता है। केवल-पढ़ने योग्य byte[]।

**वापसी:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

छवि की एक प्रति लौटाता है। केवल-पढ़ने योग्य \#getImage.getImage।

**वापसी:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

ISvgImage ऑब्जेक्ट को लौटाता है या सेट करता है [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

यह मान दर्शाता है कि यह छवि SVG से बनाई गई है।

**वापसी:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

ISvgImage ऑब्जेक्ट को लौटाता है या सेट करता है [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

यह मान दर्शाता है कि यह छवि SVG से बनाई गई है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

छवि डेटा को बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImageData | byte[] | नई छवि का डेटा। |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

छवि को बदलता है। ध्यान दें: जब छवि मेटाफाइल होती है - यह रास्टराइज़ किया जाएगा। इसके बजाय replaceImage(byte[]) का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | नया चित्र। |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

छवि को बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | नया IPPImage। |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

छवि का MIME टाइप लौटाता है, जो \#getBinaryData.getBinaryData में एन्कोड किया गया है। केवल-पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

छवि की चौड़ाई लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

छवि की ऊँचाई लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getX() {#getX--}
```
public abstract int getX()
```

छवि का X-ऑफ़सेट लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getY() {#getY--}
```
public abstract int getY()
```

छवि का Y-ऑफ़सेट लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int