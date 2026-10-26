---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /hi/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame के फ़ॉर्मेटिंग गुणधर्म शामिल हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | टेक्स्ट की शैली को लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपर मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे मार्जिन (प्वाइंट) को लौटाता या सेट करता है। |
| [getWrapText()](#getWrapText--) | यदि टेक्स्ट TextFrame की सीमाओं पर लिपटा हुआ है तो true। |
| [setWrapText(byte value)](#setWrapText-byte-) | यदि टेक्स्ट TextFrame की सीमाओं पर लिपटा हुआ है तो true। |
| [getAnchoringType()](#getAnchoringType--) | TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। |
| [getCenterText()](#getCenterText--) | यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केन्द्रित होना चाहिए। |
| [setCenterText(byte value)](#setCenterText-byte-) | यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केन्द्रित होना चाहिए। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट के ऑटोफ़िट मोड को लौटाता या सेट करता है। |
| [setAutofitType(byte value)](#setAutofitType-byte-) | टेक्स्ट के ऑटोफ़िट मोड को लौटाता या सेट करता है। |
| [getColumnCount()](#getColumnCount--) | टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता या सेट करता है। |
| [setColumnCount(int value)](#setColumnCount-int-) | टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता या सेट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (प्वाइंट में) को लौटाता या सेट करता है। |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (प्वाइंट में) को लौटाता या सेट करता है। |
| [getThreeDFormat()](#getThreeDFormat--) | टेक्स्ट के 3डी इफ़ेक्ट गुणधर्मों का प्रतिनिधित्व करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। |
| [getKeepTextFlat()](#getKeepTextFlat--) | टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता या सेट करता है। |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता या सेट करता है। |
| [getRotationAngle()](#getRotationAngle--) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू किए जा रहे कस्टम रोटेशन को निर्दिष्ट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू किए जा रहे कस्टम रोटेशन को निर्दिष्ट करता है। |
| [getTransform()](#getTransform--) | टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। |
| [setTransform(byte value)](#setTransform-byte-) | टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। |
| [getEffective()](#getEffective--) | इनहेरिटेंस लागू होते हुए प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

टेक्स्ट की शैली को लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame में बाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame में बाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame में दाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame में दाएँ मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame में ऊपर मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame में ऊपर मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame में नीचे मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame में नीचे मार्जिन (प्वाइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

यदि टेक्स्ट TextFrame की सीमाओं पर लिपटा हुआ है तो true। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

यदि टेक्स्ट TextFrame की सीमाओं पर लिपटा हुआ है तो true। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**रिटर्न:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केन्द्रित होना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केन्द्रित होना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल से सम्मिलित दृश्य टेक्स्ट रोटेशन का परिणाम प्राप्त होता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**रिटर्न:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल से सम्मिलित दृश्य टेक्स्ट रोटेशन का परिणाम प्राप्त होता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

टेक्स्ट के ऑटोफ़िट मोड को लौटाता या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype)।

**रिटर्न:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

टेक्स्ट के ऑटोफ़िट मोड को लौटाता या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता या सेट करता है। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा मान शून्य पर सेट हो जाएगा। मान 0 अनिर्धारित मान को दर्शाता है। पढ़ें/लिखें int।

**रिटर्न:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता या सेट करता है। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा मान शून्य पर सेट हो जाएगा। मान 0 अनिर्धारित मान को दर्शाता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (प्वाइंट में) को लौटाता या सेट करता है। यह केवल तब लागू होना चाहिए जब 1 से अधिक कॉलम मौजूद हों। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा मान शून्य पर सेट हो जाएगा। पढ़ें/लिखें double।

**रिटर्न:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (प्वाइंट में) को लौटाता या सेट करता है। यह केवल तब लागू होना चाहिए जब 1 से अधिक कॉलम मौजूद हों। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा मान शून्य पर सेट हो जाएगा। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

ThreeDFormat ऑब्जेक्ट को लौटाता है जो टेक्स्ट के 3d इफ़ेक्ट गुणधर्म दर्शाता है। केवल-पढ़ने योग्य [IThreeDFormat](../../com.aspose.slides/ithreedformat)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // टेक्स्ट ट्रांसफ़ॉर्मेशन सेट करें
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // एक्सट्रूज़न सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // कंटूर सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // गहराई सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // मैटेरियल सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // लाइटिंग सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // कैमरा प्रकार सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता या सेट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता या सेट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू किए जा रहे कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं है, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट है, तो यह शेप से स्वतंत्र रूप से लागू होता है। अर्थात शेप में अतिरिक्त रोटेशन हो सकता है जबकि टेक्स्ट पर भी अलग रोटेशन लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType में पूर्वनिर्धारित वर्टिकल प्रकार से सम्मिलित दृश्य टेक्स्ट रोटेशन का परिणाम प्राप्त होता है। पढ़ें/लिखें float।

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**रिटर्न:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू किए जा रहे कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं है, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट है, तो यह शेप से स्वतंत्र रूप से लागू होता है। अर्थात शेप में अतिरिक्त रोटेशन हो सकता है जबकि टेक्स्ट पर भी अलग रोटेशन लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType में पूर्वनिर्धारित वर्टिकल प्रकार से सम्मिलित दृश्य टेक्स्ट रोटेशन का परिणाम प्राप्त होता है। पढ़ें/लिखें float।

--------------------

> ```
> उस स्थिति पर विचार करें जहाँ किसी आकार पर 90 डिग्री घड़ी की दिशा में घुमाव लागू किया गया हो. 
>  इसके अतिरिक्त, टेक्स्ट बॉडी पर स्वयं -90 डिग्री 
>  प्रतिचक्र दिशा में लागू किया गया है। फिर परिणामस्वरूप आकार ऐसा दिखेगा कि
>  वह घुमा हुआ है, लेकिन उसके भीतर का टेक्स्ट ऐसा लगेगा जैसे उसे बिल्कुल भी घुमाया न गया हो। 
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype)।

**रिटर्न:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

इनहेरिटेंस लागू होते हुए प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).