---
title: ILayoutSlide
second_title: Aspose.Slides cho Java Tham chiếu API
description: Biểu diễn một layout slide.
type: docs
url: /vi/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Biểu diễn một layout slide.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của layout slide. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Trả về trình quản lý placeholder của layout slide. |
| [getMasterSlide()](#getMasterSlide--) | Trả về hoặc đặt master slide cho một layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Trả về hoặc đặt master slide cho một layout. |
| [getLayoutType()](#getLayoutType--) | Trả về loại layout của layout slide này. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào layout slide này. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào layout slide này. |
| [remove()](#remove--) | Xóa layout khỏi bản trình chiếu. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một tập hợp các hướng dẫn vẽ cho layout slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của layout slide. Chỉ đọc [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Trả về:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Trả về trình quản lý placeholder của layout slide. Chỉ đọc [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

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

Trả về loại layout của layout slide này. Chỉ đọc [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Trả về:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào layout slide này. Chỉ đọc boolean.

**Trả về:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Trả về một mảng chứa tất cả các slide phụ thuộc vào layout slide này.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng chứa tất cả các slide, phụ thuộc vào layout slide này
### remove() {#remove--}
```
public abstract void remove()
```

Xóa layout khỏi bản trình chiếu.
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Trả về một tập hợp các hướng dẫn vẽ cho layout slide. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào bên trái trung tâm slide
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)