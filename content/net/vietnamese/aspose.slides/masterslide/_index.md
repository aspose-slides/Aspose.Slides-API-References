---
title: MasterSlide
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một slide chủ trong một bài thuyết trình.
type: docs
weight: 8030
url: /vi/aspose.slides/masterslide/
---
## MasterSlide lớp

Biểu diễn một slide chủ trong một bài thuyết trình.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Trả về nền của slide. Chỉ đọc [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Trả về kiểu dáng của văn bản thân. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Trả về tập hợp các điều khiển ActiveX trên slide. Chỉ đọc [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Trả về tập hợp các hướng dẫn vẽ cho slide chủ. Chỉ đọc [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide chủ này. Chỉ đọc Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của slide chủ. Chỉ đọc [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Cung cấp truy cập dễ dàng tới các hyperlink được chứa. Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Trả về tập hợp các slide bố cục con cho slide chủ này. Chỉ đọc [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Trả về hoặc đặt tên của một slide chủ. Đọc/ghi String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Trả về kiểu dáng của một văn bản khác. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Trả về giao diện IPresentation. Chỉ đọc [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Xác định xem master tương ứng có bị xóa khi tất cả các slide theo sau master đó bị xóa không. Lưu ý: Aspose.Slides sẽ không tự động xóa bất kỳ master không sử dụng nào, để thực sự xóa các master không sử dụng, hãy gọi [`RemoveUnused`](../masterslidecollection/removeunused) Đọc/ghi Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Trả về các shape của một slide. Chỉ đọc [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Xác định liệu các shape trên slide chủ có được hiển thị trên các slide hay không. Đối với chính slide chủ, thuộc tính này luôn trả về `false`. Đọc/ghi Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Trả về ID của một slide. Chỉ đọc UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Trả về đối tượng Transition chứa thông tin về cách slide được chỉ định tiến triển trong buổi trình chiếu. Chỉ đọc [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Trả về trình quản lý theme. Chỉ đọc [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Trả về đối tượng animation timeline. Chỉ đọc [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Trả về kiểu dáng của văn bản tiêu đề. Chỉ đọc [`ITextStyle`](../itextstyle). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Tạo một slide chủ mới dựa trên slide hiện tại, áp dụng một theme bên ngoài cho nó và áp dụng slide chủ đã tạo cho tất cả các slide phụ thuộc. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Trả về một theme hiệu quả cho slide này. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Xác định xem hai thể hiện IBaseSlide có bằng nhau không. Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh. Hai slide bằng nhau nếu tất cả các shape, style, text, animation và các cài đặt khác, v.v. đều bằng nhau. So sánh không xét đến các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide chủ này. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Ghép các run có cùng định dạng trong tất cả các đoạn văn của tất cả các shape chấp nhận được. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Ghép các run có cùng định dạng trong tất cả các đoạn văn của tất cả các shape chấp nhận được. |

### Xem thêm

* lớp [BaseSlide](../baseslide)
* giao diện [IMasterSlide](../imasterslide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->