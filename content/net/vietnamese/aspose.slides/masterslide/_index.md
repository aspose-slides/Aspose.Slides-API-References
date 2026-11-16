---
title: MasterSlide
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Biểu thị một master slide trong một bản trình chiếu.
type: docs
weight: 8050
url: /vi/aspose.slides/masterslide/
---
## Lớp MasterSlide

Biểu thị một master slide trong một bản trình chiếu.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Trả về nền của slide. Chỉ đọc [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Trả về kiểu của văn bản nội dung. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Trả về bộ sưu tập các điều khiển ActiveX trên một slide. Chỉ đọc [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Trả về bộ sưu tập các hướng dẫn vẽ cho master slide. Chỉ đọc [`IDrawingGuidesCollection`](../idrawingguidescollection). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào master slide này. Chỉ đọc Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của master slide. Chỉ đọc [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Cung cấp quyền truy cập dễ dàng tới các hyperlink được chứa. Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Trả về bộ sưu tập các slide bố cục con cho master slide này. Chỉ đọc [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Trả về hoặc đặt tên của master slide. Đọc/ghi String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Trả về kiểu của văn bản khác. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Trả về giao diện IPresentation. Chỉ đọc [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Xác định liệu master tương ứng có bị xoá khi tất cả các slide theo sau master đó được xoá hay không. Lưu ý: Aspose.Slides sẽ không bao giờ tự động xoá bất kỳ master không sử dụng nào, để thực sự xoá các master không sử dụng hãy gọi [`RemoveUnused`](../masterslidecollection/removeunused) Đọc/ghi Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Trả về các shape của một slide. Chỉ đọc [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Xác định liệu các shape trên master slide có được hiển thị trên các slide hay không. Đối với chính master slide, thuộc tính này luôn trả về `false`. Đọc/ghi Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Trả về ID của một slide. Chỉ đọc UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Trả về đối tượng Transition chứa thông tin về cách slide được chuyển trong một buổi trình chiếu. Chỉ đọc [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Trả về trình quản lý theme. Chỉ đọc [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Trả về đối tượng animation timeline. Chỉ đọc [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Trả về kiểu của văn bản tiêu đề. Chỉ đọc [`ITextStyle`](../itextstyle). |

## Phương thức

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Tạo một master slide mới dựa trên slide hiện tại, áp dụng một theme bên ngoài và áp dụng master slide đã tạo cho tất cả các slide phụ thuộc. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Trả về theme hiệu quả cho slide này. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Xác định liệu hai thể hiện IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh. Hai slide được coi bằng nhau nếu tất cả các shape, style, text, animation và các thiết lập khác, v.v. đều bằng nhau. Phép so sánh không tính đến các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Placeholder ngày. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Trả về một mảng chứa tất cả các slide phụ thuộc vào master slide này. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Kết hợp các run có cùng định dạng trong tất cả các đoạn văn và các shape chấp nhận được. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Kết hợp các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các shape chấp nhận được. |

### Xem thêm

* lớp [BaseSlide](../baseslide)
* giao diện [IMasterSlide](../imasterslide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->