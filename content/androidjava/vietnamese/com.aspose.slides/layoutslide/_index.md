---
title: LayoutSlide
second_title: Tham khảo API Java của Aspose.Slides cho Android
description: Đại diện cho một slide bố cục.
type: docs
url: /vi/com.aspose.slides/layoutslide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Đại diện cho một slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide bố cục. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Trả về trình quản lý placeholder của slide bố cục. |
| [getMasterSlide()](#getMasterSlide--) | Trả về hoặc đặt master slide cho một bố cục. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Trả về hoặc đặt master slide cho một bố cục. |
| [remove()](#remove--) | Xóa bố cục khỏi bản trình chiếu. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý theme ghi đè. |
| [getLayoutType()](#getLayoutType--) | Trả về loại layout của slide bố cục này. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide bố cục này. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide bố cục này. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một collection của drawing guides cho slide bố cục. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide bố cục. Chỉ đọc [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Trả về:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Trả về trình quản lý placeholder của slide bố cục. Chỉ đọc [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Trả về:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Trả về hoặc đặt master slide cho một bố cục. Đọc/ghi [IMasterSlide](../../com.aspose.slides/imasterslide).

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Trả về hoặc đặt master slide cho một bố cục. Đọc/ghi [IMasterSlide](../../com.aspose.slides/imasterslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Xóa bố cục khỏi bản trình chiếu.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Trả về trình quản lý theme ghi đè. Chỉ đọc [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Trả về:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Trả về loại layout của slide bố cục này. Chỉ đọc [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Trả về:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Trả về một mảng chứa tất cả các slide phụ thuộc vào slide bố cục này.

**Trả về:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide bố cục này. Chỉ đọc  boolean .

**Trả về:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. Đọc/ghi  boolean .

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. Đọc/ghi  boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Trả về một collection của drawing guides cho slide bố cục. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào phía bên trái của trung tâm slide
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)