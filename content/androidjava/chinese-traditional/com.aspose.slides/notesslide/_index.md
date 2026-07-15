---
title: NotesSlide
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示簡報中的備註投影片。
type: docs
url: /zh-hant/com.aspose.slides/notesslide/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**  
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)  
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

代表簡報中的備註投影片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 取得備註投影片的 HeaderFooter 管理器。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 若有備註文字，則回傳包含備註文字的 TextFrame。 |
| [getThemeManager()](#getThemeManager--) | 取得覆蓋的佈景主題管理器。 |
| [getParentSlide()](#getParentSlide--) | 取得父投影片。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在投影片上顯示母版投影片的形狀。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在投影片上顯示母版投影片的形狀。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

取得備註投影片的 HeaderFooter 管理器。唯讀 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**回傳：**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)

### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

若有備註文字，則回傳包含備註文字的 TextFrame。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**回傳：**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

取得覆蓋的佈景主題管理器。唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**回傳：**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

取得父投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**回傳：**  
[ISlide](../../com.aspose.slides/islide)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在投影片上顯示母版投影片的形狀。可讀寫 boolean。

**回傳：**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在投影片上顯示母版投影片的形狀。可讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |