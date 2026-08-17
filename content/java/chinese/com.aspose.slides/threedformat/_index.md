---
title: ThreeDFormat
second_title: Aspose.Slides for Java API 参考
description: 表示 3-D 属性。
type: docs
url: /zh/com.aspose.slides/threedformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**实现的所有接口：**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

表示 3-D 属性。

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // 创建 Presentation 类的实例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法添加形状
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // 定义 TextFrame 及其属性
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // 定义 ThreeDFormat 属性
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // 保存 Presentation 文件
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // 创建 Presentation 类的实例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法添加形状
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // 定义 TextFrame 及其属性
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // 将 FillFormat.FillType 配置为 FillType.Gradient 并定义渐变属性
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // 定义 ThreeDFormat 属性
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // 保存 Presentation 文件
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // 创建 Presentation 类的实例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法添加形状
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // 定义 TextFrame 及其属性
>      shape.getTextFrame().setText("3D Text");
>      // 将 FillFormat.FillType 配置为 FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // 配置 TextFrame 的 Portion 并设置 PortionFormat 属性
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // 设置 "Arch Up" WordArt 变换效果
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // 定义 ITextFrame 的 ThreeDFormat 属性
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // 保存 Presentation 文件
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 返回或设置 3D 轮廓的宽度。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 返回或设置 3D 轮廓的宽度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 返回或设置 拉伸效果的高度。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 返回或设置 拉伸效果的高度。 |
| [getDepth()](#getDepth--) | 返回或设置 3D 形状的深度。 |
| [setDepth(double value)](#setDepth-double-) | 返回或设置 3D 形状的深度。 |
| [getBevelTop()](#getBevelTop--) | 返回或设置 顶部 3D 倒角的类型。 |
| [getBevelBottom()](#getBevelBottom--) | 返回或设置 底部 3D 倒角的类型。 |
| [getContourColor()](#getContourColor--) | 返回或设置 轮廓的颜色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 返回或设置 拉伸的颜色。 |
| [getCamera()](#getCamera--) | 返回或设置 相机的设置。 |
| [getLightRig()](#getLightRig--) | 返回或设置 光源的类型。 |
| [getMaterial()](#getMaterial--) | 返回或设置 材料的类型。 |
| [setMaterial(int value)](#setMaterial-int-) | 返回或设置 材料的类型。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效 3-D 格式化数据。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

返回或设置 3D 轮廓的宽度。读写 double。

**返回：**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

返回或设置 3D 轮廓的宽度。读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

返回或设置 拉伸效果的高度。读写 double。

**返回：**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

返回或设置 拉伸效果的高度。读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

返回或设置 3D 形状的深度。读写 double。

**返回：**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

返回或设置 3D 形状的深度。读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

返回或设置 顶部 3D 倒角的类型。只读 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

返回或设置 底部 3D 倒角的类型。只读 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

返回或设置 轮廓的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

返回或设置 拉伸的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

返回或设置 相机的设置。只读 [ICamera](../../com.aspose.slides/icamera)。

**返回：**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

返回或设置 光源的类型。只读 [ILightRig](../../com.aspose.slides/ilightrig)。

**返回：**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

返回或设置 材料的类型。读写 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**返回：**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

返回或设置 材料的类型。读写 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

获取已应用继承的有效 3-D 格式化数据。

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


**返回：**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).