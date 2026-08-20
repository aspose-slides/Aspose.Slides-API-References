---
title: BaseSlide
second_title: Aspose.Slides Java API 參考
description: 代表所有投影片類型的共通資料。
type: docs
url: /zh-hant/com.aspose.slides/baseslide/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

代表所有投影片類型的共通資料。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapes()](#getShapes--) | 返回投影片的形狀。 |
| [getControls()](#getControls--) | 返回投影片上 ActiveX 控制項的集合。 |
| [getName()](#getName--) | 返回或設定投影片的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回或設定投影片的名稱。 |
| [getSlideId()](#getSlideId--) | 返回投影片的 ID。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 判斷兩個 IBaseSlide 實例是否相等。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 將所有可接受形狀中所有段落的相同格式文字合併。 |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | 將所有可接受形狀中所有段落的相同格式文字合併。 |
| [createThemeEffective()](#createThemeEffective--) | 返回此投影片的有效佈景主題。 |
| [getCustomData()](#getCustomData--) | 返回投影片的自訂資料。 |
| [getTimeline()](#getTimeline--) | 返回動畫時間軸物件。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 返回 Transition 物件，該物件包含有關指定投影片在投影片放映期間如何前進的資訊。 |
| [getBackground()](#getBackground--) | 返回投影片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對包含的超連結的簡易存取。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母片上的形狀是否應在投影片上顯示。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母片上的形狀是否應在投影片上顯示。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 尋找具有指定替代文字的形狀的第一個出現位置。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | 返回 IPresentation 介面。 |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

返回投影片的形狀。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

返回投影片上 ActiveX 控制項的集合。唯讀 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**返回：**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

返回或設定投影片的名稱。讀寫 String。

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

返回或設定投影片的名稱。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

返回投影片的 ID。唯讀 long。

**返回：**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

判斷兩個 IBaseSlide 實例是否相等。返回值是根據投影片的結構和靜態內容計算的。若所有形狀、樣式、文字、動畫和其他設定等皆相等，則兩張投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，亦不考慮動態內容，例如日期占位符中的當前日期值。

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要與目前的 IBaseSlide 比較的 IBaseSlide。 |

**返回：**
boolean - **true** 表示指定的 IBaseSlide 與目前的 IBaseSlide 相等；否則 **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

將所有可接受形狀中所有段落的相同格式文字合併。
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

將所有可接受形狀中所有段落的相同格式文字合併。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

返回此投影片的有效佈景主題。

**返回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

返回投影片的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

返回動畫時間軸物件。唯讀 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**返回：**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

返回 Transition 物件，該物件包含有關指定投影片在投影片放映期間如何前進的資訊。唯讀 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**返回：**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

返回投影片的背景。唯讀 [IBackground](../../com.aspose.slides/ibackground)。

**返回：**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供對包含的超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

指定母片上的形狀是否應在投影片上顯示。對於母片本身，此屬性總是返回 false。讀寫 boolean。

**返回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

指定母片上的形狀是否應在投影片上顯示。對於母片本身，此屬性總是返回 false。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

尋找具有指定替代文字的形狀的第一個出現位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| altText | java.lang.String | 替代文字。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - Shape 物件或 null。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 IPresentation 介面。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回基礎投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)