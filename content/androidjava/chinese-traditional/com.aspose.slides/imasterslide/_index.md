---
title: IMasterSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示簡報中的 master slide。
type: docs
url: /zh-hant/com.aspose.slides/imasterslide/
---
**已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

表示簡報中的 master slide。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回 master slide 的 HeaderFooter 管理員。 |
| [getTitleStyle()](#getTitleStyle--) | 傳回標題文字的樣式。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 建立一個基於目前 master slide 的新 master slide，套用外部佈景主題，並將建立的 master slide 套用至所有相依的投影片。 |
| [getBodyStyle()](#getBodyStyle--) | 傳回內文文字的樣式。 |
| [getOtherStyle()](#getOtherStyle--) | 傳回其他文字的樣式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 傳回此 master slide 的子版面配置投影片集合。 |
| [getPreserve()](#getPreserve--) | 判斷當所有跟隨該 master 的投影片皆被刪除時，對應的 master 是否會被刪除。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 判斷當所有跟隨該 master 的投影片皆被刪除時，對應的 master 是否會被刪除。 |
| [hasDependingSlides()](#hasDependingSlides--) | 若至少有一個投影片相依於此 master slide，則傳回 true。 |
| [getDependingSlides()](#getDependingSlides--) | 傳回一個包含所有相依於此 master slide 的投影片之陣列。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回此 master slide 的繪圖參考線集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

傳回 master slide 的 HeaderFooter 管理員。唯讀 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

**傳回：**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

傳回標題文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

建立一個基於目前 master slide 的新 master slide，套用外部佈景主題，並將建立的 master slide 套用至所有相依的投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 外部佈景主題檔案 (.thmx) 的路徑。 |

**傳回：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的有佈景的 MasterSlide。
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

傳回內文文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

傳回其他文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

傳回此 master slide 的子版面配置投影片集合。唯讀 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以透過使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性，存取用於新增/插入/移除/複製版面配置投影片的替代 API。

**傳回：**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

判斷當所有跟隨該 master 的投影片皆被刪除時，對應的 master 是否會被刪除。備註：Aspose.Slides 不會自行移除任何未使用的 master，若要實際移除未使用的 master，請呼叫 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) 可讀寫 boolean。

**傳回：**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

判斷當所有跟隨該 master 的投影片皆被刪除時，對應的 master 是否會被刪除。備註：Aspose.Slides 不會自行移除任何未使用的 master，若要實際移除未使用的 master，請呼叫 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

若存在至少一個相依於此 master slide 的投影片，則傳回 true。唯讀 boolean。

**傳回：**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

傳回一個包含所有相依於此 master slide 的投影片之陣列。

**傳回：**
com.aspose.slides.ISlide[] - 陣列，包含相依於此 master slide 的 [ISlide](../../com.aspose.slides/islide)。
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

傳回此 master slide 的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // 在投影片中心右側加入新的垂直繪圖參考線
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)