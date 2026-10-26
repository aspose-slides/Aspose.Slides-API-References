---
title: IBaseSlide
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 代表所有投影片類型的共同資料。
type: docs
url: /zh-hant/com.aspose.slides/ibaseslide/
---
**已實作的介面:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

代表所有投影片類型的共同資料。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapes()](#getShapes--) | 返回投影片的形狀。 |
| [getControls()](#getControls--) | 返回投影片上 ActiveX 控制項的集合。 |
| [getName()](#getName--) | 返回或設定投影片的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定投影片的名稱。 |
| [getSlideId()](#getSlideId--) | 返回投影片的 ID。 |
| [getCustomData()](#getCustomData--) | 返回投影片的自訂資料。 |
| [getTimeline()](#getTimeline--) | 返回動畫時間軸物件。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 返回 TransitionEx 物件，其中包含指定投影片在投影片秀期間如何前進的資訊。 |
| [getBackground()](#getBackground--) | 返回投影片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對所含超連結的便捷存取。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母片投影片上的形狀是否應顯示於投影片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母片投影片上的形狀是否應顯示於投影片上。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 尋找具有指定替代文字的形狀的首次出現。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有可接受的形狀中，將所有段落的相同格式的文字片段合併。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 判斷兩個 IBaseSlide 實例是否相等。 |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


返回投影片的形狀。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


返回投影片上 ActiveX 控制項的集合。唯讀 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**Returns:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


返回或設定投影片的名稱。讀寫 String。

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


返回或設定投影片的名稱。讀寫 String。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


返回投影片的 ID。唯讀 long。

**Returns:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


返回投影片的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


返回動畫時間軸物件。唯讀 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


返回 TransitionEx 物件，其中包含指定投影片在投影片秀期間如何前進的資訊。唯讀 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


返回投影片的背景。唯讀 [IBackground](../../com.aspose.slides/ibackground)。

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


提供對所含超連結的便捷存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


指定母片投影片上的形狀是否應顯示於投影片上。對於母片本身，此屬性始終返回 false。讀寫 boolean。

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


指定母片投影片上的形狀是否應顯示於投影片上。對於母片本身，此屬性始終返回 false。讀寫 boolean。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


尋找具有指定替代文字的形狀的首次出現。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| altText | java.lang.String | 替代文字。 |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx 物件或 null。
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


在所有可接受的形狀中，將所有段落的相同格式的文字片段合併。

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


判斷兩個 IBaseSlide 實例是否相等。返回值根據投影片的結構和靜態內容計算。若所有形狀、樣式、文字、動畫以及其他設定等全部相等，則兩個投影片相等。比較不會考慮唯一識別碼的值，例如 SlideId，亦不會考慮動態內容，例如日期佔位符中的當前日期值。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要與目前的 IBaseSlide 比較的 IBaseSlide。 |

**Returns:**
boolean - **true** 若指定的 IBaseSlide 等於目前的 IBaseSlide，否則 **false**。