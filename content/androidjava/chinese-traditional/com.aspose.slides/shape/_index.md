---
title: Shape
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片上的形狀。
type: docs
url: /zh-hant/com.aspose.slides/shape/
---
**繼承:**  
java.lang.Object

**所有已實作介面:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

表示投影片上的形狀。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 判斷形狀是否為 TextHolder_PPT。 |
| [getPlaceholder()](#getPlaceholder--) | 返回形狀的占位符。 |
| [removePlaceholder()](#removePlaceholder--) | 定義此形狀不是占位符。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在則新增占位符，並將占位符屬性設定為指定的占位符。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本占位符形狀（從版面配置和/或母片投影片繼承的形狀）。 |
| [getCustomData()](#getCustomData--) | 返回形狀的自訂資料。 |
| [getRawFrame()](#getRawFrame--) | 返回或設定原始形狀框架的屬性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或設定原始形狀框架的屬性。 |
| [getFrame()](#getFrame--) | 返回或設定形狀框架的屬性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或設定形狀框架的屬性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形狀線條格式屬性的 LineFormat 物件。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形狀填充格式屬性的 FillFormat 物件。 |
| [getImage()](#getImage--) | 返回形狀縮圖。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形狀縮圖。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將形狀內容儲存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將形狀內容儲存為 SVG 檔案。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 返回或設定滑鼠點擊時的超連結。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 返回或設定滑鼠點擊時的超連結。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 返回或設定滑鼠移過時的超連結。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 返回或設定滑鼠移過時的超連結。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | 返回超連結管理器。 |
| [getHidden()](#getHidden--) | 判斷形狀是否隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷形狀是否隱藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形狀在 Z 軸排序中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形狀的連接點數量。 |
| [getRotation()](#getRotation--) | 返回或設定指定形狀繞 Z 軸旋轉的度數。 |
| [setRotation(float value)](#setRotation-float-) | 返回或設定指定形狀繞 Z 軸旋轉的度數。 |
| [getX()](#getX--) | 取得或設定形狀左上角的 x 座標（以點為單位）。 |
| [setX(float value)](#setX-float-) | 取得或設定形狀左上角的 x 座標（以點為單位）。 |
| [getY()](#getY--) | 取得或設定形狀左上角的 y 座標（以點為單位）。 |
| [setY(float value)](#setY-float-) | 取得或設定形狀左上角的 y 座標（以點為單位）。 |
| [getWidth()](#getWidth--) | 取得或設定形狀的寬度（以點為單位）。 |
| [setWidth(float value)](#setWidth-float-) | 取得或設定形狀的寬度（以點為單位）。 |
| [getHeight()](#getHeight--) | 取得或設定形狀的高度（以點為單位）。 |
| [setHeight(float value)](#setHeight-float-) | 取得或設定形狀的高度（以點為單位）。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [getUniqueId()](#getUniqueId--) | 返回供外掛或其他程式使用的內部簡報範圍識別碼。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式能可靠地在文件任意位置參照該形狀。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或設定與形狀相關聯的替代文字。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或設定與形狀相關聯的替代文字。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或設定與形狀相關聯的替代文字標題。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或設定與形狀相關聯的替代文字標題。 |
| [getName()](#getName--) | 返回或設定形狀的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定形狀的名稱。 |
| [isDecorative()](#isDecorative--) | 取得或設定「標記為裝飾」選項（可讀寫布林值）。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 取得或設定「標記為裝飾」選項（可讀寫布林值）。 |
| [getShapeLock()](#getShapeLock--) | 返回形狀的鎖定狀態。 |
| [isGrouped()](#isGrouped--) | 判斷形狀是否已群組。 |
| [getParentGroup()](#getParentGroup--) | 若形狀已群組，則返回父 GroupShape 物件。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [getSlide()](#getSlide--) | 返回形狀的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回投影片的父簡報。 |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

判斷形狀是否為 TextHolder_PPT。唯讀 boolean 。

**返回：**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

返回形狀的占位符。若形狀沒有占位符則返回 null。唯讀 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // 實例化一個 Presentation 類別
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // 存取第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 遍歷形狀以尋找占位符
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // 更改每個占位符中的文字
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // 將簡報儲存至磁碟
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // 遍歷投影片
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint 顯示 "點擊以新增標題"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // 新增副標題
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

定義此形狀不是占位符。

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

如果不存在則新增占位符，並將占位符屬性設定為指定的占位符。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 要複製內容的占位符。 |

**返回：**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新的 #getPlaceholder.getPlaceholder。

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

返回基本占位符形狀（從版面配置和/或母片投影片繼承的形狀）。

--------------------

> ```
> // 取得占位符形狀的所有 (母版/版面/投影片) 動畫效果
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

若當前形狀未繼承，則返回 null。

**返回：**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

返回形狀的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

返回或設定原始形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，禁止在 IShape.getFrame() 使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須被定義（不可為 Float.NaN 或 NullableBool.NotDefined）。上述程式碼現在會拋出 ArgumentException 例外。
>  //此適用於以下使用情況：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能為未定義
>  IShapeCollection shapes = ...;
>  // x、y、width、height 參數不能為 Float.NaN：
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //但 IShape.RawFrame 的框架屬性可以未定義。當形狀連結到占位符時這是有意義的。未定義的形狀框架值會從父占位符形狀覆寫。如果該形狀沒有父占位符形狀，則該形狀在基於其 IShape.RawFrame 評估有效框架時會使用預設值。預設值為 x、y、width、height、flipH、flipV 與 rotationAngle 的 0 與 NullableBool.False。例如：
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在形狀會從占位符繼承 x、y、height、flipH、flipV 的值，並覆寫 width=100 與 rotationAngle=0。{code}
```

**返回：**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

返回或設定原始形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，以防在 IShape.getFrame() 中使用未定義的值。x、y、width、height、flipH、flipV 和 rotationAngle 必須被定義（不能為 Float.NaN 或 NullableBool.NotDefined）。上述範例程式碼現在會拋出 ArgumentException 例外。
>  //此適用於以下使用情況：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能為未定義
>  IShapeCollection shapes = ...;
>  // x、y、width、height 參數不能為 Float.NaN：
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //但 IShape.RawFrame 的框架屬性可以未定義。當形狀連結到占位符時這是有意義的。未定義的形狀框架值會被父占位符形狀覆寫。如果該形狀沒有父占位符形狀，則該形狀在根據其 IShape.RawFrame 評估有效框架時會使用預設值。預設值為 x、y、width、height、flipH、flipV 與 rotationAngle 的 0 與 NullableBool.False。例如：
>  IShape shape = ...; // 形狀已連結到占位符
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在形狀會從占位符繼承 x、y、height、flipH、flipV 的值，並覆寫 width=100 與 rotationAngle=0。{code}
> ```


**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

返回或設定形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回的 IShapeFrame 實例之所有屬性皆已定義（非 Float.NaN 或 NotDefined）。指派的 IShapeFrame 實例之所有屬性亦必須已定義（非 Float.NaN 或 NotDefined）。可為 RawFrame 實例屬性指派未定義值。

**返回：**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

返回或設定形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回的 IShapeFrame 實例之所有屬性皆已定義（非 Float.NaN 或 NotDefined）。指派的 IShapeFrame 實例之所有屬性亦必須已定義（非 Float.NaN 或 NotDefined）。可為 RawFrame 實例屬性指派未定義值。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

返回包含形狀線條格式屬性的 LineFormat 物件。備註：對於沒有線條屬性的某些形狀類型，可能返回 null。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。備註：對於沒有 3D 屬性的某些形狀類型，可能返回 null。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回：**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

返回包含套用於形狀的像素效果的 EffectFormat 物件。備註：對於沒有效果屬性的某些形狀類型，可能返回 null。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

返回包含形狀填充格式屬性的 FillFormat 物件。備註：對於沒有填充屬性的某些形狀類型，可能返回 null。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。

**返回：**  
[IImage](../../com.aspose.slides/iimage) - 形狀縮圖。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IWrite  ??? ???
```

返回形狀縮圖。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bounds | int | 形狀縮圖邊界類型。 |
| scaleX | float | X 比例 |
| scaleY | float | Y 比例 |

**返回：**  
[IImage](../../com.aspose.slides/iimage) - 形狀縮圖；若使用 ShapeThumbnailBounds.Appearance 且形狀沒有可見元素，則返回 null。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

將形狀內容儲存為 SVG 檔案。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

將形狀內容儲存為 SVG 檔案。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 產生選項 |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

返回或設定滑鼠點擊時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

返回或設定滑鼠點擊時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

返回或設定滑鼠移過時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

返回或設定滑鼠移過時的超連結。可讀寫 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

返回超連結管理器。唯讀 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**返回：**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

判斷形狀是否隱藏。可讀寫 boolean 。

**返回：**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

判斷形狀是否隱藏。可讀寫 boolean 。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

返回形狀在 Z 軸排序中的位置。Shapes[0] 返回位於 Z 軸最背面的形狀，Shapes[Shapes.Count - 1] 返回位於最前面的形狀。唯讀 int 。

**返回：**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

返回形狀的連接點數量。唯讀 int 。

**返回：**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

返回或設定指定形狀繞 Z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 float。

--------------------

返回值始終已定義（非 Float.NaN）。指派值必須已定義（非 Float.NaN），可為 RawFrame 實例屬性指派未定義值。

**返回：**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

返回或設定指定形狀繞 Z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 float。

--------------------

返回值始終已定義（非 Float.NaN）。指派值必須已定義（非 Float.NaN），可為 RawFrame 實例屬性指派未定義值。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

取得或設定形狀左上角的 x 座標（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回：**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

取得或設定形狀左上角的 x 座標（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

取得或設定形狀左上角的 y 座標（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回：**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

取得或設定形狀左上角的 y 座標（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

取得或設定形狀的寬度（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回：**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

取得或設定形狀的寬度（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

取得或設定形狀的高度（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回：**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

取得或設定形狀的高度（以點為單位）。可讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值亦必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**返回：**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

返回供外掛或其他程式使用的內部簡報範圍識別碼。因為此值可能被使用者或程式重新指派，故不應視為永久唯一鍵。唯讀 long。另請參閱 #getOfficeInteropShapeId.getOfficeInteropShapeId。

**返回：**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

返回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或互操作程式能可靠地在文件任意位置參照該形狀。唯讀 long。另請參閱 #getUniqueId.getUniqueId。

**返回：**  
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

返回或設定與形狀相關聯的替代文字。可讀寫 String。

**返回：**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

返回或設定與形狀相關聯的替代文字。可讀寫 String。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

返回或設定與形狀相關聯的替代文字標題。可讀寫 String。

**返回：**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

返回或設定與形狀相關聯的替代文字標題。可讀寫 String。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

返回或設定形狀的名稱。不得為 null。如有需要請使用空字串。可讀寫 String。

**返回：**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

返回或設定形狀的名稱。不得為 null。如有需要請使用空字串。可讀寫 String。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

取得或設定「標記為裝飾」選項（可讀寫布林值）。

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**  
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

取得或設定「標記為裝飾」選項（可讀寫布林值）。

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

返回形狀的鎖定狀態。唯讀 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**返回：**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

判斷形狀是否已群組。唯讀 boolean。

--------------------

屬性 #getParentGroup.getParentGroup 若形狀已群組則返回父 GroupShape 物件。

**返回：**  
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

返回父 GroupShape 物件（若形狀已群組），否則返回 null。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

--------------------

屬性 #isGrouped.isGrouped 判斷形狀是否已群組。

**返回：**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public  ??  ??  ???  ??.
```

取得根據渲染內容計算出的形狀視覺邊界。

**返回：**  
android.graphics.RectF - 代表形狀在投影片座標中的視覺邊界的 android.graphics.RectF。

--------------------

返回的矩形表示形狀在渲染過程中產生的所有內容在投影片座標空間中的軸對齊邊界。此邊界可能與形狀的模型邊界 #getX.getX/#setX(float)、#getY.getY/#setY(float)、#getWidth.getWidth/#setWidth(float)、#getHeight.getHeight/#setHeight(float) 不同，且若渲染內容超出投影片原點，邊界可能包含負座標。視覺邊界會考慮變換（例如旋轉）、筆畫寬度與接合、文字版面與溢位、SmartArt 幾何形狀以及其他影響最終渲染外觀的版面效果。返回的邊界不會被裁切至投影片矩形。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回形狀的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回投影片的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**  
[IPresentation](../../com.aspose.slides/ipresentation)