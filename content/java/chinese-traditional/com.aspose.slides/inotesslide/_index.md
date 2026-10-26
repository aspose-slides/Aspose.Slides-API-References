---
title: INotesSlide
second_title: Aspose.Slides for Java API 參考
description: 表示簡報中的備註投影片。
type: docs
url: /zh-hant/com.aspose.slides/inotesslide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

代表簡報中的備註投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回備註投影片的 HeaderFooter 管理器。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 如果存在，返回包含備註文字的 TextFrame（若有的話）。 |
| [getParentSlide()](#getParentSlide--) | 返回唯讀的 ParentSlide [ISlide](../../com.aspose.slides/islide)。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

返回備註投影片的 HeaderFooter 管理器。唯讀 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**返回：**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

如果存在，返回包含備註文字的 TextFrame（若有的話）。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

返回唯讀的 ParentSlide [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)