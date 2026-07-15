---
title: ILayoutSlide
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個版面投影片。
type: docs
url: /zh-hant/com.aspose.slides/ilayoutslide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

表示一個版面投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回版面投影片的 HeaderFooter 管理器。 |
| [getPlaceholderManager()](#getPlaceholderManager--) | 傳回版面投影片的 placeholder 管理器。 |
| [getMasterSlide()](#getMasterSlide--) | 傳回或設定版面的 master slide。 |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 傳回或設定版面的 master slide。 |
| [getLayoutType()](#getLayoutType--) | 傳回此版面投影片的版面類型。 |
| [hasDependingSlides()](#hasDependingSlides--) | 如果存在至少一個依賴此版面投影片的投影片，則傳回 true。 |
| [getDependingSlides()](#getDependingSlides--) | 傳回包含所有依賴此版面投影片的投影片的陣列。 |
| [remove()](#remove--) | 從簡報中移除版面。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回版面投影片的 drawing guides 集合。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

傳回版面投影片的 HeaderFooter 管理器。唯讀 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)。

**傳回：**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

傳回版面投影片的 placeholder 管理器。唯讀 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)。

**傳回：**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

傳回或設定版面的 master slide。讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**傳回：**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

傳回或設定版面的 master slide。讀寫 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

傳回此版面投影片的版面類型。唯讀 [SlideLayoutType](../../com.aspose.slides/slidelayouttype)。

**傳回：**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

如果存在至少一個依賴此版面投影片的投影片，則傳回 true。唯讀 boolean。

**傳回：**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

傳回包含所有依賴此版面投影片的投影片的陣列。

**傳回：**
com.aspose.slides.ISlide[] - 包含所有依賴此版面投影片的投影片的陣列
### remove() {#remove--}
```
public abstract void remove()
```

從簡報中移除版面。
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

傳回版面投影片的 drawing guides 集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // 在投影片中心左側加入新的垂直繪圖參考線
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)