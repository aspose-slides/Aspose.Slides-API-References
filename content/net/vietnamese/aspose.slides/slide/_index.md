---
title: Slide
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Biểu thị một slide trong bản trình bày.
type: docs
weight: 9980
url: /vi/aspose.slides/slide/
---
## Lớp Slide

Biểu thị một slide trong một bản trình bày.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Trả về nền của slide. Chỉ đọc [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Trả về bộ sưu tập các điều khiển ActiveX trên một slide. Chỉ đọc [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của slide. Chỉ đọc [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Xác định liệu slide được chỉ định có bị ẩn trong chế độ chiếu slide hay không. Đọc/ghi Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Cung cấp quyền truy cập dễ dàng tới các hyperlink được chứa. Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Trả về hoặc đặt slide bố cục cho slide hiện tại. Đọc/ghi [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Trả về hoặc đặt tên của một slide. Đọc/ghi String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Cho phép truy cập slide ghi chú, thêm và xoá nó. Chỉ đọc [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Trả về giao diện IPresentation. Chỉ đọc [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Trả về các shape của một slide. Chỉ đọc [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. Đọc/ghi Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Trả về ID của một slide. Chỉ đọc UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Trả về số thứ tự của slide. Chỉ số của slide trong bộ sưu tập [`Slides`](../presentation/slides) luôn bằng SlideNumber - Presentation.FirstSlideNumber. Đọc/ghi Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Trả về đối tượng Transition chứa thông tin về cách slide được chỉ định tiến tới trong chế độ chiếu slide. Chỉ đọc [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Trả về trình quản lý theme ghi đè. Chỉ đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Trả về đối tượng animation timeline. Chỉ đọc [`IAnimationTimeLine`](../ianimationtimeline). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Trả về một theme hiệu quả cho slide này. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Xác định liệu hai thể hiện IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh. Hai slide bằng nhau nếu tất cả các shape, style, text, animation và các cài đặt khác, v.v. đều bằng nhau. So sánh không xét các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Trả về đối tượng Thumbnail Image (20% kích thước thực). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Trả về đối tượng Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Trả về đối tượng ảnh tiff Thumbnail với các tham số được chỉ định. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Trả về đối tượng Thumbnail Image với kích thước được chỉ định. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Trả về đối tượng Thumbnail Image với kích thước được chỉ định. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Trả về đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Trả về tất cả bình luận slide được thêm bởi tác giả cụ thể. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Nối các run có cùng định dạng trong mọi đoạn văn trong tất cả các shape chấp nhận được. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Nối các run có cùng định dạng trong mọi đoạn văn trong tất cả các shape chấp nhận được. |
| [Remove](../../aspose.slides/slide/remove)() | Xóa slide khỏi bản trình bày. |
| [Reset](../../aspose.slides/slide/reset)() | Đặt lại vị trí, kích thước và định dạng của mọi shape có mẫu trên LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Lưu nội dung slide dưới dạng tệp EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Lưu nội dung slide dưới dạng tệp SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Lưu nội dung slide dưới dạng tệp SVG. |

### Xem thêm

* lớp [BaseSlide](../baseslide)
* giao diện [ISlide](../islide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->