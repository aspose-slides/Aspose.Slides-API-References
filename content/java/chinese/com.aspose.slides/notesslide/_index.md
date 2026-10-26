---
title: NotesSlide
second_title: Aspose.Slides 的 Java API 参考
description: 表示演示文稿中的备注幻灯片。
type: docs
url: /zh/com.aspose.slides/notesslide/
---
**继承:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**已实现的所有接口:**  
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)  
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

表示演示文稿中的备注幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回备注幻灯片的 HeaderFooter 管理器。 |
| [getNotesTextFrame()](#getNotesTextFrame--) | 如果存在，则返回包含备注文本的 TextFrame。 |
| [getThemeManager()](#getThemeManager--) | 返回覆盖的 theme manager。 |
| [getParentSlide()](#getParentSlide--) | 返回父幻灯片。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定是否在幻灯片上显示母版幻灯片上的形状。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定是否在幻灯片上显示母版幻灯片上的形状。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

返回 HeaderFooter 管理器的备注幻灯片。只读 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)。

**返回值:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)

### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

如果存在，则返回包含备注文本的 TextFrame。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回值:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

返回覆盖的 theme manager。只读 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回值:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

返回父幻灯片。只读 [ISlide](../../com.aspose.slides/islide)。

**返回值:**  
[ISlide](../../com.aspose.slides/islide)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定是否在幻灯片上显示母版幻灯片上的形状。可读写 boolean。

**返回值:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定是否在幻灯片上显示母版幻灯片上的形状。可读写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |