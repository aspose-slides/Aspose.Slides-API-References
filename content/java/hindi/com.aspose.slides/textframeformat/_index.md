---
title: TextFrameFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: TextFrames के formatTextFrameFormatting गुणों को सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/textframeformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

TextFrame के formatTextFrameFormatting गुणों को सम्मिलित करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | नई [TextFrameFormat](../../com.aspose.slides/textframeformat) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | टेक्स्ट की स्टाइल लौटाता है। |
| [getThreeDFormat()](#getThreeDFormat--) | टेक्स्ट के लिए 3D प्रभाव गुणों को दर्शाने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता या सेट करता है। |
| [getWrapText()](#getWrapText--) | यदि टेक्स्ट को TextFrame के मार्जिन पर रैप किया गया हो तो सत्य। |
| [setWrapText(byte value)](#setWrapText-byte-) | यदि टेक्स्ट को TextFrame के मार्जिन पर रैप किया गया हो तो सत्य। |
| [getAnchoringType()](#getAnchoringType--) | TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame में वर्टिकल एंकर टेक्स्ट को लौटाता या सेट करता है। |
| [getCenterText()](#getCenterText--) | यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। |
| [setCenterText(byte value)](#setCenterText-byte-) | यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | टेक्स्ट की अभिविन्यास निर्धारित करता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट के autofit मोड को लौटाता या सेट करता है। |
| [setAutofitType(byte value)](#setAutofitType-byte-) | टेक्स्ट के autofit मोड को लौटाता या सेट करता है। |
| [getColumnCount()](#getColumnCount--) | टेक्स्ट एरिया में कॉलम की संख्या को लौटाता या सेट करता है। |
| [setColumnCount(int value)](#setColumnCount-int-) | टेक्स्ट एरिया में कॉलम की संख्या को लौटाता या सेट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्ट एरिया में टेक्स्ट कॉलम के बीच की जगह (पॉइंट में) को लौटाता या सेट करता है। |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | टेक्ट एरिया में टेक्स्ट कॉलम के बीच की जगह (पॉइंट में) को लौटाता या सेट करता है। |
| [getRotationAngle()](#getRotationAngle--) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। |
| [getTransform()](#getTransform--) | टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। |
| [setTransform(byte value)](#setTransform-byte-) | टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। |
| [getKeepTextFlat()](#getKeepTextFlat--) | भले ही 3-D रोटेशन प्रभाव लागू किया गया हो, टेक्स्ट को सपाट रखने को प्राप्त करता या सेट करता है। |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | भले ही 3-D रोटेशन प्रभाव लागू किया गया हो, टेक्स्ट को सपाट रखने को प्राप्त करता या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


नई [TextFrameFormat](../../com.aspose.slides/textframeformat) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पठन long।

**रिटर्न:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


टेक्स्ट की स्टाइल लौटाता है। केवल-पठन [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


टेक्स्ट के लिए 3D प्रभाव गुणों को दर्शाने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। केवल-पठन [IThreeDFormat](../../com.aspose.slides/ithreedformat)।

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
>      // कॉन्टूर सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // गहराई सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // मैटीरियल सेट करें
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
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


यदि टेक्स्ट को TextFrame के मार्जिन पर रैप किया गया हो तो सत्य। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि Presentation में टेक्स्ट कैसे रैप किया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


यदि टेक्स्ट को TextFrame के मार्जिन पर रैप किया गया हो तो सत्य। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि Presentation में टेक्स्ट कैसे रैप किया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


TextFrame में वर्टिकल एंकर टेक्स्ट को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**रिटर्न:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


TextFrame में वर्टिकल एंकर टेक्स्ट को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल से संक्षिप्त दृश्य टेक्स्ट रोटेशन का मूल्य प्राप्त होता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**रिटर्न:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


टेक्स्ट की अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल से संक्षिप्त दृश्य टेक्स्ट रोटेशन का मूल्य प्राप्त होता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


टेक्स्ट के autofit मोड को लौटाता या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype)।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint प्रस्तुति में टेक्स्ट को फिट करने के लिए आकार को कैसे री-साइज़ किया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  निम्नलिखित नमूना कोड दर्शाता है कि ओवरफ़्लो पर टेक्स्ट को कैसे सिकुड़ाया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


टेक्स्ट के autofit मोड को लौटाता या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype)।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint प्रस्तुति में टेक्स्ट को फिट करने के लिए आकार को कैसे री-साइज़ किया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  निम्नलिखित नमूना कोड दर्शाता है कि ओवरफ़्लो पर टेक्स्ट को कैसे सिकुड़ाया जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


टेक्स्ट एरिया में कॉलम की संख्या को लौटाता या सेट करता है। यह मान सकारात्मक होना चाहिए। अन्यथा, मान शून्य सेट हो जाएगा। मान 0 अनिर्धारित मान दर्शाता है। पढ़ें/लिखें int।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint प्रस्तुति में टेक्स्ट फ्रेम के भीतर कॉलम कैसे जोड़ा जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


टेक्स्ट एरिया में कॉलम की संख्या को लौटाता या सेट करता है। यह मान सकारात्मक होना चाहिए। अन्यथा, मान शून्य सेट हो जाएगा। मान 0 अनिर्धारित मान दर्शाता है। पढ़ें/लिखें int।

--------------------

> ```
> निम्नलिखित नमूना कोड दर्शाता है कि PowerPoint प्रस्तुति में टेक्स्ट फ्रेम के भीतर कॉलम कैसे जोड़ा जाए।
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


टेक्स्ट एरिया में टेक्स्ट कॉलम के बीच की जगह (पॉइंट में) को लौटाता या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान सकारात्मक होना चाहिए। अन्यथा, मान शून्य सेट हो जाएगा। पढ़ें/लिखें double।

**रिटर्न:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


टेक्स्ट एरिया में टेक्स्ट कॉलम के बीच की जगह (पॉइंट में) को लौटाता या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान सकारात्मक होना चाहिए। अन्यथा, मान शून्य सेट हो जाएगा। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं है, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट है, तो यह शेप से स्वतंत्र रूप से लागू होता है। अर्थात शेप का रोटेशन अतिरिक्त रूप से लागू हो सकता है जबकि टेक्स्ट खुद का रोटेशन भी लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType में पूर्वनिर्धारित वर्टिकल टाइप से संक्षिप्त दृश्य टेक्स्ट रोटेशन का मूल्य प्राप्त होता है। पढ़ें/लिखें float।

--------------------

> ```
> ऐसे केस को विचार करें जहाँ किसी आकार पर 90 डिग्री घड़ी की दिशा में घुमाव लागू किया गया हो. 
>  इसके अतिरिक्त, टेक्स्ट बॉडी स्वयं पर -90 डिग्री उल्टी दिशा में लागू किया गया है. फिर परिणामी आकार ऐसा दिखाई देगा कि
>  घुमा हुआ है लेकिन उसके भीतर का टेक्स्ट ऐसा दिखाई देगा जैसे कि उसे बिल्कुल भी घुमा नहीं गया हो.
```

**रिटर्न:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं है, तो साथ वाले शेप का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट है, तो यह शेप से स्वतंत्र रूप से लागू होता है। अर्थात शेप का रोटेशन अतिरिक्त रूप से लागू हो सकता है जबकि टेक्स्ट खुद का रोटेशन भी लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType में पूर्वनिर्धारित वर्टिकल टाइप से संक्षिप्त दृश्य टेक्स्ट रोटेशन का मूल्य प्राप्त होता है। पढ़ें/लिखें float।

--------------------

> ```
> ऐसे मामले पर विचार करें जहाँ किसी आकार पर 90 डिग्री घड़ी की दिशा में घुमाव लागू किया गया हो। 
>  इसके अतिरिक्त, टेक्स्ट बॉडी स्वयं पर -90 डिग्री 
>  उल्टी दिशा में लागू किया गया है। फिर परिणामी आकार ऐसा दिखेगा कि 
>  घुमा हुआ है, लेकिन उसके भीतर का टेक्स्ट ऐसा दिखेगा जैसे उसे बिल्कुल भी नहीं घुमा गया हो। 
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype)।

**रिटर्न:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


टेक्स्ट रैपिंग आकार को प्राप्त करता या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


भले ही 3-D रोटेशन प्रभाव लागू किया गया हो, टेक्स्ट को सपाट रखने को प्राप्त करता या सेट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


भले ही 3-D रोटेशन प्रभाव लागू किया गया हो, टेक्स्ट को सपाट रखने को प्राप्त करता या सेट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).