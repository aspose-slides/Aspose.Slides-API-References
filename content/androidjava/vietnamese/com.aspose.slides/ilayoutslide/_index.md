---
title: ILayoutSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một slide bố cục.
type: docs
url: /vi/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Represents a layout slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide bố cục. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Trả về trình quản lý placeholder của slide bố cục. |
| [getMasterSlide()](#getMasterSlide--) | Trả về hoặc đặt master slide cho một layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Trả về hoặc đặt master slide cho một layout. |
| [getLayoutType()](#getLayoutType--) | Trả về loại layout của slide bố cục này. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide bố cục này. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide bố cục này. |
| [remove()](#remove--) | Xóa layout khỏi bản trình bày. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một bộ sưu tập các drawing guide cho slide bố cục. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của slide bố cục. Chỉ đọc [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Trả về:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Trả về trình quản lý placeholder của slide bố cục. Chỉ đọc [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Trả về:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Trả về hoặc đặt master slide cho một layout. Đọc/ghi [IMasterSlide](../../com.aspose.slides/imasterslide).

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Trả về hoặc đặt master slide cho một layout. Đọc/ghi [IMasterSlide](../../com.aspose.slides/imasterslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Trả về loại layout của slide bố cục này. Chỉ đọc [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Trả về:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide bố cục này. Chỉ đọc boolean.

**Trả về:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Trả về một mảng chứa tất cả các slide phụ thuộc vào slide bố cục này.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng chứa tất cả các slide phụ thuộc vào slide bố cục này
### remove() {#remove--}
```
public abstract void remove()
```

Xóa layout khỏi bản trình bày.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Trả về một bộ sưu tập các drawing guide cho slide bố cục. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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