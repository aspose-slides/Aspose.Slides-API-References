---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: पैराग्राफ बुलेट फ़ॉर्मैटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

पैराग्राफ बुलेट फ़ॉर्मैटिंग गुणों का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | बिना विरासत के पैराग्राफ की बुलेट प्रकार को लौटाता है या सेट करता है। |
| [setType(byte value)](#setType-byte-) | बिना विरासत के पैराग्राफ की बुलेट प्रकार को लौटाता है या सेट करता है। |
| [getChar()](#getChar--) | बिना विरासत के पैराग्राफ के बुलेट अक्षर को लौटाता है या सेट करता है। |
| [setChar(char value)](#setChar-char-) | बिना विरासत के पैराग्राफ के बुलेट अक्षर को लौटाता है या सेट करता है। |
| [getFont()](#getFont--) | बिना विरासत के पैराग्राफ के बुलेट फ़ॉन्ट को लौटाता है या सेट करता है। |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | बिना विरासत के पैराग्राफ के बुलेट फ़ॉन्ट को लौटाता है या सेट करता है। |
| [getHeight()](#getHeight--) | बिना विरासत के पैराग्राफ के बुलेट ऊँचाई को लौटाता है या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | बिना विरासत के पैराग्राफ के बुलेट ऊँচाई को लौटाता है या सेट करता है। |
| [getColor()](#getColor--) | बिना विरासत के पैराग्राफ के बुलेट के रंग फ़ॉर्मेट को लौटाता है। |
| [getPicture()](#getPicture--) | बिना विरासत के पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर लौटाता है। |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | बिना विरासत के क्रमांकित बुलेट समूह के लिए उपयोग किया गया पहला नंबर लौटाता है या सेट करता है। |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | बिना विरासत के क्रमांकित बुलेट समूह के लिए उपयोग किया गया पहला नंबर लौटाता है या सेट करता है। |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | बिना विरासत के क्रमांकित बुलेट की शैली को लौटाता है या सेट करता है। |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | बिना विरासत के क्रमांकित बुलेट की शैली को लौटाता है या सेट करता है। |
| [isBulletHardColor()](#isBulletHardColor--) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। |
| [isBulletHardFont()](#isBulletHardFont--) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | जब बुलेट सक्षम हो तो प्रभावी पैराग्राफ इंडेंट और मार्जिनलेफ़्ट के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है (जैसे PowerPoint में पैराग्राफ बुलेट/नंबरिंग सक्षम करने पर करता है)। |
| [getEffective()](#getEffective--) | विरासत लागू होने पर प्रभावी बुलेट फ़ॉर्मैटिंग डेटा प्राप्त करता है। |

### getType() {#getType--}
```
public abstract byte getType()
```

बिना विरासत के पैराग्राफ की बुलेट प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [BulletType](../../com.aspose.slides/bullettype).

**रिटर्न्स:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

बिना विरासत के पैराग्राफ की बुलेट प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [BulletType](../../com.aspose.slides/bullettype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

बिना विरासत के पैराग्राफ के बुलेट अक्षर को लौटाता है या सेट करता है। पढ़ें/लिखें char.

**रिटर्न्स:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

बिना विरासत के पैराग्राफ के बुलेट अक्षर को लौटाता है या सेट करता है। पढ़ें/लिखें char.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

बिना विरासत के पैराग्राफ के बुलेट फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**रिटर्न्स:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

बिना विरासत के पैराग्राफ के बुलेट फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

बिना विरासत के पैराग्राफ के बुलेट ऊँचाई को लौटाता है या सेट करता है। मान Float.NaN निर्धारित करता है कि बुलेट पैराग्राफ के पहले हिस्से से ऊँचाई विरासत में लेता है। पढ़ें/लिखें float.

**रिटर्न्स:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

बिना विरासत के पैराग्राफ के बुलेट ऊँचाई को लौटाता है या सेट करता है। मान Float.NaN निर्धारित करता है कि बुलेट पैराग्राफ के पहले हिस्से से ऊँचाई विरासत में लेता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

बिना विरासत के पैराग्राफ के बुलेट के रंग फ़ॉर्मेट को लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न्स:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

बिना विरासत के पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर लौटाता है। केवल-पढ़ने योग्य [ISlidesPicture](../../com.aspose.slides/islidespicture).

**रिटर्न्स:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

बिना विरासत के क्रमांकित बुलेट समूह के लिए उपयोग किया गया पहला नंबर लौटाता है या सेट करता है। पढ़ें/लिखें short.

**रिटर्न्स:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

बिना विरासत के क्रमांकित बुलेट समूह के लिए उपयोग किया गया पहला नंबर लौटाता है या सेट करता है। पढ़ें/लिखें short.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

बिना विरासत के क्रमांकित बुलेट की शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**रिटर्न्स:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

बिना विरासत के क्रमांकित बुलेट की शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। **NullableBool\#True** यदि बुलेट का अपना रंग है और **NullableBool\#False** यदि बुलेट रंग को पैराग्राफ के पहले हिस्से से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न्स:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। **NullableBool\#True** यदि बुलेट का अपना रंग है और **NullableBool\#False** यदि बुलेट रंग को पैराग्राफ के पहले हिस्से से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। **NullableBool\#True** यदि बुलेट का अपना फ़ॉन्ट है और **NullableBool\#False** यदि बुलेट फ़ॉन्ट को पैराग्राफ के पहले हिस्से से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न्स:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले हिस्से से विरासत में लेता है। **NullableBool\#True** यदि बुलेट का अपना फ़ॉन्ट है और **NullableBool\#False** यदि बुलेट फ़ॉन्ट को पैराग्राफ के पहले हिस्से से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

जब बुलेट सक्षम हो तो प्रभावी पैराग्राफ इंडेंट और मार्जिनलेफ़्ट के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है (जैसे PowerPoint में पैराग्राफ बुलेट/नंबरिंग सक्षम करने पर करता है)। यदि बुलेट निष्क्रिय हो तो केवल पैराग्राफ इंडेंट और मार्जिनलेफ़्ट को रीसेट करता है (जैसे PowerPoint में पैराग्राफ बुलेट/नंबरिंग निष्क्रिय करने पर करता है)। शिफ्ट वर्तमान बुलेट संदर्भ - IBulletFormat.Type, .NumberedBulletStyle और पहले हिस्से के फ़ॉन्ट ऊँचाई - के अनुसार लागू होते हैं। गैर-शून्य इंडेंट शिफ्ट वर्तमान पैराग्राफ के प्रभावी इंडेंट और मार्जिनलेफ़्ट पर लागू होते हैं (परिणाम मान स्थानीय मान बनते हैं)।

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

विरासत लागू होने पर प्रभावी बुलेट फ़ॉर्मैटिंग डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न्स:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).