---
title: ISlide
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một slide trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/islide/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Biểu diễn một slide trong bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về trình quản lý HeaderFooter của slide. |
| [getSlideNumber()](#getSlideNumber--) | Trả về số của slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Trả về số của slide. |
| [getHidden()](#getHidden--) | Xác định xem slide được chỉ định có bị ẩn trong buổi chiếu slide hay không. |
| [setHidden(boolean value)](#setHidden-boolean-) | Xác định xem slide được chỉ định có bị ẩn trong buổi chiếu slide hay không. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Trả về đối tượng ảnh với tỷ lệ tùy chỉnh. |
| [getImage()](#getImage--) | Trả về đối tượng Thumbnail Image (20% kích thước thực). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Trả về đối tượng ảnh với kích thước được chỉ định. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Trả về đối tượng Thumbnail tiff bitmap với các tham số được chỉ định. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Trả về đối tượng Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Trả về đối tượng Thumbnail Bitmap với tỷ lệ tùy chỉnh. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Trả về đối tượng Thumbnail Bitmap với kích thước được chỉ định. |
| [getLayoutSlide()](#getLayoutSlide--) | Trả về hoặc thiết lập layout slide cho slide hiện tại. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Trả về hoặc thiết lập layout slide cho slide hiện tại. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Cho phép truy cập slide ghi chú, thêm và xóa nó. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Lưu nội dung slide dưới dạng tệp SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Lưu nội dung slide dưới dạng tệp SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Lưu nội dung slide dưới dạng tệp EMF. |
| [remove()](#remove--) | Xóa slide khỏi bản trình chiếu. |
| [reset()](#reset--) | Đặt lại vị trí, kích thước và định dạng của mọi hình dạng có nguyên mẫu trên LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Trả về trình quản lý HeaderFooter của slide. Chỉ đọc [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Trả về:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Trả về số của slide. Chỉ mục của slide trong bộ sưu tập [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) luôn bằng SlideNumber - 1. Đọc/ghi int.

**Trả về:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Trả về số của slide. Chỉ mục của slide trong bộ sưu tập [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) luôn bằng SlideNumber - 1. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Xác định xem slide được chỉ định có bị ẩn trong buổi chiếu slide hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Xác định xem slide được chỉ định có bị ẩn trong buổi chiếu slide hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Trả về đối tượng ảnh với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scaleX | float | Giá trị để phóng to Thumbnail theo trục x. |
| scaleY | float | Giá trị để phóng to Thumbnail theo trục y. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Trả về đối tượng Thumbnail Image (20% kích thước thực).

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```


Trả về đối tượng ảnh với kích thước được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Kích thước của ảnh cần tạo. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Trả về đối tượng Thumbnail tiff bitmap với các tham số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tùy chọn Tiff. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Trả về đối tượng Thumbnail Bitmap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Trả về đối tượng Thumbnail Bitmap với tỷ lệ tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |
| scaleX | float | Giá trị để phóng to Thumbnail theo trục x. |
| scaleY | float | Giá trị để phóng to Thumbnail theo trục y. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```


Trả về đối tượng Thumbnail Bitmap với kích thước được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |
| imageSize | java.awt.Dimension | Kích thước của ảnh cần tạo. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Trả về hoặc thiết lập layout slide cho slide hiện tại. Đọc/ghi [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Trả về hoặc thiết lập layout slide cho slide hiện tại. Đọc/ghi [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Cho phép truy cập slide ghi chú, thêm và xóa nó. Chỉ đọc [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Trả về:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Tác giả của các bình luận để tìm hoặc null để trả về tất cả bình luận. |

**Trả về:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Lưu nội dung slide dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Lưu nội dung slide dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Tùy chọn tạo SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Lưu nội dung slide dưới dạng tệp EMF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |

### remove() {#remove--}
```
public abstract void remove()
```


Xóa slide khỏi bản trình chiếu.

### reset() {#reset--}
```
public abstract void reset()
```


Đặt lại vị trí, kích thước và định dạng của mọi hình dạng có nguyên mẫu trên LayoutSlide.