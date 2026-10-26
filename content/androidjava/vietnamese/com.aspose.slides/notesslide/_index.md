---
title: NotesSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một slide ghi chú trong bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/notesslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các Interface đã triển khai:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Biểu diễn một notes slide trong bài thuyết trình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide ghi chú. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Trả về một TextFrame với nội dung ghi chú nếu có. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme ghi đè. |
| [getParentSlide()](#getParentSlide--) | Trả về slide cha. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Chỉ định liệu các hình dạng trên master slide có nên được hiển thị trên slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Chỉ định liệu các hình dạng trên master slide có nên được hiển thị trên slide hay không. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của slide ghi chú. Chỉ đọc [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Trả về:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Trả về một TextFrame với nội dung ghi chú nếu có. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Trả về trình quản lý theme ghi đè. Chỉ đọc [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Trả về:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Trả về slide cha. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Chỉ định liệu các hình dạng trên master slide có nên được hiển thị trên slide hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Chỉ định liệu các hình dạng trên master slide có nên được hiển thị trên slide hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |