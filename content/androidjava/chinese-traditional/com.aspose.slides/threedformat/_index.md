---
title: ThreeDFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 3-D 屬性。
type: docs
url: /zh-hant/com.aspose.slides/threedformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面：**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

代表 3-D 屬性。

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // 建立 Presentation 類別的實例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法加入形狀
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // 定義 TextFrame 及其屬性
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // 定義 ThreeDFormat 屬性
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // 儲存 Presentation 檔案
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // 建立 Presentation 類別的實例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法加入形狀
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // 定義 TextFrame 及其屬性
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // 將 FillFormat.FillType 設定為 FillType.Gradient 並定義漸層屬性
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // 定義 ThreeDFormat 屬性
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // 儲存 Presentation 檔案
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // 建立 Presentation 類別的實例。
>  Presentation pres = new Presentation();
>  try {
>      // 使用 AddAutoShape 方法加入形狀
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // 定義 TextFrame 及其屬性
>      shape.getTextFrame().setText("3D Text");
>      // 將 FillFormat.FillType 設定為 FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // 設定 TextFrame 的 Portion 並配置 PortionFormat 的屬性
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // 設定 "Arch Up" WordArt 變形效果
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // 定義 ITextFrame 的 ThreeDFormat 屬性
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // 儲存 Presentation 檔案
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 傳回或設定 3D 輪廓的寬度。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 傳回或設定 3D 輪廓的寬度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 傳回或設定 擠壓效果的高度。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 傳回或設定 擠壓效果的高度。 |
| [getDepth()](#getDepth--) | 傳回或設定 3D 形狀的深度。 |
| [setDepth(double value)](#setDepth-double-) | 傳回或設定 3D 形狀的深度。 |
| [getBevelTop()](#getBevelTop--) | 傳回或設定 上方 3D 斜角的類型。 |
| [getBevelBottom()](#getBevelBottom--) | 傳回或設定 下方 3D 斜角的類型。 |
| [getContourColor()](#getContourColor--) | 傳回或設定 輪廓的顏色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 傳回或設定 擠壓的顏色。 |
| [getCamera()](#getCamera--) | 傳回或設定 相機的設定。 |
| [getLightRig()](#getLightRig--) | 傳回或設定 光源的類型。 |
| [getMaterial()](#getMaterial--) | 傳回或設定 材料的類型。 |
| [setMaterial(int value)](#setMaterial-int-) | 傳回或設定 材料的類型。 |
| [getEffective()](#getEffective--) | 取得套用繼承的有效 3-D 格式資料。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

傳回或設定 3D 輪廓的寬度。可讀寫 double。

**返回：**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

傳回或設定 3D 輪廓的寬度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

傳回或設定 擠壓效果的高度。可讀寫 double。

**返回：**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

傳回或設定 擠壓效果的高度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

傳回或設定 3D 形狀的深度。可讀寫 double。

**返回：**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

傳回或設定 3D 形狀的深度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

傳回或設定 上方 3D 斜角的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

傳回或設定 下方 3D 斜角的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

傳回或設定 輪廓的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

傳回或設定 擠壓的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

傳回或設定 相機的設定。唯讀 [ICamera](../../com.aspose.slides/icamera)。

**返回：**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

傳回或設定 光源的類型。唯讀 [ILightRig](../../com.aspose.slides/ilightrig)。

**返回：**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

傳回或設定 材料的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**返回：**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

傳回或設定 材料的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

取得套用繼承的有效 3-D 格式資料。

--------------------

> ```
> 此範例示範如何取得相機、光源組與形狀上斜角的有效屬性。
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
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - 一個 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)。