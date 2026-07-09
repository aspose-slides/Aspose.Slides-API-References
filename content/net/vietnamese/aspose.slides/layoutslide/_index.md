---
title: LayoutSlide
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một slide bố cục.
type: docs
weight: 7640
url: /vi/aspose.slides/layoutslide/
---
## LayoutSlide lớp

Biểu diễn một slide bố cục.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Trả về nền của slide. Chỉ đọc [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Trả về bộ sưu tập các điều khiển ActiveX trên một slide. Chỉ đọc [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Trả về một bộ sưu tập các hướng dẫn vẽ cho slide bố cục. Chỉ đọc [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide bố cục này. Chỉ đọc Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của slide bố cục. Chỉ đọc [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Cung cấp truy cập dễ dàng đến các siêu liên kết được chứa. Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Trả về kiểu bố cục của slide bố cục này. Chỉ đọc [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Trả về hoặc đặt slide master cho một bố cục. Đọc/ghi [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Trả về hoặc đặt tên của một slide. Đọc/ghi String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Trả về trình quản lý placeholder của slide bố cục. Chỉ đọc [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Trả về giao diện IPresentation. Chỉ đọc [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Trả về các shape của một slide. Chỉ đọc [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Xác định xem các shape trên slide master có được hiển thị trên các slide hay không. Đọc/ghi Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Trả về ID của một slide. Chỉ đọc UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Trả về đối tượng Transition chứa thông tin về cách slide được chuyển tiếp trong buổi trình chiếu. Chỉ đọc [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Trả về trình quản lý theme ghi đè. Chỉ đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Trả về đối tượng timeline hoạt ảnh. Chỉ đọc [`IAnimationTimeLine`](../ianimationtimeline). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Trả về theme hiệu quả cho slide này. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Xác định xem hai đối tượng IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide. Hai slide bằng nhau nếu tất cả shape, style, text, animation và các thiết lập khác, v.v. đều bằng nhau. So sánh không xét tới các giá trị định danh duy nhất, chẳng hạn SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Placeholder ngày. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Trả về một mảng chứa tất cả slide phụ thuộc vào slide bố cục này. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Nối các run có cùng định dạng trong tất cả các đoạn văn của các shape có thể chấp nhận. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Nối các run có cùng định dạng trong tất cả các đoạn văn của tất cả các shape có thể chấp nhận. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Xóa bố cục khỏi bản trình bày. |

### Xem Thêm

* lớp [BaseSlide](../baseslide)
* giao diện [ILayoutSlide](../ilayoutslide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->