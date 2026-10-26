---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /hi/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | पैराग्राफ की बुलेट प्रकार को लौटाता या सेट करता है, बिना विरासत के। |
| [setType(byte value)](#setType-byte-) | पैराग्राफ की बुलेट प्रकार को लौटाता या सेट करता है, बिना विरासत के। |
| [getChar()](#getChar--) | पैराग्राफ की बुलेट अक्षर को लौटाता या सेट करता है, बिना विरासत के। |
| [setChar(char value)](#setChar-char-) | पैराग्राफ की बुलेट अक्षर को लौटाता या सेट करता है, बिना विरासत के। |
| [getFont()](#getFont--) | पैराग्राफ की बुलेट फ़ॉन्ट को लौटाता या सेट करता है, बिना विरासत के। |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | पैराग्राफ की बुलेट फ़ॉन्ट को लौटाता या सेट करता है, बिना विरासत के। |
| [getHeight()](#getHeight--) | पैराग्राफ की बुलेट ऊँचाई को लौटाता या सेट करता है, बिना विरासत के। |
| [setHeight(float value)](#setHeight-float-) | पैराग्राफ की बुलेट ऊँचाई को लौटाता या सेट करता है, बिना विरासत के। |
| [getColor()](#getColor--) | पैराग्राफ की बुलेट का रंग स्वरूप लौटाता है, बिना विरासत के। |
| [getPicture()](#getPicture--) | पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर को लौटाता है, बिना विरासत के। |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | क्रमांकित बुलेट समूह के लिए इस्तेमाल होने वाला पहला नंबर लौटाता या सेट करता है, बिना विरासत के। |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | क्रमांकित बुलेट समूह के लिए इस्तेमाल होने वाला पहला नंबर लौटाता या सेट करता है, बिना विरासत के। |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | क्रमांकित बुलेट की शैली को लौटाता या सेट करता है, बिना विरासत के। |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | क्रमांकित बुलेट की शैली को लौटाता या सेट करता है, बिना विरासत के। |
| [isBulletHardColor()](#isBulletHardColor--) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [isBulletHardFont()](#isBulletHardFont--) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | बुलेट सक्षम होने पर प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट शून्य-नहीँ शिफ्ट सेट करता है (जैसे PowerPoint पैराग्राफ बुलेट/नंबरिंग सक्षम करने पर करता है)। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### getType() {#getType--}
```
public abstract byte getType()
```

पैराग्राफ की बुलेट प्रकार को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [BulletType](../../com.aspose.slides/bullettype)।

**वापसी:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

पैराग्राफ की बुलेट प्रकार को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [BulletType](../../com.aspose.slides/bullettype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

पैराग्राफ की बुलेट अक्षर को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें char।

**वापसी:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

पैराग्राफ की बुलेट अक्षर को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें char।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

पैराग्राफ की बुलेट फ़ॉन्ट को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**वापसी:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

पैराग्राफ की बुलेट फ़ॉन्ट को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [IFontData](../../com.aspose.slides/ifontdata)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

पैराग्राफ की बुलेट ऊँचाई को लौटाता या सेट करता है, बिना विरासत के। मान Float.NaN निर्धारित करता है कि बुलेट पैराग्राफ के पहले भाग से ऊँचाई विरासत में लेता है। पढ़ें/लिखें float।

**वापसी:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

पैराग्राफ की बुलेट ऊँचाई को लौटाता या सेट करता है, बिना विरासत के। मान Float.NaN निर्धारित करता है कि बुलेट पैराग्राफ के पहले भाग से ऊँचाई विरासत में लेता है। पढ़ें/लिखें float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

पैराग्राफ की बुलेट का रंग स्वरूप लौटाता है, बिना विरासत के। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर को लौटाता है, बिना विरासत के। केवल पढ़ने योग्य [ISlidesPicture](../../com.aspose.slides/islidespicture)।

**वापसी:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

क्रमांकित बुलेट समूह के लिए इस्तेमाल होने वाला पहला नंबर लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें short।

**वापसी:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

क्रमांकित बुलेट समूह के लिए इस्तेमाल होने वाला पहला नंबर लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें short।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

क्रमांकित बुलेट की शैली को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))।

**वापसी:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

क्रमांकित बुलेट की शैली को लौटाता या सेट करता है, बिना विरासत के। पढ़ें/लिखें [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। **NullableBool#True** अगर बुलेट का अपना रंग है और **NullableBool#False** अगर बुलेट रंग को पैराग्राफ के पहले भाग से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

निर्धारित करता है कि बुलेट का अपना रंग है या पैराग्राफ के पहले भाग से विरासत में लेता है। **NullableBool#True** अगर बुलेट का अपना रंग है और **NullableBool#False** अगर बुलेट रंग को पैराग्राफ के पहले भाग से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। **NullableBool#True** अगर बुलेट का अपना फ़ॉन्ट है और **NullableBool#False** अगर बुलेट फ़ॉन्ट को पैराग्राफ के पहले भाग से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या पैराग्राफ के पहले भाग से विरासत में लेता है। **NullableBool#True** अगर बुलेट का अपना फ़ॉन्ट है और **NullableBool#False** अगर बुलेट फ़ॉन्ट को पैराग्राफ के पहले भाग से विरासत में लेता है। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

बुलेट सक्षम होने पर प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट शून्य-नहीँ शिफ्ट सेट करता है (जैसे PowerPoint पैराग्राफ बुलेट/नंबरिंग को सक्षम करने पर करता है)। यदि बुलेट अक्षम हैं तो केवल पैराग्राफ Indent और MarginLeft को रीसेट करता है (जैसे PowerPoint अक्षम करने पर करता है)। शिफ्ट वर्तमान बुलेट संदर्भ - IBulletFormat.Type, .NumberedBulletStyle और पहले भाग की FontHeight - के अनुसार लागू होते हैं। गैर-शून्य शिफ्ट वर्तमान पैराग्राफ के प्रभावी Indent और MarginLeft पर लागू होते हैं (परिणाम मूल्यों को स्थानीय बनाते हैं)।
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी बुलेट फ़ॉर्मेटिंग डेटा प्राप्त करता है।

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

**वापसी:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - एक [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)।