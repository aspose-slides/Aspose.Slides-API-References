---
title: IMasterSlide
second_title: Aspose.Slides for Java API 參考文件
description: 代表簡報中的母投影片。
type: docs
url: /zh-hant/com.aspose.slides/imasterslide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

代表簡報中的母投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回母投影片的 HeaderFooter 管理器。 |
| [getTitleStyle()](#getTitleStyle--) | 傳回標題文字的樣式。 |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 依目前的母投影片建立新的母投影片，套用外部主題，並將建立的母投影片套用至所有相依的投影片。 |
| [getBodyStyle()](#getBodyStyle--) | 傳回本文文字的樣式。 |
| [getOtherStyle()](#getOtherStyle--) | 傳回其他文字的樣式。 |
| [getLayoutSlides()](#getLayoutSlides--) | 傳回此母投影片的子版面配置投影片集合。 |
| [getPreserve()](#getPreserve--) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除對應的母投影片。 |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除對應的母投影片。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一張相依於此母投影片的投影片，則傳回 true。 |
| [getDependingSlides()](#getDependingSlides--) | 傳回所有相依於此母投影片的投影片陣列。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回此母投影片的繪圖指引集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


傳回母投影片的 HeaderFooter 管理器。唯讀 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)。

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


依目前的母投影片建立新的母投影片，套用外部主題，並將建立的母投影片套用至所有相依的投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | java.lang.String | 外部主題檔案 (.thmx) 的路徑。 |

**傳回：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 新的主題化 MasterSlide。
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


傳回本文文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

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


傳回此母投影片的子版面配置投影片集合。唯讀 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)。

--------------------

您可以透過使用 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性來存取用於新增/插入/移除/複製版面配置投影片的替代 API。

**傳回：**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除對應的母投影片。備註：Aspose.Slides 永不自行移除任何未使用的母投影片，如需實際移除未使用的母投影片，請呼叫 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-)，可讀寫布林值。

**傳回：**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


判斷當所有跟隨該母投影片的投影片皆被刪除時，是否同時刪除對應的母投影片。備註：Aspose.Slides 永不自行移除任何未使用的母投影片，如需實際移除未使用的母投影片，請呼叫 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-)，可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


如果存在至少一張相依於此母投影片的投影片，則傳回 true。唯讀布林值。

**傳回：**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


傳回所有相依於此母投影片的投影片陣列。

**傳回：**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 陣列，這些投影片相依於此母投影片
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


傳回此母投影片的繪圖指引集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)