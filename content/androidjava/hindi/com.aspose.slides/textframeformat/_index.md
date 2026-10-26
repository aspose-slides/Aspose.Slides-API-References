---
title: TextFrameFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: TextFrames की formatTextFrameFormatting गुणों को सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/textframeformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

TextFrame के formatTextFrameFormatting गुणों को सम्मिलित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | एक नया उदाहरण आरंभ करता है [TextFrameFormat](../../com.aspose.slides/textframeformat) क्लास का। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | टेक्स्ट की शैली लौटाता है। |
| [getThreeDFormat()](#getThreeDFormat--) | टेक्स्ट के लिए 3d प्रभाव गुणों का प्रतिनिधित्व करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता है या सेट करता है। |
| [getWrapText()](#getWrapText--) | यदि टेक्स्ट TextFrame के मार्जिन पर लिपटा हो तो True। |
| [setWrapText(byte value)](#setWrapText-byte-) | यदि टेक्स्ट TextFrame के मार्जिन पर लिपटा हो तो True। |
| [getAnchoringType()](#getAnchoringType--) | TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। |
| [getCenterText()](#getCenterText--) | यदि NullableBool.True है तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित किया जाना चाहिए। |
| [setCenterText(byte value)](#setCenterText-byte-) | यदि NullableBool.True है तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित किया जाना चाहिए। |
| [getTextVerticalType()](#getTextVerticalType--) | टेक्स्ट अभिविन्यास निर्धारित करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | टेक्स्ट अभिविन्यास निर्धारित करता है। |
| [getAutofitType()](#getAutofitType--) | टेक्स्ट के ऑटोफिट मोड को लौटाता है या सेट करता है। |
| [setAutofitType(byte value)](#setAutofitType-byte-) | टेक्स्ट के ऑटोफिट मोड को लौटाता है या सेट करता है। |
| [getColumnCount()](#getColumnCount--) | टेक्स्ट क्षेत्र में स्तंभों की संख्या को लौटाता है या सेट करता है। |
| [setColumnCount(int value)](#setColumnCount-int-) | टेक्स्ट क्षेत्र में स्तंभों की संख्या को लौटाता है या सेट करता है। |
| [getColumnSpacing()](#getColumnSpacing--) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की जगह (पॉइंट) को लौटाता है या सेट करता है। |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की जगह (पॉइंट) को लौटाता है या सेट करता है। |
| [getRotationAngle()](#getRotationAngle--) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू की जा रही कस्टम घूर्णन को निर्दिष्ट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू की जा रही कस्टम घूर्णन को निर्दिष्ट करता है। |
| [getTransform()](#getTransform--) | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। |
| [setTransform(byte value)](#setTransform-byte-) | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। |
| [getKeepTextFlat()](#getKeepTextFlat--) | यदि 3-D घूर्णन प्रभाव लागू किया गया हो तो भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | यदि 3-D घूर्णन प्रभाव लागू किया गया हो तो भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

एक नया उदाहरण आरंभ करता है [TextFrameFormat](../../com.aspose.slides/textframeformat) क्लास का।

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long.

**रिटर्न:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

टेक्स्ट के लिए 3D प्रभाव गुणों का प्रतिनिधित्व करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // टेक्स्ट परिवर्तन सेट करें
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // एक्सट्रूज़न सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // कॉन्टूर सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // गहराई सेट करें
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // मटेरियल सेट करें
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

TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

TextFrame में बाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

TextFrame में दाएँ मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

TextFrame में ऊपर मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

TextFrame में नीचे मार्जिन (पॉइंट) को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

यदि टेक्स्ट TextFrame के मार्जिन पर लिपटा हो तो True। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
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

यदि टेक्स्ट TextFrame के मार्जिन पर लिपटा हो तो True। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
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


**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype).

**रिटर्न:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

यदि NullableBool.True है तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित किया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

यदि NullableBool.True है तो टेक्स्ट को क्षैतिज रूप से बॉक्स में केंद्रित किया जाना चाहिए। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

टेक्स्ट अभिविन्यास निर्धारित करता है। दृश्य टेक्स्ट घूर्णन का परिणाम इस गुण और RotationAngle संपत्ति के कस्टम कोण से संक्षिप्त है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype).

**रिटर्न:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

टेक्स्ट अभिविन्यास निर्धारित करता है। दृश्य टेक्स्ट घूर्णन का परिणाम इस गुण और RotationAngle संपत्ति के कस्टम कोण से संक्षिप्त है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

टेक्स्ट के ऑटोफिट मोड को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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

टेक्स्ट के ऑटोफिट मोड को लौटाता है या सेट करता है। पढ़ें/लिखें [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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


**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता है या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। मान 0 अज्ञात मान दर्शाता है। पढ़ें/लिखें int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
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

टेक्स्ट क्षेत्र में कॉलमों की संख्या को लौटाता है या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। मान 0 अज्ञात मान दर्शाता है। पढ़ें/लिखें int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
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


**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की जगह (पॉइंट) को लौटाता है या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। पढ़ें/लिखें double.

**रिटर्न:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच की जगह (पॉइंट) को लौटाता है या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू की जा रही कस्टम घूर्णन को निर्दिष्ट करता है। यदि यह निर्दिष्ट नहीं है, तो सहायक आकार की घूर्णन उपयोग की जाती है। यदि यह निर्दिष्ट है, तो यह आकार से स्वतंत्र रूप से लागू होती है। अर्थात् आकार के साथ अतिरिक्त घूर्णन लागू हो सकता है जबकि टेक्स्ट स्वयं पर भी घूर्णन लागू हो। दृश्य टेक्स्ट घूर्णन का परिणाम इस गुण और TextVerticalType संपत्ति में पूर्व निर्धारित ऊर्ध्वाधर प्रकार से संक्षिप्त है। पढ़ें/लिखें float.

--------------------

> ```
> विचार करें कि एक आकार पर 90 डिग्री घड़ी की दिशा में घूर्णन लागू किया गया है। 
>  इसके अतिरिक्त, स्वयं टेक्स्ट बॉडी पर -90 डिग्री प्रतिक्लॉकवाइज (घड़ी की विपरीत दिशा) घूर्णन लागू किया गया है। फिर परिणामी आकार ऐसा प्रतीत होगा
>  घुमा हुआ, लेकिन उसके भीतर का टेक्स्ट ऐसा दिखेगा मानो उसे बिल्कुल भी नहीं घुमाया गया हो। 
```

**रिटर्न:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू की जा रही कस्टम घूर्णन को निर्दिष्ट करता है। यदि यह निर्दिष्ट नहीं है, तो सहायक आकार की घूर्णन उपयोग की जाती है। यदि यह निर्दिष्ट है, तो यह आकार से स्वतंत्र रूप से लागू होती है। अर्थात् आकार के साथ अतिरिक्त घूर्णन लागू हो सकता है जबकि टेक्स्ट स्वयं पर भी घूर्णन लागू हो। दृश्य टेक्स्ट घूर्णन का परिणाम इस गुण और TextVerticalType संपत्ति में पूर्व निर्धारित ऊर्ध्विक प्रकार से संक्षिप्त है। पढ़ें/लिखें float.

--------------------

> ```
> विचार करें कि एक आकार पर 90 डिग्री घड़ी की दिशा में घूर्णन लागू किया गया है। 
>  इसके अतिरिक्त, स्वयं टेक्स्ट बॉडी पर -90 डिग्री प्रतिक्लॉकवाइज (घड़ी की विपरीत दिशा) घूर्णन लागू किया गया है 
>  फिर परिणामी आकार ऐसा दिखेगा कि वह घुमा हुआ है
>  लेकिन उसके भीतर का टेक्स्ट ऐसा प्रतीत होगा मानो उसे बिल्कुल भी नहीं घुमा गया हो। 
```

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype).

**रिटर्न:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [TextShapeType](../../com.aspose.slides/textshapetype).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

3-D घूर्णन प्रभाव लागू होने पर भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

3-D घूर्णन प्रभाव लागू होने पर भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
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