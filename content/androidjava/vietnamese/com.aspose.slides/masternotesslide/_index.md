---
title: MasterNotesSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho slide chủ của ghi chú.
type: docs
url: /vi/com.aspose.slides/masternotesslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Đại diện cho slide chủ của ghi chú.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định xem các hình dạng trên slide chủ có nên được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định xem các hình dạng trên slide chủ có nên được hiển thị trên các slide hay không. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide ghi chú chủ. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme. |
| [getNotesStyle()](#getNotesStyle--) | Trả về kiểu của văn bản ghi chú. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một bộ sưu tập các hướng dẫn vẽ cho slide ghi chú chủ. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Xác định xem các hình dạng trên slide chủ có nên được hiển thị trên các slide hay không. Đối với chính slide chủ, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Xác định xem các hình dạng trên slide chủ có nên được hiển thị trên các slide hay không. Đối với chính slide chủ, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của slide ghi chú chủ. Chỉ đọc [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Trả về:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Trả về trình quản lý theme. Chỉ đọc [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Trả về:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Trả về kiểu của văn bản ghi chú. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Trả về một bộ sưu tập các hướng dẫn vẽ cho slide ghi chú chủ. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Thêm hướng dẫn vẽ ngang mới dưới trung tâm slide
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)