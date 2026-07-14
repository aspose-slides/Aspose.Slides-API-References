---
title: ThreeDFormat
second_title: Aspose.Slides एंड्रॉइड के लिए Java API संदर्भ
description: 3-D गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/threedformat/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)  
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

3-D गुणों का प्रतिनिधित्व करता है।

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Presentation क्लास का एक उदाहरण बनाएं।
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape मेथड का उपयोग करके एक शैल जोड़ें।
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // TextFrame और उसकी गुणों को परिभाषित करें।
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // ThreeDFormat गुणों को परिभाषित करें।
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation फ़ाइल सहेजें।
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Presentation क्लास का एक उदाहरण बनाएं।
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape मेथड का उपयोग करके एक शैल जोड़ें।
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame और उसकी गुणों को परिभाषित करें।
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // FillFormat.FillType को FillType.Gradient के रूप में सेट करें और ग्रेडिएंट गुणों को परिभाषित करें।
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // ThreeDFormat गुणों को परिभाषित करें।
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation फ़ाइल सहेजें।
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Presentation क्लास का एक उदाहरण बनाएं।
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape मेथड का उपयोग करके एक शैल जोड़ें।
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame और उसकी गुणों को परिभाषित करें।
>      shape.getTextFrame().setText("3D Text");
>      // FillFormat.FillType को FillType.NoFill के रूप में सेट करें।
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // TextFrame के Portion को कॉन्फ़िगर करें और PortionFormat के गुणों को सेट करें।
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // "Arch Up" WordArt ट्रांसफ़ॉर्म इफ़ेक्ट सेटअप करें।
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // ITextFrame के ThreeDFormat गुणों को परिभाषित करें।
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Presentation फ़ाइल सहेजें।
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 3D कंटूर की चौड़ाई को लौटाता या सेट करता है। |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D कंटूर की चौड़ाई को लौटाता या सेट करता है। |
| [getExtrusionHeight()](#getExtrusionHeight--) | एक्सट्रूज़न प्रभाव की ऊंचाई को लौटाता या सेट करता है। |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | एक्सट्रूज़न प्रभाव की ऊंचाई को लौटाता या सेट करता है। |
| [getDepth()](#getDepth--) | 3D आकार की गहराई को लौटाता या सेट करता है। |
| [setDepth(double value)](#setDepth-double-) | 3D आकार की गहराई को लौटाता या सेट करता है। |
| [getBevelTop()](#getBevelTop--) | शीर्ष 3D बेलव की प्रकार को लौटाता या सेट करता है। |
| [getBevelBottom()](#getBevelBottom--) | निचले 3D बेलव की प्रकार को लौटाता या सेट करता है। |
| [getContourColor()](#getContourColor--) | कंटूर का रंग लौटाता या सेट करता है। |
| [getExtrusionColor()](#getExtrusionColor--) | एक्सट्रूज़न का रंग लौटाता या सेट करता है। |
| [getCamera()](#getCamera--) | कैमरा की सेटिंग्स को लौटाता या सेट करता है। |
| [getLightRig()](#getLightRig--) | लाइट की प्रकार को लौटाता या सेट करता है। |
| [getMaterial()](#getMaterial--) | मैटेरियल की प्रकार को लौटाता या सेट करता है। |
| [setMaterial(int value)](#setMaterial-int-) | मैटेरियल की प्रकार को लौटाता या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू किए गए प्रभावी 3-D फॉर्मेटिंग डेटा को प्राप्त करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long.

**रिटर्न:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


3D कंटूर की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


3D कंटूर की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


एक्सट्रूज़न प्रभाव की ऊंचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


एक्सट्रूज़न प्रभाव की ऊंचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```


3D आकार की गहराई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


3D आकार की गहराई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


शीर्ष 3D बेलव की प्रकार को लौटाता या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**रिटर्न:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


निचले 3D बेलव की प्रकार को लौटाता या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**रिटर्न:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


कंटूर का रंग लौटाता या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


एक्सट्रूज़न का रंग लौटाता या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


कैमरा की सेटिंग्स को लौटाता या सेट करता है। केवल-पढ़ने योग्य [ICamera](../../com.aspose.slides/icamera).

**रिटर्न:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


लाइट की प्रकार को लौटाता या सेट करता है। केवल-पढ़ने योग्य [ILightRig](../../com.aspose.slides/ilightrig).

**रिटर्न:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


मैटेरियल की प्रकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**रिटर्न:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


मैटेरियल की प्रकार को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


विरासत लागू किए गए प्रभावी 3-D फॉर्मेटिंग डेटा को प्राप्त करता है।

--------------------

> ```
> This example demonstrates how to get effective properties for camera, light rig and shape's top bevel.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try 
>  {
>      IThreeDFormatEffectiveData threeDEffectiveData = pres.getSlides().get_Item(0).getShapes().get_Item(0).getThreeDFormat().getEffective();
>      System.out.println("= Effective camera properties =");
>      System.out.println("Type: " + threeDEffectiveData.getCamera().getCameraType());
>      System.out.println("Field of view: " + threeDEffectiveData.getCamera().getFieldOfViewAngle());
>      System.out.println("Zoom: " + threeDEffectiveData.getCamera().getZoom());
>      System.out.println("= Effective light rig properties =");
>      System.out.println("Type: " + threeDEffectiveData.getLightRig().getLightType());
>      System.out.println("Direction: " + threeDEffectiveData.getLightRig().getDirection());
>      System.out.println("= Effective shape's top face relief properties =");
>      System.out.println("Type: " + threeDEffectiveData.getBevelTop().getBevelType());
>      System.out.println("Width: " + threeDEffectiveData.getBevelTop().getWidth());
>      System.out.println("Height: " + threeDEffectiveData.getBevelTop().getHeight());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - एक [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).