---
title: PPImage
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति में एक छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ppimage/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

प्रस्तुति में एक छवि का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | छवि के डेटा की प्रतिलिपि लौटाता है। |
| [getImage()](#getImage--) | छवि की प्रतिलिपि लौटाता है। |
| [getSvgImage()](#getSvgImage--) | ISvgImage ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है। |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है। |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | छवि डेटा को प्रतिस्थापित करता है। |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | छवि डेटा को प्रतिस्थापित करता है। |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | छवि डेटा को प्रतिस्थापित करता है। |
| [getContentType()](#getContentType--) | छवि का MIME प्रकार लौटाता है, जो BinaryData (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई लौटाता है। |
| [getX()](#getX--) | छवि का X-ऑफ़सेट लौटाता है। |
| [getY()](#getY--) | छवि का Y-ऑफ़सेट लौटाता है। |
| [hashCode()](#hashCode--) | छवि का हैश कोड लौटाता है। |
| [dispose()](#dispose--) | ऑब्जेक्ट को नष्ट करता है। |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

छवि के डेटा की प्रतिलिपि लौटाता है। केवल-पढ़ने योग्य  byte[]।

**वापसी:**
byte[] - बाइट्स का ऐरे
### getImage() {#getImage--}
```
public final IImage getImage()
```

छवि की प्रतिलिपि लौटाता है। केवल-पढ़ने योग्य [IImage](../../com.aspose.slides/iimage)।

**वापसी:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

ISvgImage ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है।

--------------------

यह मान दर्शाता है कि यह छवि SVG से बनाई गई है।

**वापसी:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

ISvgImage ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है।

--------------------

यह मान दर्शाता है कि यह छवि SVG से बनाई गई है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

छवि डेटा को प्रतिस्थापित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImageData | byte[] | नई छवि का डेटा। |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

छवि डेटा को प्रतिस्थापित करता है। ध्यान दें: जब छवि मेटाफाइल होती है - तो इसे रास्टर किया जाएगा। इसके बजाय ReplaceImage(byte[]) का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | नई छवि। |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

छवि डेटा को प्रतिस्थापित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | नया IPPImage। |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

छवि का MIME प्रकार लौटाता है, जो BinaryData (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल-pढ़ने योग्य String।

**वापसी:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

छवि की चौड़ाई लौटाता है। केवल-pढ़ने योग्य  int।

**वापसी:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

छवि की ऊँचाई लौटाता है। केवल-pढ़ने योग्य  int।

**वापसी:**
int
### getX() {#getX--}
```
public final int getX()
```

छवि का X-ऑफ़सेट लौटाता है। केवल-pढ़ने योग्य  int।

**वापसी:**
int
### getY() {#getY--}
```
public final int getY()
```

छवि का Y-ऑफ़सेट लौटाता है। केवल-pढ़ने योग्य  int।

**वापसी:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

छवि का हैश कोड लौटाता है।

**वापसी:**
int - हैश कोड।
### dispose() {#dispose--}
```
public final void dispose()
```

ऑब्जेक्ट को नष्ट करता है।