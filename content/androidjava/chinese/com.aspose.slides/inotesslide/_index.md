---
title: INotesSlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿中的备注幻灯片。
type: docs
url: /zh/com.aspose.slides/inotesslide/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

表示演示文稿中的备注幻灯片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回备注幻灯片的 HeaderFooter manager。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 如果存在，则返回包含备注文本的 TextFrame。 |
| [getParentSlide()](#getParentSlide--) | 返回只读的 ParentSlide [ISlide](../../com.aspose.slides/islide)。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


返回备注幻灯片的 HeaderFooter manager。只读 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**返回：**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


如果存在，则返回包含备注文本的 TextFrame。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


返回只读的 ParentSlide [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)