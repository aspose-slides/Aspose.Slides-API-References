---
title: PPImage
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रस्तुति में एक छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ppimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

एक प्रस्तुति में छवि को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | एक छवि के डेटा की प्रति लौटाता है। |
| [getImage()](#getImage--) | एक छवि की प्रति लौटाता है। |
| [getSvgImage()](#getSvgImage--) | ISvgImage वस्तु [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है। |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage वस्तु [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है। |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | छवि डेटा को बदलता है। |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | छवि डेटा को बदलता है। |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | छवि डेटा को बदलता है। |
| [getContentType()](#getContentType--) | एक छवि का MIME प्रकार लौटाता है, जो BinaryData (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। |
| [getWidth()](#getWidth--) | एक छवि की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | एक छवि की ऊँचाई लौटाता है। |
| [getX()](#getX--) | एक छवि का X-ऑफसेट लौटाता है। |
| [getY()](#getY--) | एक छवि का Y-ऑफसेट लौटाता है। |
| [hashCode()](#hashCode--) | एक छवि का हैश कोड लौटाता है। |
| [dispose()](#dispose--) | ऑब्जेक्ट को नष्ट करता है। |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

एक छवि के डेटा की प्रति लौटाता है। केवल-पढ़ने योग्य  byte[] ।

**वापसी:**
byte[] - बाइट्स की एरे

### getImage() {#getImage--}
```
public final IImage getImage()
```

एक छवि की प्रति लौटाता है। केवल-पढ़ने योग्य [IImage](../../com.aspose.slides/iimage)।

**वापसी:**
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

ISvgImage वस्तु [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है।

--------------------

यह मान दर्शाता है कि यह छवि SVG से बनाई गई है।

**वापसी:**
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

ISvgImage वस्तु [ISvgImage](../../com.aspose.slides/isvgimage) को लौटाता या सेट करता है।

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

छवि डेटा को बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImageData | byte[] | नई छवि का डेटा। |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

छवि डेटा को बदलता है। ध्यान दें: जब Image एक मेटाफाइल है - इसे रास्टराइज़ किया जाएगा। इसके बजाय ReplaceImage(byte[]) का उपयोग करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | नई छवि। |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

छवि डेटा को बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | नया IPPImage। |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

एक छवि का MIME प्रकार लौटाता है, जो BinaryData (\#getBinaryData.getBinaryData) में एन्कोड किया गया है। केवल-पढ़ने योग्य String।

**वापसी:**
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

एक छवि की चौड़ाई लौटाता है। केवल-पढ़ने योग्य  int ।

**वापसी:**
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

एक छवि की ऊँचाई लौटाता है। केवल-पढ़ने योग्य  int ।

**वापसी:**
int

### getX() {#getX--}
```
public final int getX()
```

एक छवि का X-ऑफसेट लौटाता है। केवल-पढ़ने योग्य  int ।

**वापसी:**
int

### getY() {#getY--}
```
public final int getY()
```

एक छवि का Y-ऑफसेट लौटाता है। केवल-पढ़ने योग्य  int ।

**वापसी:**
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक छवि का हैश कोड लौटाता है।

**वापसी:**
int - Hash code.

### dispose() {#dispose--}
```
public final void dispose()
```

ऑब्जेक्ट को नष्ट करता है।