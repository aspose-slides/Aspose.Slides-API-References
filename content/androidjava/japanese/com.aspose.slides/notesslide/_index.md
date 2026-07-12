---
title: NotesSlide
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: プレゼンテーション内のノートスライドを表します。
type: docs
url: /ja/com.aspose.slides/notesslide/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

プレゼンテーション内のノートスライドを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ノートスライドの HeaderFooter マネージャーを返します。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | ノートのテキストがある場合、その TextFrame を返します。 |
| [getThemeManager()](#getThemeManager--) | オーバーライドされるテーママネージャーを返します。 |
| [getParentSlide()](#getParentSlide--) | 親スライドを返します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスター スライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスター スライド上のシェイプをスライドに表示するかどうかを指定します。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

ノートスライドの HeaderFooter マネージャーを返します。読み取り専用 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**戻り値:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

ノートのテキストがある場合、その TextFrame を返します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

オーバーライドされるテーママネージャーを返します。読み取り専用 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**戻り値:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

親スライドを返します。読み取り専用 [ISlide](../../com.aspose.slides/islide)。

**戻り値:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスター スライド上のシェイプをスライドに表示するかどうかを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスター スライド上のシェイプをスライドに表示するかどうかを指定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |