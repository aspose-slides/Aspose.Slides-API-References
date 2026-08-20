---
title: IBaseSlide
second_title: Aspose.Slides for Java API 參考
description: 表示所有投影片類型的共通資料。
type: docs
url: /zh-hant/com.aspose.slides/ibaseslide/
---
**所有已實作的介面:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

表示所有投影片類型的共通資料。

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
| [getSlideShowTransition()](#getSlideShowTransition--) | 返回 TransitionEx 物件，該物件包含關於在投影片放映期間指定投影片如何前進的資訊。 |
| [getBackground()](#getBackground--) | 返回投影片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對包含的超連結的簡易存取。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母投影片的形狀。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母投影片的形狀。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 尋找第一個具有指定替代文字的形狀。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 將所有可接受形狀中所有段落的相同格式文字串合併。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 判斷兩個 IBaseSlide 實例是否相等。 |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


返回投影片的形狀。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


返回投影片上 ActiveX 控制項的集合。唯讀 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**返回:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


返回或設定投影片的名稱。讀寫 String。

**返回:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


返回或設定投影片的名稱。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


返回投影片的 ID。唯讀 long。

**返回:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


返回投影片的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


返回動畫時間軸物件。唯讀 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**返回:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


返回 TransitionEx 物件，該物件包含關於在投影片放映期間指定投影片如何前進的資訊。唯讀 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**返回:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


返回投影片的背景。唯讀 [IBackground](../../com.aspose.slides/ibackground)。

**返回:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


提供對包含的超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


指定是否在投影片上顯示母投影片的形狀。對於母投影片本身，此屬性永遠返回 false。讀寫 boolean。

**返回:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


指定是否在投影片上顯示母投影片的形狀。對於母投影片本身，此屬性永遠返回 false。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


尋找第一個具有指定替代文字的形狀。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| altText | java.lang.String | 替代文字。 |

**返回:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx 物件或 null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


將所有可接受形狀中所有段落的相同格式文字串合併。
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


判斷兩個 IBaseSlide 實例是否相等。返回值是根據投影片的結構和靜態內容計算的。若所有形狀、樣式、文字、動畫及其他設定等均相等，則兩個投影片相等。比較時不考慮唯一識別值，例如 SlideId，以及動態內容，例如日期佔位符中的目前日期值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要與目前的 IBaseSlide 進行比較的 IBaseSlide。 |

**返回:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.