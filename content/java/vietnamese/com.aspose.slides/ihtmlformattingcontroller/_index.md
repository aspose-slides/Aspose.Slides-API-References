---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java Tham chiếu API
description: Kiểm soát việc tạo tệp html.
type: docs
url: /vi/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Kiểm soát việc tạo tệp html.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi tiêu đề tài liệu html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi chân trang tài liệu html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi tiêu đề slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi chân trang slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi tiêu đề tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đang được render. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi chân trang tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đang được render. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi tiêu đề slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi chân trang slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, quá trình tạo ảnh slide hiện tại sẽ kết thúc, đoạn html được thêm sẽ được chèn và ảnh mới sẽ được bắt đầu phía trên ảnh trước đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape sắp được render. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, quá trình tạo ảnh slide hiện tại sẽ kết thúc, đoạn html được thêm sẽ được chèn và ảnh mới sẽ được bắt đầu phía trên ảnh trước đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape được render cuối cùng. |