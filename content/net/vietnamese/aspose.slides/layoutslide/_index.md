---
title: LayoutSlide
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Đại diện cho một slide bố cục.
type: docs
weight: 7640
url: /vi/aspose.slides/layoutslide/
---
## LayoutSlide lớp

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Trả về nền slide. Chỉ đọc [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Trả về tập hợp các điều khiển ActiveX trên slide. Chỉ đọc [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Trả về một tập hợp các hướng dẫn vẽ cho layout slide. Chỉ đọc [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào layout slide này. Chỉ đọc Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của layout slide. Chỉ đọc [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Cung cấp truy cập dễ dàng tới các hyperlink được chứa. Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Trả về loại layout của layout slide này. Chỉ đọc [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Trả về hoặc thiết lập master slide cho một layout. Đọc/ghi [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Trả về hoặc thiết lập tên của một slide. Đọc/ghi String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Trả về trình quản lý placeholder của layout slide. Chỉ đọc [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Trả về giao diện IPresentation. Chỉ đọc [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Trả về các shape của một slide. Chỉ đọc [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Xác định xem các shape trên master slide có nên hiển thị trên slide hay không. Đọc/ghi Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Trả về ID của một slide. Chỉ đọc UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Trả về đối tượng Transition chứa thông tin về cách slide được chỉ định tiến lên trong trình chiếu. Chỉ đọc [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Trả về trình quản lý theme ghi đè. Chỉ đọc [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Trả về đối tượng timeline animation. Chỉ đọc [`IAnimationTimeLine`](../ianimationtimeline). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Trả về theme hiệu quả cho slide này. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Xác định xem hai thể hiện IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh. Hai slide bằng nhau nếu tất cả các shape, style, văn bản, animation và các cài đặt khác, v.v. đều bằng nhau. So sánh không xét các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Trả về một mảng gồm tất cả các slide phụ thuộc vào layout slide này. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Nối các run có cùng định dạng trong tất cả các đoạn văn của tất cả các shape chấp nhận được. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Nối các run có cùng định dạng trong tất cả các đoạn văn của tất cả các shape chấp nhận được. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Xóa layout khỏi bản trình chiếu. |

### Xem thêm

* lớp [BaseSlide](../baseslide)
* giao diện [ILayoutSlide](../ilayoutslide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* bộ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->