---
title: IShape
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片上的形狀。
type: docs
url: /zh-hant/com.aspose.slides/ishape/
---
**所有已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

表示投影片上的形狀。

## 方法

| 方法 | 說明 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 判斷形狀是否為 TextHolder。 |
| [getPlaceholder()](#getPlaceholder--) | 返回形狀的占位符。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 如果不存在則新增占位符，並將占位符屬性設定為指定的占位符。 |
| [removePlaceholder()](#removePlaceholder--) | 定義此形狀不是占位符。 |
| [getCustomData()](#getCustomData--) | 返回形狀的自訂資料。 |
| [getRawFrame()](#getRawFrame--) | 返回或設定原始形狀框架的屬性。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 返回或設定原始形狀框架的屬性。 |
| [getFrame()](#getFrame--) | 返回或設定原始形狀框架的屬性。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或設定原始形狀框架的屬性。 |
| [getLineFormat()](#getLineFormat--) | 返回包含形狀線條格式屬性的 LineFormat 物件。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回包含形狀線條格式屬性的 ThreeDFormat 物件。 |
| [getEffectFormat()](#getEffectFormat--) | 返回包含套用於形狀的像素效果的 EffectFormat 物件。 |
| [getFillFormat()](#getFillFormat--) | 返回包含形狀填充格式屬性的 FillFormat 物件。 |
| [getImage()](#getImage--) | 返回形狀的縮圖。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 返回形狀的縮圖。 |
| [getHidden()](#getHidden--) | 判斷形狀是否被隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷形狀是否被隱藏。 |
| [getZOrderPosition()](#getZOrderPosition--) | 返回形狀在 Z 軸順序中的位置。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 返回形狀的連接點數量。 |
| [getRotation()](#getRotation--) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。 |
| [setRotation(float value)](#setRotation-float-) | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。 |
| [getX()](#getX--) | 取得或設定形狀左上角的 X 座標（以點為單位）。 |
| [setX(float value)](#setX-float-) | 取得或設定形狀左上角的 X 座標（以點為單位）。 |
| [getY()](#getY--) | 取得或設定形狀左上角的 Y 座標（以點為單位）。 |
| [setY(float value)](#setY-float-) | 取得或設定形狀左上角的 Y 座標（以點為單位）。 |
| [getWidth()](#getWidth--) | 取得或設定形狀的寬度（以點為單位）。 |
| [setWidth(float value)](#setWidth-float-) | 取得或設定形狀的寬度（以點為單位）。 |
| [getHeight()](#getHeight--) | 取得或設定形狀的高度（以點為單位）。 |
| [setHeight(float value)](#setHeight-float-) | 取得或設定形狀的高度（以點為單位）。 |
| [getAlternativeText()](#getAlternativeText--) | 返回或設定與形狀相關聯的替代文字。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 返回或設定與形狀相關聯的替代文字。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 返回或設定與形狀相關聯的替代文字標題。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 返回或設定與形狀相關聯的替代文字標題。 |
| [getName()](#getName--) | 返回或設定形狀的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定形狀的名稱。 |
| [isDecorative()](#isDecorative--) | 取得或設定「標記為裝飾」選項的讀寫 boolean。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 取得或設定「標記為裝飾」選項的讀寫 boolean。 |
| [getShapeLock()](#getShapeLock--) | 返回形狀的鎖定。 |
| [getUniqueId()](#getUniqueId--) | 返回供外掛程式或其他程式碼使用的內部、簡報範圍的識別碼。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 返回在投影片範圍內唯一的識別碼，此識別碼在形狀生命週期內保持不變，讓 PowerPoint 或跨語言程式碼能可靠地從文件任何位置參照該形狀。 |
| [isGrouped()](#isGrouped--) | 判斷形狀是否為群組。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 屬性指定形狀在黑白顯示模式下的呈現方式。 |
| [getParentGroup()](#getParentGroup--) | 如果形狀已群組，返回其父 GroupShape 物件。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將 Shape 的內容另存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將 Shape 的內容另存為 SVG 檔案。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 返回基本的占位符形狀（來自佈局或母片且被目前形狀繼承的形狀）。 |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

判斷形狀是否為 TextHolder。唯讀 boolean。

**返回:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

返回形狀的占位符。唯讀 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

**返回:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

如果不存在則新增占位符，並將占位符屬性設定為指定的占位符。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 要複製內容的占位符。 |

**返回:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新的 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

定義此形狀不是占位符。

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回形狀的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

返回或設定原始形狀框架的屬性。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，不允許在 IShape.getFrame() 中使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須被定義（不可為 Float.NaN 或 NullableBool.NotDefined）。上述範例程式碼現在會拋出 ArgumentException 例外。
>  //這適用於以下使用情境：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能未定義
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape 已連結至占位符
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在 shape 繼承來自占位符的 x、y、height、flipH、flipV 值，且將 width 設為 100、rotationAngle 設為 0。
> ```

**返回:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

返回或設定原始形狀框架的屬性。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //或
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //此類程式碼可能導致不明確的情況。因此已加入限制，不允許在 IShape.getFrame() 中使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須被定義（不可為 Float.NaN 或 NullableBool.NotDefined）。上述範例程式碼現在會拋出 ArgumentException 例外。
>  //這適用於以下使用情境：
>  IShape shape = ...;
>  shape.setFrame(...); // 不能未定義
>  IShapeCollection shapes = ...;
>  // x, y, width, height 參數不能為 Float.NaN：
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape 已連結至占位符
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在 shape 繼承來自占位符的 x、y、height、flipH、flipV 值，並將 width 設為 100、rotationAngle 設為 0.
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

返回或設定形狀框架的屬性。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回的 IShapeFrame 實例中每個屬性的值皆已定義（不是 NaN 或 NotDefined）。指派給 IShapeFrame 實例的每個屬性值也必須已定義（不能是 NaN 或 NotDefined）。您可以為 RawFrame 實例屬性設定未定義的值。

**返回:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

返回或設定形狀框架的屬性。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返回的 IShapeFrame 實例中每個屬性的值皆已定義（不是 NaN 或 NotDefined）。指派給 IShapeFrame 實例的每個屬性值也必須已定義（不能是 NaN 或 NotDefined）。您可以為 RawFrame 實例屬性設定未定義的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

返回包含形狀線條格式屬性的 LineFormat 物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

返回包含形狀線條格式屬性的 ThreeDFormat 物件。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

返回包含套用於形狀的像素效果的 EffectFormat 物件。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回包含形狀填充格式屬性的 FillFormat 物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖範圍類型。

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 形狀縮圖。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

返回形狀縮圖。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bounds | int | 形狀縮圖範圍類型。 |
| scaleX | float | X 軸比例 |
| scaleY | float | Y 軸比例 |

**返回:**  
[IImage](../../com.aspose.slides/iimage) - 形狀縮圖；若使用 ShapeThumbnailBounds.Appearance 且形狀沒有可見元素，則返回 null。

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

判斷形狀是否被隱藏。讀寫 boolean。

**返回:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

判斷形狀是否被隱藏。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

返回形狀在 Z 軸順序中的位置。Shapes[0] 代表最底層形狀，Shapes[Shapes.Count - 1] 代表最上層形狀。唯讀 int。

**返回:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

返回形狀的連接點數量。唯讀 int。

**返回:**  
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀寫 float。

--------------------

返回值始終已定義（不是 Float.NaN）。指派的值必須已定義（不是 Float.NaN）。您可以為 RawFrame 實例屬性設定未定義的值。

**返回:**  
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀寫 float。

--------------------

返回值始終已定義（不是 Float.NaN）。指派的值必須已定義（不是 Float.NaN）。您可以為 RawFrame 實例屬性設定未定義的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

取得或設定形狀左上角的 X 座標（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回:**  
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

取得或設定形狀左上角的 X 座標（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

取得或設定形狀左上角的 Y 座標（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回:**  
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

取得或設定形狀左上角的 Y 座標（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

取得或設定形狀的寬度（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回:**  
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

取得或設定形狀的寬度（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

取得或設定形狀的高度（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**返回:**  
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

取得或設定形狀的高度（以點為單位）。讀寫 float。

--------------------

返回的值始終已定義且永不為 Float.NaN。指派的值也必須已定義；僅可將 Float.NaN 指派給 RawFrame 實例的屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

返回或設定與形狀相關聯的替代文字。讀寫 String。

**返回:**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

返回或設定與形狀相關聯的替代文字。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

返回或設定與形狀相關聯的替代文字標題。讀寫 String。

**返回:**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

返回或設定與形狀相關聯的替代文字標題。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

返回或設定形狀的名稱。讀寫 String。

**返回:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回或設定形狀的名稱。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

取得或設定「標記為裝飾」選項的讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

取得或設定「標記為裝飾」選項的讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

返回形狀的鎖定。唯讀 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**返回:**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

返回供外掛程式或其他程式碼使用的內部、簡報範圍的識別碼。因為此值可能會被使用者或程式重新指派，不能被視為永久唯一鍵。唯讀 long。另請參閱 \#getOfficeInteropShapeId.getOfficeInteropShapeId。

**返回:**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

返回在投影片範圍內唯一的識別碼，此識別碼在形狀生命週期內保持不變，讓 PowerPoint 或跨語言程式碼能可靠地從文件任何位置參照該形狀。唯讀 long。另請參閱 \#getUniqueId.getUniqueId。

**返回:**  
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

判斷形狀是否為群組。唯讀 boolean。

--------------------

屬性 \#getParentGroup.getParentGroup 返回父 GroupShape 物件（如果形狀已群組）。

**返回:**  
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**返回:**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

返回父 GroupShape 物件（如果形狀已群組），否則返回 null。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

--------------------

屬性 \#isGrouped.isGrouped 判斷形狀是否為群組。

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

將 Shape 的內容另存為 SVG 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

將 Shape 的內容另存為 SVG 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 產生選項 |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

返回基本的占位符形狀（來自佈局或母片且被目前形狀繼承的形狀）。

--------------------

> ```
> // 取得占位符形狀的所有（母片/版面/投影片）動畫效果
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

若目前形狀未被繼承，則返回 null。

**返回:**  
[IShape](../../com.aspose.slides/ishape)