---
title: INotesSlide
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示簡報中的備註投影片。
type: docs
url: /zh-hant/com.aspose.slides/inotesslide/
---
**所有已實作介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

表示簡報中的備註投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 回傳備註投影片的 HeaderFooter 管理器。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 如果存在，回傳包含備註文字的 TextFrame。 |
| [getParentSlide()](#getParentSlide--) | 回傳 ParentSlide 唯讀 [ISlide](../../com.aspose.slides/islide)。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

回傳備註投影片的 HeaderFooter 管理器。唯讀 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**回傳:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

如果存在，回傳包含備註文字的 TextFrame。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**回傳:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

回傳 ParentSlide 唯讀 [ISlide](../../com.aspose.slides/islide)。

**回傳:**  
[ISlide](../../com.aspose.slides/islide)