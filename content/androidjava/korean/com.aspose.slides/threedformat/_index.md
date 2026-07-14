---
title: ThreeDFormat
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 3-D 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/threedformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)  
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

3-D 속성을 나타냅니다.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Presentation 클래스의 인스턴스를 생성합니다.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape 메서드를 사용하여 도형을 추가합니다.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // TextFrame 및 해당 속성을 정의합니다.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // ThreeDFormat 속성을 정의합니다.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation 파일을 저장합니다.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Presentation 클래스의 인스턴스를 생성합니다.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape 메서드를 사용하여 도형을 추가합니다.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame 및 해당 속성을 정의합니다.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // FillFormat.FillType을 FillType.Gradient로 설정하고 그라디언트 속성을 정의합니다.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // ThreeDFormat 속성을 정의합니다.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation 파일을 저장합니다.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Presentation 클래스의 인스턴스를 생성합니다.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape 메서드를 사용하여 도형을 추가합니다.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame 및 해당 속성을 정의합니다.
>      shape.getTextFrame().setText("3D Text");
>      // FillFormat.FillType을 FillType.NoFill로 설정합니다.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // TextFrame의 Portion을 설정하고 PortionFormat 속성을 구성합니다.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // "Arch Up" WordArt 변환 효과를 설정합니다.
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // ITextFrame의 ThreeDFormat 속성을 정의합니다.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Presentation 파일을 저장합니다.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 3D 윤곽선의 너비를 반환하거나 설정합니다. |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D 윤곽선의 너비를 반환하거나 설정합니다. |
| [getExtrusionHeight()](#getExtrusionHeight--) | 돌출 효과의 높이를 반환하거나 설정합니다. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 돌출 효과의 높이를 반환하거나 설정합니다. |
| [getDepth()](#getDepth--) | 3D 형상의 깊이를 반환하거나 설정합니다. |
| [setDepth(double value)](#setDepth-double-) | 3D 형상의 깊이를 반환하거나 설정합니다. |
| [getBevelTop()](#getBevelTop--) | 상단 3D 베벨의 유형을 반환하거나 설정합니다. |
| [getBevelBottom()](#getBevelBottom--) | 하단 3D 베벨의 유형을 반환하거나 설정합니다. |
| [getContourColor()](#getContourColor--) | 윤곽선의 색상을 반환하거나 설정합니다. |
| [getExtrusionColor()](#getExtrusionColor--) | 돌출 효과의 색상을 반환하거나 설정합니다. |
| [getCamera()](#getCamera--) | 카메라 설정을 반환하거나 설정합니다. |
| [getLightRig()](#getLightRig--) | 광원의 유형을 반환하거나 설정합니다. |
| [getMaterial()](#getMaterial--) | 재료의 유형을 반환하거나 설정합니다. |
| [setMaterial(int value)](#setMaterial-int-) | 재료의 유형을 반환하거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long

### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

3D 윤곽선의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

3D 윤곽선의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

돌출 효과의 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

돌출 효과의 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

3D 형상의 깊이를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

3D 형상의 깊이를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

상단 3D 베벨의 유형을 반환하거나 설정합니다. 읽기 전용 [IShapeBevel](../../com.aspose.slides/ishapebevel).

**반환:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

하단 3D 베벨의 유형을 반환하거나 설정합니다. 읽기 전용 [IShapeBevel](../../com.aspose.slides/ishapebevel).

**반환:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

윤곽선의 색상을 반환하거나 설정합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

돌출 효과의 색상을 반환하거나 설정합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

카메라 설정을 반환하거나 설정합니다. 읽기 전용 [ICamera](../../com.aspose.slides/icamera).

**반환:**  
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

광원의 유형을 반환하거나 설정합니다. 읽기 전용 [ILightRig](../../com.aspose.slides/ilightrig).

**반환:**  
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

재료의 유형을 반환하거나 설정합니다. 읽기/쓰기 [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**반환:**  
int

### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

재료의 유형을 반환하거나 설정합니다. 읽기/쓰기 [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**매개변수:**  
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 3-D 서식 데이터를 가져옵니다.

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

**반환:**  
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - 하나의 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).