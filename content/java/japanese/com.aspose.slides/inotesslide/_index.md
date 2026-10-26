---
title: INotesSlide
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のノートスライドを表します。
type: docs
url: /ja/com.aspose.slides/inotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Represents a notes slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ノートスライドの HeaderFooter マネージャーを返します。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | テキストがある場合、ノートのテキストを含む TextFrame を返します。 |
| [getParentSlide()](#getParentSlide--) | ParentSlide を読み取り専用で返します。 [ISlide](../../com.aspose.slides/islide) |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

ノートスライドの HeaderFooter マネージャーを返します。 読み取り専用 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**戻り値:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

テキストがある場合、ノートのテキストを含む TextFrame を返します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

ParentSlide を読み取り専用で返します。 [ISlide](../../com.aspose.slides/islide)。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)