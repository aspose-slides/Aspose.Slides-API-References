---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp bộ điều khiển định dạng được sử dụng để nhúng tất cả phông chữ của bản trình chiếu ở định dạng WOFF.
type: docs
url: /vi/com.aspose.slides/embedallfontshtmlcontroller/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Lớp điều khiển định dạng được sử dụng để nhúng tất cả phông chữ của bản trình chiếu ở định dạng WOFF.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Tạo một thể hiện mới |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Tạo một thể hiện mới |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi phần đầu của tài liệu html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Được gọi để ghi phần cuối của tài liệu html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi phần đầu của slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Được gọi để ghi phần cuối của slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Được gọi trước khi render shape. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Ghi tất cả phông chữ chứa trong [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Ghi dữ liệu dưới dạng base64 vào chính tài liệu HTML |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Tạo một thể hiện mới

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Tạo một thể hiện mới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Các phông chữ sẽ bị loại trừ khỏi việc nhúng |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Được gọi để ghi phần đầu của tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đang được render hiện tại. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Được gọi để ghi phần cuối của tài liệu html. Được gọi một lần cho mỗi lần chuyển đổi bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đang được render hiện tại. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Được gọi để ghi phần đầu của slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render hiện tại. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Được gọi để ghi phần cuối của slide html. Được gọi một lần cho mỗi slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide đang được render hiện tại. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ gì vào generator, việc tạo hình ảnh slide hiện tại sẽ kết thúc, đoạn html được chèn vào và hình ảnh mới sẽ được bắt đầu trên hình ảnh trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape sẽ được render. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Được gọi trước khi render shape. Được gọi một lần cho mỗi shape. Nếu hàm này ghi bất kỳ gì vào generator, việc tạo hình ảnh slide hiện tại sẽ kết thúc, đoạn html được chèn vào và hình ảnh mới sẽ được bắt đầu trên hình ảnh trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape được render cuối cùng. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Ghi tất cả phông chữ chứa trong [Presentation](../../com.aspose.slides/presentation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Đối tượng đầu ra. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đang được render hiện tại. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Ghi dữ liệu dưới dạng base64 vào chính tài liệu HTML

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Trình tạo HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ để tuần tự hoá |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ thay thế (nếu đã xảy ra việc thay thế phông chữ), null nếu không |
| fontStyle | java.lang.String | Kiểu phông chữ |
| fontWeight | java.lang.String | Độ đậm phông chữ |
| fontData | byte[] | Dữ liệu phông chữ |