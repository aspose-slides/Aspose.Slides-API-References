---
title: MasterHandoutSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho slide master cho tài liệu phụ lục.
type: docs
url: /vi/com.aspose.slides/masterhandoutslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Đại diện cho slide master cho tài liệu phụ lục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định xem các hình dạng trên slide master có được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định xem các hình dạng trên slide master có được hiển thị trên các slide hay không. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide master tài liệu phụ lục. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một tập hợp các hướng dẫn vẽ cho slide master tài liệu phụ lục. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Xác định xem các hình dạng trên slide master có được hiển thị trên các slide hay không. Đối với chính slide master, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Xác định xem các hình dạng trên slide master có được hiển thị trên các slide hay không. Đối với chính slide master, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide master tài liệu phụ lục. Chỉ đọc [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Trả về:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Trả về trình quản lý theme. Chỉ đọc [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Trả về:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Trả về một tập hợp các hướng dẫn vẽ cho slide master tài liệu phụ lục. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Thêm hướng dẫn vẽ ngang mới phía trên trung tâm slide
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)