---
title: MasterSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示簡報中的母投影片。
type: docs
url: /zh-hant/com.aspose.slides/masterslide/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有已實作的介面:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

表示簡報中的母投影片。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 回傳母投影片的 HeaderFooter 管理器。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 建立一個基於目前投影片的新母投影片，套用外部佈景主題，並將建立的母投影片套用至所有相依的投影片。 |
| [getTitleStyle()](#getTitleStyle--) | 回傳標題文字的樣式。 |
| [getBodyStyle()](#getBodyStyle--) | 回傳內文文字的樣式。 |
| [getOtherStyle()](#getOtherStyle--) | 回傳其他文字的樣式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 回傳此母投影片的子版面配置投影片集合。 |
| [getPreserve()](#getPreserve--) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否刪除相應的母投影片。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否刪除相應的母投影片。 |
| [getDependingSlides()](#getDependingSlides--) | 回傳一個包含所有相依於此母投影片的投影片之陣列。 |
| [hasDependingSlides()](#hasDependingSlides--) | 若存在至少一個相依於此母投影片的投影片，則回傳 true。 |
| [getThemeManager()](#getThemeManager--) | 回傳 theme manager。 |
| [getName()](#getName--) | 回傳或設定母投影片的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 回傳或設定母投影片的名稱。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母投影片上的圖形是否應顯示於投影片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母投影片上的圖形是否應顯示於投影片上。 |
| [getDrawingGuides()](#getDrawingGuides--) | 回傳母投影片的繪圖指南集合。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

回傳母投影片的 HeaderFooter 管理器。唯讀 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**回傳:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

建立一個基於目前投影片的新母投影片，套用外部佈景主題，並將建立的母投影片套用至所有相依的投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 外部佈景主題檔案 (.thmx) 的路徑。 |

**回傳:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的已套用佈景的 MasterSlide。

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

回傳標題文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**回傳:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

回傳內文文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**回傳:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

回傳其他文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**回傳:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

回傳此母投影片的子版面配置投影片集合。唯讀 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以透過使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性，存取用於新增/插入/移除/複製版面配置投影片的替代 API。

**回傳:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

判斷當所有跟隨該母投影片的投影片皆被刪除時，是否刪除相應的母投影片。注意：Aspose.Slides 永不會自行移除任何未使用的母投影片，若要實際移除未使用的母投影片，請呼叫 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-)，讀寫 boolean 。

**回傳:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

判斷當所有跟隨該母投影片的投影片皆被刪除時，是否刪除相應的母投影片。注意：Aspose.Slides 永不會自行移除任何未使用的母投影片，若要實際移除未使用的母投影片，請呼叫 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-)，讀寫 boolean 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

回傳一個包含所有相依於此母投影片的投影片之陣列。

**回傳:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 陣列。

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

若存在至少一個相依於此母投影片的投影片，則回傳 true。唯讀 boolean 。

**回傳:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

回傳 theme manager。唯讀 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)。

**回傳:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

回傳或設定母投影片的名稱。讀寫 String。

**回傳:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

回傳或設定母投影片的名稱。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定母投影片上的圖形是否應顯示於投影片上。對於母投影片本身，此屬性永遠回傳 false。讀寫 boolean 。

**回傳:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定母投影片上的圖形是否應顯示於投影片上。對於母投影片本身，此屬性永遠回傳 false。讀寫 boolean 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

回傳母投影片的繪圖指南集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // 將新的垂直繪圖指示線添加到投影片中心右側
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**回傳:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)