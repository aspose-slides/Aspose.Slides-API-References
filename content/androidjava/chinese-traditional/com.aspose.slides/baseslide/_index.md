---
title: BaseSlide
second_title: Aspose.Slides for Android Java API 參考
description: 代表所有投影片類型的共用資料。
type: docs
url: /zh-hant/com.aspose.slides/baseslide/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

代表所有投影片類型的共用資料。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapes()](#getShapes--) | 傳回投影片的形狀。 |
| [getControls()](#getControls--) | 傳回投影片上 ActiveX 控制項的集合。 |
| [getName()](#getName--) | 傳回或設定投影片的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回或設定投影片的名稱。 |
| [getSlideId()](#getSlideId--) | 傳回投影片的 ID。 |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 判斷兩個 IBaseSlide 實例是否相等。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有段落的所有可接受形狀中合併具有相同格式的文字片段。 |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | 在所有段落的所有可接受形狀中合併具有相同格式的文字片段。 |
| [createThemeEffective()](#createThemeEffective--) | 傳回此投影片的有效佈景主題。 |
| [getCustomData()](#getCustomData--) | 傳回投影片的自訂資料。 |
| [getTimeline()](#getTimeline--) | 傳回動畫時間軸物件。 |
| [getSlideShowTransition()](#getSlideShowTransition--) | 傳回 Transition 物件，其中包含指定投影片在投影片放映期間如何前進的資訊。 |
| [getBackground()](#getBackground--) | 傳回投影片的背景。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對包含的超連結的簡易存取。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母片上的形狀。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母片上的形狀。 |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 尋找具有指定替代文字的形狀的第一個出現。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | 傳回 IPresentation 介面。 |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


傳回投影片的形狀。唯讀 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**傳回：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


傳回投影片上 ActiveX 控制項的集合。唯讀 [IControlCollection](../../com.aspose.slides/icontrolcollection)。

**傳回：**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


傳回或設定投影片的名稱。讀寫 String。

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


傳回或設定投影片的名稱。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


傳回投影片的 ID。唯讀 long。

**傳回：**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


判斷兩個 IBaseSlide 實例是否相等。回傳值根據投影片的結構和靜態內容計算。若所有形狀、樣式、文字、動畫及其他設定等全部相等，則兩個投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，及動態內容，例如日期佔位符的當前日期值。

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

**傳回：**
boolean -  **true**  若指定的 IBaseSlide 等於目前的 IBaseSlide，則為 true；否則為 **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


在所有段落的所有可接受形狀中合併具有相同格式的文字片段。

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


在所有段落的所有可接受形狀中合併具有相同格式的文字片段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


傳回此投影片的有效佈景主題。

**傳回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


傳回投影片的自訂資料。唯讀 [ICustomData](../../com.aspose.slides/icustomdata)。

**傳回：**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


傳回動畫時間軸物件。唯讀 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)。

**傳回：**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


傳回 Transition 物件，其中包含指定投影片在投影片放映期間如何前進的資訊。唯讀 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)。

**傳回：**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


傳回投影片的背景。唯讀 [IBackground](../../com.aspose.slides/ibackground)。

**傳回：**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


提供對包含的超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**傳回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


指定是否在投影片上顯示母片上的形狀。對於母片本身，此屬性始終傳回 false。讀寫 boolean。

**傳回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


指定是否在投影片上顯示母片上的形狀。對於母片本身，此屬性始終傳回 false。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


尋找具有指定替代文字的形狀的第一個出現。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| altText | java.lang.String | 替代文字。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - Shape 物件或 null。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


傳回 IPresentation 介面。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


傳回基礎投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)