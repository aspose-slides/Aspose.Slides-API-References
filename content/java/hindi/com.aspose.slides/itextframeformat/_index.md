---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /hi/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame की स्वरूपण गुणों को सम्मिलित करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | टेक्स्ट की शैली लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | एक TextFrame में बाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | एक TextFrame में बाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | एक TextFrame में दाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | एक TextFrame में दाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | एक TextFrame में ऊपर मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | एक TextFrame में ऊपर मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | एक TextFrame में नीचे मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | एक TextFrame में नीचे मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। |
| [getWrapText()](#getWrapText--) | यदि टेक्स्ट TextFrame की सीमाओं पर रैप किया गया है तो सत्य। |
| [setWrapText(byte value)](#setWrapText-byte-) | यदि टेक्स्ट TextFrame की सीमाओं पर रैप किया गया है तो सत्य। |
| [getAnchoringType()](#getAnchoringType--) | एक TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | एक TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। |
| [getCenterText()](#getCenterText--) | यदि NullableBool.True हो तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित होना चाहिए। |
| [setCenterText(byte value)](#setCenterText-byte-) | यदि NullableBool.True हो तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित होना चाहिए। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट का ऑटोफिट मोड लौटाता है या सेट करता है। |
| [setAutofitType(byte value)](#setAutofitType-byte-) | टेक्स्ट का ऑटोफिट मोड लौटाता है या सेट करता है। |
| [getColumnCount()](#getColumnCount--) | टेक्स्ट क्षेत्र में स्तम्भों की संख्या लौटाता है या सेट करता है। |
| [setColumnCount(int value)](#setColumnCount-int-) | टेक्स्ट क्षेत्र में स्तम्भों की संख्या लौटाता है या सेट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है या सेट करता है। |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है या सेट करता है। |
| [getThreeDFormat()](#getThreeDFormat--) | टेक्स्ट के 3D प्रभाव गुणों का प्रतिनिधित्व करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। |
| [getKeepTextFlat()](#getKeepTextFlat--) | टेक्स्ट को पूरी तरह 3D दृश्य से बाहर रखने को लौटाता है या सेट करता है। |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | टेक्स्ट को पूरी तरह 3D दृश्य से बाहर रखने को लौटाता है या सेट करता है। |
| [getRotationAngle()](#getRotationAngle--) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन निर्दिष्ट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन निर्दिष्ट करता है। |
| [getTransform()](#getTransform--) | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। |
| [setTransform(byte value)](#setTransform-byte-) | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी टेक्स्ट फ्रेम स्वरूपण डेटा प्राप्त करता है। |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

एक TextFrame में बाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**रिटर्न:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

एक TextFrame में बाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

एक TextFrame में दाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**रिटर्न:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

एक TextFrame में दाएँ मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

एक TextFrame में ऊपर मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**रिटर्न:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

एक TextFrame में ऊपर मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

एक TextFrame में नीचे मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**रिटर्न:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

एक TextFrame में नीचे मार्जिन (पॉइंट्स) को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

यदि टेक्स्ट TextFrame की सीमाओं पर रैप किया गया है तो सत्य। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

यदि टेक्स्ट TextFrame की सीमाओं पर रैप किया गया है तो सत्य। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

एक TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype)।

**रिटर्न:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

एक TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

यदि NullableBool.True हो तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित होना चाहिए। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

यदि NullableBool.True हो तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित होना चाहिए। पढ़ने-लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल के आधार पर दृश्य टेक्स्ट रोटेशन का सारांशित मान लौटाता है। पढ़ने-लिखने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**रिटर्न:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल के आधार पर दृश्य टेक्स्ट रोटेशन का सारांशित मान लौटाता है। पढ़ने-लिखने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

टेक्स्ट का ऑटोफिट मोड लौटाता है या सेट करता है। पढ़ने-लिखने योग्य [TextAutofitType](../../com.aspose.slides/textautofittype)।

**रिटर्न:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

टेक्स्ट का ऑटोफिट मोड लौटाता है या सेट करता है। पढ़ने-लिखने योग्य [TextAutofitType](../../com.aspose.slides/textautofittype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

टेक्स्ट क्षेत्र में स्तम्भों की संख्या लौटाता है या सेट करता है। यह मान सकारात्मक संख्या होना आवश्यक है; अन्यथा शून्य सेट किया जाएगा। मान 0 अपरिभाषित मान दर्शाता है। पढ़ने-लिखने योग्य int।

**रिटर्न:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

टेक्स्ट क्षेत्र में स्तम्भों की संख्या लौटाता है या सेट करता है। यह मान सकारात्मक संख्या होना आवश्यक है; अन्यथा शून्य सेट किया जाएगा। मान 0 अपरिभाषित मान दर्शाता है। पढ़ने-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है या सेट करता है। यह केवल तभी लागू होना चाहिए जब 1 से अधिक कॉलम हों। यह मान सकारात्मक संख्या होना आवश्यक है; अन्यथा शून्य सेट किया जाएगा। पढ़ने-लिखने योग्य double।

**रिटर्न:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है या सेट करता है। यह केवल तभी लागू होना चाहिए जब 1 से अधिक कॉलम हों। यह मान सकारात्मक संख्या होना आवश्यक है; अन्यथा शून्य सेट किया जाएगा। पढ़ने-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

टेक्स्ट के 3D प्रभाव गुणों का प्रतिनिधित्व करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IThreeDFormat](../../com.aspose.slides/ithreedformat)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // टेक्स्ट ट्रांसफ़ॉर्मेशन सेट करें
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // एक्स्ट्रूज़न सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // कंटूर सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // गहराई सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // सामग्री सेट करें
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

टेक्स्ट को पूरी तरह 3D दृश्य से बाहर रखने को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

टेक्स्ट को पूरी तरह 3D दृश्य से बाहर रखने को लौटाता है या सेट करता है। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट किया गया, तो यह शेप से स्वतंत्र रूप से लागू होता है। यह शेप के अतिरिक्त टेक्स्ट पर भी रोटेशन लागू कर सकता है। इस प्रॉपर्टी और TextVerticalType में निर्धारित ऊर्ध्वाधर प्रकार से सारांशित दृश्य टेक्स्ट रोटेशन का मान लौटाता है। पढ़ने-लिखने योग्य float।

--------------------

> ```
> विचार करें कि एक आकार पर 90 डिग्री घड़ी की दिशा में घुमाव लागू किया गया है। 
>  इसके अतिरिक्त, पाठ बॉड़ी स्वयं पर -90 डिग्री घड़ी की उल्टी दिशा में घुमाव लागू किया गया है। 
>  तब परिणामी आकार घुमाया हुआ दिखाई देगा, लेकिन उसके भीतर का पाठ ऐसे दिखेगा जैसे वह बिल्कुल भी घुमाया न गया हो।
> ```

**रिटर्न:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट किया गया, तो यह शेप से स्वतंत्र रूप से लागू होता है। यह शेप के अतिरिक्त टेक्स्ट पर भी रोटेशन लागू कर सकता है। इस प्रॉपर्टी और TextVerticalType में निर्धारित ऊर्ध्वाधर प्रकार से सारांशित दृश्य टेक्स्ट रोटेशन का मान लौटाता है। पढ़ने-लिखने योग्य float।

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [TextShapeType](../../com.aspose.slides/textshapetype)।

**रिटर्न:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [TextShapeType](../../com.aspose.slides/textshapetype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

विरासत लागू करके प्रभावी टेक्स्ट फ्रेम स्वरूपण डेटा प्राप्त करता है।

**रिटर्न:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).