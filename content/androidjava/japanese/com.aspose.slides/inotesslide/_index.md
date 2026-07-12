---
title: INotesSlide
second_title: Aspose.Slides の Android 用 Java API リファレンス
description: プレゼンテーションのノートスライドを表します。
type: docs
url: /ja/com.aspose.slides/inotesslide/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

プレゼンテーションのノートスライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ノートスライドの HeaderFooter マネージャーを返します。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 存在する場合、ノートのテキストを含む TextFrame を返します。 |
| [getParentSlide()](#getParentSlide--) | 読み取り専用 [ISlide](../../com.aspose.slides/islide) の ParentSlide を返します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

ノートスライドの HeaderFooter マネージャーを返します。読み取り専用 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**戻り値:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

存在する場合、ノートのテキストを含む TextFrame を返します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

読み取り専用 [ISlide](../../com.aspose.slides/islide) の ParentSlide を返します。

**戻り値:**  
[ISlide](../../com.aspose.slides/islide)