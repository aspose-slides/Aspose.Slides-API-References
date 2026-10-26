---
title: NotesSlide
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một slide ghi chú trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/notesslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Biểu thị một slide ghi chú trong bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide ghi chú. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Trả về một TextFrame chứa văn bản ghi chú nếu có. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme đang ghi đè. |
| [getParentSlide()](#getParentSlide--) | Trả về slide cha. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định xem các hình dạng trên master slide có nên hiển thị trên slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định xem các hình dạng trên master slide có nên hiển thị trên slide hay không. |
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


Trả về một TextFrame chứa văn bản ghi chú nếu có. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Trả về trình quản lý theme đang ghi đè. Chỉ đọc [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

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


Xác định xem các hình dạng trên master slide có nên hiển thị trên slide hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Xác định xem các hình dạng trên master slide có nên hiển thị trên slide hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |   |