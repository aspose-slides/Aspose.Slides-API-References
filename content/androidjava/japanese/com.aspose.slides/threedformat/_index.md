---
title: ThreeDFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: 3-D プロパティを表します。
type: docs
url: /ja/com.aspose.slides/threedformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)  
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

3-D プロパティを表します。

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Presentation クラスのインスタンスを作成します。
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape メソッドを使用してシェイプを追加します。
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // TextFrame とそのプロパティを定義します。
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // ThreeDFormat のプロパティを定義します。
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation ファイルを保存します。
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Presentation クラスのインスタンスを作成します。
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape メソッドを使用してシェイプを追加します。
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame とそのプロパティを定義します。
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // FillFormat.FillType を FillType.Gradient に設定し、グラデーションのプロパティを定義します。
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // ThreeDFormat のプロパティを定義します。
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation ファイルを保存します。
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Presentation クラスのインスタンスを作成します。
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape メソッドを使用してシェイプを追加します。
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame とそのプロパティを定義します。
>      shape.getTextFrame().setText("3D Text");
>      // FillFormat.FillType を FillType.NoFill に設定します。
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // TextFrame の Portion を設定し、PortionFormat のプロパティを設定します。
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // "Arch Up" の WordArt 変形エフェクトを設定します。
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // ITextFrame の ThreeDFormat プロパティを定義します。
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Presentation ファイルを保存します。
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 3D輪郭の幅を取得または設定します。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D輪郭の幅を取得または設定します。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 押し出し効果の高さを取得または設定します。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 押し出し効果の高さを取得または設定します。 |
| [getDepth()](#getDepth--) | 3D形状の奥行きを取得または設定します。 |
| [setDepth(double value)](#setDepth-double-) | 3D形状の奥行きを取得または設定します。 |
| [getBevelTop()](#getBevelTop--) | 上部3Dベベルの種類を取得または設定します。 |
| [getBevelBottom()](#getBevelBottom--) | 下部3Dベベルの種類を取得または設定します。 |
| [getContourColor()](#getContourColor--) | 輪郭の色を取得または設定します。 |
| [getExtrusionColor()](#getExtrusionColor--) | 押し出しの色を取得または設定します。 |
| [getCamera()](#getCamera--) | カメラの設定を取得または設定します。 |
| [getLightRig()](#getLightRig--) | 光源の種類を取得または設定します。 |
| [getMaterial()](#getMaterial--) | 素材の種類を取得または設定します。 |
| [setMaterial(int value)](#setMaterial-int-) | 素材の種類を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な3-D書式設定データを取得します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long。

**戻り値:**  
long

### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

3D輪郭の幅を取得または設定します。読み書き可能な double。

**戻り値:**  
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

3D輪郭の幅を取得または設定します。読み書き可能な double。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

押し出し効果の高さを取得または設定します。読み書き可能な double。

**戻り値:**  
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

押し出し効果の高さを取得または設定します。読み書き可能な double。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

3D形状の奥行きを取得または設定します。読み書き可能な double。

**戻り値:**  
double

### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

3D形状の奥行きを取得または設定します。読み書き可能な double。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

上部3Dベベルの種類を取得または設定します。読み取り専用 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**戻り値:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

下部3Dベベルの種類を取得または設定します。読み取り専用 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**戻り値:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

輪郭の色を取得または設定します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

押し出しの色を取得または設定します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

カメラの設定を取得または設定します。読み取り専用 [ICamera](../../com.aspose.slides/icamera)。

**戻り値:**  
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

光源の種類を取得または設定します。読み取り専用 [ILightRig](../../com.aspose.slides/ilightrig)。

**戻り値:**  
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

素材の種類を取得または設定します。読み書き可能 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**戻り値:**  
int

### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

素材の種類を取得または設定します。読み書き可能 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

継承が適用された有効な3-D書式設定データを取得します。

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

**戻り値:**  
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).