---
title: Slide
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một slide trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/slide/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Biểu diễn một slide trong một bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Trả về HeaderFooter manager của slide. |
| [getThemeManager()](#getThemeManager--) | Trả về theme manager ghi đè. |
| [getSlideNumber()](#getSlideNumber--) | Trả về số slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Trả về số slide. |
| [getHidden()](#getHidden--) | Xác định liệu slide đã chỉ định có bị ẩn trong buổi trình chiếu hay không. |
| [setHidden(boolean value)](#setHidden-boolean-) | Xác định liệu slide đã chỉ định có bị ẩn trong buổi trình chiếu hay không. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Chỉ định nếu các shape trên master slide nên được hiển thị trên slides hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Chỉ định nếu các shape trên master slide nên được hiển thị trên slides hay không. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [getImage()](#getImage--) | Trả về đối tượng Thumbnail Image (20% kích thước thực). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Trả về đối tượng Thumbnail Image với kích thước được chỉ định. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Trả về đối tượng Thumbnail tiff image với các tham số được chỉ định. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Trả về đối tượng Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Trả về đối tượng Thumbnail Image với kích thước được chỉ định. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Lưu nội dung slide dưới dạng tệp SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Lưu nội dung slide dưới dạng tệp SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Lưu nội dung slide dưới dạng tệp EMF. |
| [remove()](#remove--) | Xóa slide khỏi bản trình chiếu. |
| [getLayoutSlide()](#getLayoutSlide--) | Trả về hoặc đặt layout slide cho slide hiện tại. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Trả về hoặc đặt layout slide cho slide hiện tại. |
| [reset()](#reset--) | Đặt lại vị trí, kích thước và định dạng của mọi shape có prototype trên LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Cho phép truy cập notes slide, thêm và xóa nó. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ghép các run có cùng định dạng trong tất cả các đoạn trong mọi shape có thể chấp nhận. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Trả về HeaderFooter manager của slide. Chỉ đọc [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Trả về:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Trả về theme manager ghi đè. Chỉ đọc [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Trả về:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Trả về số slide. Chỉ mục của slide trong [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) luôn bằng SlideNumber - Presentation.FirstSlideNumber. Đọc/ghi int.

**Trả về:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Trả về số slide. Chỉ mục của slide trong [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) luôn bằng SlideNumber - Presentation.FirstSlideNumber. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Xác định liệu slide đã chỉ định có bị ẩn trong buổi trình chiếu hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Xác định liệu slide đã chỉ định có bị ẩn trong buổi trình chiếu hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Chỉ định nếu các shape trên master slide nên được hiển thị trên slides hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Chỉ định nếu các shape trên master slide nên được hiển thị trên slides hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Tạo ảnh tỷ lệ đầy đủ
>      IImage bmp = sld.getImage(1f, 1f);
>      // Lưu ảnh vào đĩa ở định dạng JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Chuyển đổi slide đầu tiên trong bản trình chiếu thành đối tượng Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Lưu ảnh ở định dạng PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Tạo ảnh tỷ lệ đầy đủ
>          IImage bmp = sld.getImage(1f, 1f);
>          // Lưu ảnh vào đĩa ở định dạng JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Định nghĩa kích thước
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Lấy giá trị tỷ lệ của X và Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Tạo ảnh tỷ lệ đầy đủ
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Lưu ảnh vào đĩa ở định dạng JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scaleX | float | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục x. |
| scaleY | float | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục y. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Trả về đối tượng Thumbnail Image (20% kích thước thực).

**Trả về:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Trả về đối tượng Thumbnail Image với kích thước được chỉ định.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Chuyển đổi slide đầu tiên trong bản trình chiếu thành một Bitmap với kích thước được chỉ định
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Lưu ảnh ở định dạng JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của hình ảnh cần tạo. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Trả về đối tượng Thumbnail tiff image với các tham số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tùy chọn Tiff. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Trả về đối tượng Thumbnail Image.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Tạo các tùy chọn render
>      IRenderingOptions options = new RenderingOptions();
>      // Tạo tùy chọn bố cục ghi chú và bình luận
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Đặt vị trí của ghi chú trên trang
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Đặt vị trí của bình luận trên trang
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Đặt chiều rộng của khu vực xuất bình luận
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Đặt màu cho khu vực bình luận
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Đặt tùy chọn bố cục cho việc render
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Chuyển đổi slide đầu tiên của bản trình chiếu thành một đối tượng android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Lưu ảnh ở định dạng GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |
| scaleX | float | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục x. |
| scaleY | float | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục y. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Trả về đối tượng Thumbnail Image với kích thước được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tùy chọn render. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Kích thước của hình ảnh cần tạo. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Lưu nội dung slide dưới dạng tệp SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Lưu slide đầu tiên dưới dạng tệp SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Lưu nội dung slide dưới dạng tệp SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Lưu slide đầu tiên dưới dạng tệp SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Các tùy chọn tạo SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Lưu nội dung slide dưới dạng tệp EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Lưu slide đầu tiên dưới dạng metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
### remove() {#remove--}
```
public final void remove()
```

Xóa slide khỏi bản trình chiếu.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Trả về hoặc đặt layout slide cho slide hiện tại. Đọc/ghi [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Trả về hoặc đặt layout slide cho slide hiện tại. Đọc/ghi [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Đặt lại vị trí, kích thước và định dạng của mọi shape có prototype trên LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Cho phép truy cập notes slide, thêm và xóa nó. Chỉ đọc [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Trả về:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Tác giả của các bình luận cần tìm hoặc null để trả về tất cả bình luận. |

**Trả về:**
com.aspose.slides.IComment[] - Mảng của [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Ghép các run có cùng định dạng trong tất cả các đoạn trong mọi shape có thể chấp nhận.