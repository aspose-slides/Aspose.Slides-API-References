---
title: NotesSlide
second_title: Aspose.Slides for Java API 參考
description: 代表簡報中的筆記投影片。
type: docs
url: /zh-hant/com.aspose.slides/notesslide/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**全部已實作介面：**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

代表簡報中的注釋投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回筆記投影片的 HeaderFooter manager。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 傳回含有筆記文字的 TextFrame（如果有的話）。 |
| [getThemeManager()](#getThemeManager--) | 傳回 overriding theme manager。 |
| [getParentSlide()](#getParentSlide--) | 傳回父投影片。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母片上的形狀。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母片上的形狀。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

傳回筆記投影片的 HeaderFooter manager。唯讀 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**返回：**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

傳回含有筆記文字的 TextFrame（如果有的話）。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

傳回 overriding theme manager。唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回：**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

傳回父投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在投影片上顯示母片上的形狀。讀寫布林。

**返回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在投影片上顯示母片上的形狀。讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |