---
title: IMasterSlide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một slide chủ trong một bản trình bày.
type: docs
url: /vi/com.aspose.slides/imasterslide/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Đại diện cho một slide chủ trong một bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide chủ. |
| [getTitleStyle()](#getTitleStyle--) | Trả về kiểu dáng của văn bản tiêu đề. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Tạo một slide chủ mới dựa trên slide hiện tại, áp dụng một chủ đề bên ngoài cho nó và áp dụng slide chủ đã tạo cho tất cả các slide phụ thuộc. |
| [getBodyStyle()](#getBodyStyle--) | Trả về kiểu dáng của văn bản nội dung. |
| [getOtherStyle()](#getOtherStyle--) | Trả về kiểu dáng của một văn bản khác. |
| [getLayoutSlides()](#getLayoutSlides--) | Trả về tập hợp các slide bố cục con cho slide chủ này. |
| [getPreserve()](#getPreserve--) | Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. |
| [hasDependingSlides()](#hasDependingSlides--) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide chủ này. |
| [getDependingSlides()](#getDependingSlides--) | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide chủ này. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về một tập hợp các hướng dẫn vẽ cho slide chủ. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Trả về trình quản lý HeaderFooter của slide chủ. Chỉ đọc [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Trả về:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Trả về kiểu dáng của văn bản tiêu đề. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Tạo một slide chủ mới dựa trên slide hiện tại, áp dụng một chủ đề bên ngoài cho nó và áp dụng slide chủ đã tạo cho tất cả các slide phụ thuộc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | java.lang.String | Đường dẫn đến tệp chủ đề bên ngoài (.thmx). |

**Trả về:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide mới có chủ đề.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Trả về kiểu dáng của văn bản nội dung. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Trả về kiểu dáng của một văn bản khác. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Trả về tập hợp các slide bố cục con cho slide chủ này. Chỉ đọc [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Bạn có thể truy cập API thay thế để thêm/chèn/xóa/sao chép các slide bố cục bằng cách sử dụng thuộc tính ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**Trả về:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master không dùng nào, để thực sự xóa các master không dùng, hãy gọi [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-). Đọc/ghi boolean.

**Trả về:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master không dùng nào, để thực sự xóa các master không dùng, hãy gọi [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-). Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide chủ này. Chỉ đọc boolean.

**Trả về:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Trả về một mảng chứa tất cả các slide phụ thuộc vào slide chủ này.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [ISlide](../../com.aspose.slides/islide), phụ thuộc vào slide chủ này
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Trả về một tập hợp các hướng dẫn vẽ cho slide chủ. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào phía bên phải của trung tâm slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)