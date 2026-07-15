---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
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
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi phần đầu tài liệu html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi phần cuối tài liệu html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi phần đầu slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi phần cuối slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi phần đầu tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình bày.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đang được render hiện tại. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi phần cuối tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình bày.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đang được render hiện tại. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi phần đầu slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render hiện tại. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi phần cuối slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render hiện tại. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo hình ảnh slide hiện tại sẽ được hoàn tất, đoạn html được chèn thêm và hình ảnh mới sẽ được bắt đầu ở trên đoạn trước đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape đang sắp render. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo hình ảnh slide hiện tại sẽ được hoàn tất, đoạn html được chèn thêm và hình ảnh mới sẽ được bắt đầu ở trên đoạn trước đó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape được render cuối cùng. |