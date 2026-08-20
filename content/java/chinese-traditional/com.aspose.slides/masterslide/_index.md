---
title: MasterSlide
second_title: Aspose.Slides for Java API 參考
description: 表示簡報中的母投影片。
type: docs
url: /zh-hant/com.aspose.slides/masterslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

表示簡報中的母投影片。

## 方法

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回母投影片的 HeaderFooter 管理員。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 建立基於目前投影片的新母投影片，套用外部佈景主題，並將此新母投影片套用至所有相依投影片。 |
| [getTitleStyle()](#getTitleStyle--) | 傳回標題文字的樣式。 |
| [getBodyStyle()](#getBodyStyle--) | 傳回內文文字的樣式。 |
| [getOtherStyle()](#getOtherStyle--) | 傳回其他文字的樣式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 傳回此母投影片的子版面投影片集合。 |
| [getPreserve()](#getPreserve--) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除相應的母投影片。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除相應的母投影片。 |
| [getDependingSlides()](#getDependingSlides--) | 傳回一個包含所有依賴此母投影片的投影片的陣列。 |
| [hasDependingSlides()](#hasDependingSlides--) | 若存在至少一個依賴此母投影片的投影片，則傳回 true。 |
| [getThemeManager()](#getThemeManager--) | 傳回佈景主題管理員。 |
| [getName()](#getName--) | 傳回或設定母投影片的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回或設定母投影片的名稱。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母投影片上的圖形。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母投影片上的圖形。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回母投影片的繪圖指引集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

傳回母投影片的 HeaderFooter 管理員。唯讀 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**傳回:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

建立基於目前投影片的新母投影片，套用外部佈景主題，並將此新母投影片套用至所有相依投影片。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 外部佈景主題檔案的路徑 (.thmx)。 |

**傳回:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的佈景主題化 MasterSlide。

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

傳回標題文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

傳回內文文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

傳回其他文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

傳回此母投影片的子版面投影片集合。唯讀 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以透過使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性來存取可用於新增/插入/移除/複製版面投影片的替代 API。

**傳回:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除相應的母投影片。注意：Aspose.Slides 永不會自行移除任何未使用的母投影片，若要實際移除未使用的母投影片，請呼叫 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) 可讀寫 boolean 。

**傳回:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除相應的母投影片。注意：Aspose.Slides 永不會自行移除任何未使用的母投影片，若要實際移除未使用的母投影片，請呼叫 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) 可讀寫 boolean 。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

傳回一個包含所有依賴此母投影片的投影片的陣列。

**傳回:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 陣列

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

若存在至少一個依賴此母投影片的投影片，則傳回 true。唯讀 boolean 。

**傳回:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

傳回佈景主題管理員。唯讀 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**傳回:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

傳回或設定母投影片的名稱。可讀寫 String。

**傳回:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

傳回或設定母投影片的名稱。可讀寫 String。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在投影片上顯示母投影片上的圖形。對於母投影片本身，此屬性總是傳回 false。可讀寫 boolean 。

**傳回:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在投影片上顯示母投影片上的圖形。對於母投影片本身，此屬性總是傳回 false。可讀寫 boolean 。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

傳回母投影片的繪圖指引集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // 在投影片中心右側新增垂直繪圖指引
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)