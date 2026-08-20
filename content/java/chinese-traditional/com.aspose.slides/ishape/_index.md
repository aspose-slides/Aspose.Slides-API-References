---
title: IShape
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上的形狀。
type: docs
url: /zh-hant/com.aspose.slides/ishape/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Represents a shape on a slide.
## 方法

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 判斷此形狀是否為 TextHolder。 |
| [getPlaceholder()](#getPlaceholder--) | 返回形狀的 placeholder。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在則新增 placeholder，並將 placeholder 屬性設定為指定的 placeholder。 |
| [removePlaceholder()](#removePlaceholder--) | 定義此形狀不是 placeholder。 |
| [getCustomData()](#getCustomData--) | 返回形狀的自訂資料。 |
| [getRawFrame()](#getRawFrame--) | 返回或設定原始形狀框架的屬性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或設定原始形狀框架的屬性。 |
| [getFrame()](#getFrame--) | 返回或設定形狀框架的屬性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或設定形狀框架的屬性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形狀線條格式屬性的 LineFormat 物件。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形狀線條格式屬性的 ThreeDFormat 物件。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形狀填充格式屬性的 FillFormat 物件。 |
| [getImage()](#getImage--) | 返回形狀縮圖。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形狀縮圖。 |
| [getHidden()](#getHidden--) | 判斷此形狀是否隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷此形狀是否隱藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形狀在 z-order 中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形狀的連接點數量。 |
| [getRotation()](#getRotation--) | 返回或設定指定形狀繞 z 軸旋轉的度數。 |
| [setRotation(float value)](#setRotation-float-) | 返回或設定指定形狀繞 z 軸旋轉的度數。 |
| [getX()](#getX--) | 取得或設定形狀左上角的 x 坐標（以點為單位）。 |
| [setX(float value)](#setX-float-) | 取得或設定形狀左上角的 x 坐標（以點為單位）。 |
| [getY()](#getY--) | 取得或設定形狀左上角的 y 坐標（以點為單位）。 |
| [setY(float value)](#setY-float-) | 取得或設定形狀左上角的 y 坐標（以點為單位）。 |
| [getWidth()](#getWidth--) | 取得或設定形狀的寬度（以點為單位）。 |
| [setWidth(float value)](#setWidth-float-) | 取得或設定形狀的寬度（以點為單位）。 |
| [getHeight()](#getHeight--) | 取得或設定形狀的高度（以點為單位）。 |
| [setHeight(float value)](#setHeight-float-) | 取得或設定形狀的高度（以點為單位）。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或設定與形狀相關聯的替代文字。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或設定與形狀相關聯的替代文字。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或設定與替代文字相關聯的標題。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或設定與替代文字相關聯的標題。 |
| [getName()](#getName--) | 返回或設定形狀的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定形狀的名稱。 |
| [isDecorative()](#isDecorative--) | 取得或設定「標記為裝飾」選項，可讀寫 boolean。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 取得或設定「標記為裝飾」選項，可讀寫 boolean。 |
| [getShapeLock()](#getShapeLock--) | 返回形狀的鎖定資訊。 |
| [getUniqueId()](#getUniqueId--) | 返回一個內部、以簡報為範圍的識別碼，供外掛或其他程式碼使用。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回一個以投影片為範圍的唯一識別碼，在形狀生命週期內保持不變，使 PowerPoint 或互操作程式碼能可靠地從文件任何位置引用該形狀。 |
| [isGrouped()](#isGrouped--) | 判斷此形狀是否已分組。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [getParentGroup()](#getParentGroup--) | 如果形狀已分組，返回父 GroupShape 物件。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將 Shape 的內容另存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將 Shape 的內容另存為 SVG 檔案。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本的 placeholder 形狀（來自版面配置或母片的形狀，當前形狀繼承自該形狀）。 |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

判斷此形狀是否為 TextHolder。唯讀 boolean。

**返回：**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

返回形狀的 placeholder。唯讀 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

**返回：**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

如果不存在則新增 placeholder，並將 placeholder 屬性設定為指定的 placeholder。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**返回：**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

定義此形狀不是 placeholder。

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回形狀的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

返回或設定原始形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> 嘗試將未定義的框架指派給 IShape.getFrame() 的程式碼在一般情況下是沒有意義的（特別是當父 GroupShape 多層嵌套於其他 GroupShape 時）。例如：
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，禁止在 IShape.getFrame() 中使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須定義（不能是 Float.NaN 或 NullableBool.NotDefined）。上述範例程式碼現在會拋出 ArgumentException 例外。
>  //此規則適用於以下使用情況：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能為未定義
>  IShapeCollection shapes = ...;
>  // x、y、width、height 參數不能是 Float.NaN:
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
>  但是 IShape.RawFrame 的框架屬性可以是未定義的。當形狀連結至 placeholder 時這是合理的。此時未定義的形狀框架值會由父 placeholder 形狀覆寫。如果該形狀沒有父 placeholder，則在根據 IShape.RawFrame 計算有效框架時會使用預設值。預設值為 0，且 NullableBool.False 用於 x、y、width、height、flipH、flipV 與 rotationAngle。例如：
>  IShape shape = ...; // 形狀已連結至 placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在形狀會從 placeholder 繼承 x、y、height、flipH、flipV 的值，並覆寫 width=100 與 rotationAngle=0.
```

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

返回或設定原始形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> 嘗試將未定義的框架指派給 IShape.getFrame() 的程式碼在一般情況下沒有意義（尤其是當父 GroupShape 多層嵌套於其他 GroupShape 時）。例如：
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，禁止在 IShape.getFrame() 中使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須定義（不能是 Float.NaN 或 NullableBool.NotDefined）。上述範例程式碼現在會拋出 ArgumentException 例外。
>  //此規則適用於以下使用情況：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能為未定義
>  IShapeCollection shapes = ...;
>  // x、y、width、height 參數不能為 Float.NaN:
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
>  但 IShape.RawFrame 的框架屬性可以是未定義的。當形狀連結到 placeholder 時這是合理的。此時未定義的形狀框架值會由父 placeholder 形狀覆寫。如果該形狀沒有父 placeholder，則在根據 IShape.RawFrame 計算有效框架時會使用預設值。預設值為 0，且 NullableBool.False 用於 x、y、width、height、flipH、flipV 與 rotationAngle。例如：
>  IShape shape = ...; // 形狀已連結至 placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在形狀會從 placeholder 繼承 x、y、height、flipH、flipV 的值，並覆寫 width=100 與 rotationAngle=0.
```

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

返回或設定形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

返回或設定形狀框架的屬性。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

返回包含形狀線條格式屬性的 LineFormat 物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

返回包含形狀線條格式屬性的 ThreeDFormat 物件。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回：**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

返回包含套用於形狀的像素效果的 EffectFormat 物件。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回包含形狀填充格式屬性的 FillFormat 物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回形狀縮圖。ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default。

**返回：**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

返回形狀縮圖。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

判斷此形狀是否隱藏。可讀寫 boolean。

**返回：**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

判斷此形狀是否隱藏。可讀寫 boolean。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

返回形狀在 z-order 中的位置。Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order。唯讀 int。

**返回：**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

返回形狀的連接點數量。唯讀 int。

**返回：**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

返回或設定指定形狀繞 z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 float。

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**返回：**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

返回或設定指定形狀繞 z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 float。

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

取得或設定形狀左上角的 x 坐標（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**返回：**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

取得或設定形狀左上角的 x 坐標（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

取得或設定形狀左上角的 y 坐標（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**返回：**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

取得或設定形狀左上角的 y 坐標（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

取得或設定形狀的寬度（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**返回：**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

取得或設定形狀的寬度（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

取得或設定形狀的高度（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**返回：**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

取得或設定形狀的高度（以點為單位）。可讀寫 float。

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

返回或設定與形狀相關聯的替代文字。可讀寫 String。

**返回：**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

返回或設定與形狀相關聯的替代文字。可讀寫 String。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

返回或設定與替代文字相關聯的標題。可讀寫 String。

**返回：**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

返回或設定與替代文字相關聯的標題。可讀寫 String。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

返回或設定形狀的名稱。可讀寫 String。

**返回：**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或設定形狀的名稱。可讀寫 String。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

取得或設定「標記為裝飾」選項，可讀寫 boolean。

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
public abstract void setDecorative(boolean value)
```

取得或設定「標記為裝飾」選項，可讀寫 boolean。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

返回形狀的鎖定資訊。唯讀 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**返回：**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

返回一個內部、以簡報為範圍的識別碼，供外掛或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 long。See also \#getOfficeInteropShapeId.getOfficeInteropShapeId。

**返回：**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public long      ...  ... ...
```

返回一個以投影片為範圍的唯一識別碼，在形狀生命週期內保持不變，使 PowerPoint 或互操作程式碼能可靠地從文件任何位置引用該形狀。唯讀 long。See also \#getUniqueId.getUniqueId。

**返回：**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

判斷此形狀是否已分組。唯讀 boolean。

--------------------

Property \#getParentGroup.getParentGroup 若形狀已分組則返回父 GroupShape 物件。

**返回：**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**返回：**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

如果形狀已分組，返回父 GroupShape 物件。否則返回 null。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

--------------------

屬性 \#isGrouped.isGrouped 判斷形狀是否已分組。

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

將 Shape 的內容另存為 SVG 檔案。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

將 Shape 的內容另存為 SVG 檔案。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract   ...  ...
```

返回基本的 placeholder 形狀（來自版面配置或母片的形狀，當前形狀繼承自該形狀）。

--------------------

> ```
> // 取得 placeholder 形狀的所有（母片/版面配置/投影片）動畫效果
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

如果當前形狀未繼承，則返回 null。

**返回：**
[IShape](../../com.aspose.slides/ishape)