---
title: EmbeddedEotFontsHtmlController
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Lớp bộ điều khiển định dạng để sử dụng cho việc nhúng phông chữ ở định dạng EOT
type: docs
url: /vi/com.aspose.slides/embeddedeotfontshtmlcontroller/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEmbeddedEotFontsHtmlController](../../com.aspose.slides/iembeddedeotfontshtmlcontroller)
```
public class EmbeddedEotFontsHtmlController implements IEmbeddedEotFontsHtmlController
```

Lớp bộ điều khiển định dạng để sử dụng cho việc nhúng phông chữ ở định dạng EOT
## Hàm tạo

| Constructor | Mô tả |
| --- | --- |
| [EmbeddedEotFontsHtmlController()](#EmbeddedEotFontsHtmlController--) | Tạo một thể hiện mới. |
| [EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Tạo một thể hiện mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedEotFontsHtmlController() {#EmbeddedEotFontsHtmlController--}
```
public EmbeddedEotFontsHtmlController()
```

Tạo một thể hiện mới.

### EmbeddedEotFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)
```

Tạo một thể hiện mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Bộ điều khiển định dạng HTML. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi tiêu đề tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bài thuyết trình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |
### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Được gọi để ghi chân trang tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bài thuyết trình.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |
### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi tiêu đề slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |
### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Được gọi để ghi chân trang slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |
### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi shape được vẽ. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo ảnh slide hiện tại sẽ được hoàn thành, đoạn html được thêm sẽ được chèn và ảnh mới sẽ được bắt đầu ở trên ảnh trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Được gọi trước khi shape được vẽ. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ nội dung nào vào generator, việc tạo ảnh slide hiện tại sẽ được hoàn thành, đoạn html được thêm sẽ được chèn và ảnh mới sẽ được bắt đầu ở trên ảnh trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |