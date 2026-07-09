---
title: IDocumentProperties
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Biểu diễn các thuộc tính của một bản trình bày.
type: docs
weight: 5710
url: /vi/aspose.slides/idocumentproperties/
---
## IDocumentProperties giao diện

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Trả về hoặc thiết lập mẫu của một ứng dụng. Đọc/ghi String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Trả về phiên bản ứng dụng. Chỉ đọc String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Trả về hoặc thiết lập tác giả của bản trình bày. Đọc/ghi String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Trả về hoặc thiết lập danh mục của bản trình bày. Đọc/ghi String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Trả về hoặc thiết lập bình luận của bản trình bày. Đọc/ghi String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Trả về hoặc thiết lập thuộc tính công ty. Đọc/ghi String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Trả về hoặc thiết lập trạng thái nội dung của bản trình bày. Đọc/ghi String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Trả về hoặc thiết lập loại nội dung của bản trình bày. Đọc/ghi String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Trả về số lượng thuộc tính tùy chỉnh thực sự có trong một bộ sưu tập. Chỉ đọc Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Trả về ngày tạo bản trình bày. Giá trị được tính bằng UTC. Đọc/ghi DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Cho biết cách nhóm các phần tài liệu và số phần trong mỗi nhóm. Chỉ đọc IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Xác định số lượng slide ẩn trong tài liệu bản trình bày. Chỉ đọc Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Trả về hoặc thiết lập thuộc tính tài liệu HyperlinkBase. Đọc/ghi String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được cập nhật độc quyền trong phần này bởi một nhà sản xuất. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Trả về hoặc thiết lập thuộc tính tùy chỉnh liên quan đến một tên cụ thể. Đọc/ghi Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Trả về hoặc thiết lập từ khóa của bản trình bày. Đọc/ghi String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Trả về ngày bản trình bày được in lần cuối. Đọc/ghi DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Trả về hoặc thiết lập tên người cuối cùng đã sửa đổi bản trình bày. Đọc/ghi String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Trả về ngày bản trình bày được sửa đổi lần cuối. Giá trị được tính bằng UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì nó sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi thông qua thể hiện DocumentProperties trả về bởi phương thức [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Vui lòng xem ví dụ trong phương thức tóm tắt [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Cho biết liệu các siêu liên kết trong tài liệu có cập nhật mới nhất hay không. Đặt phần tử này thành **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này thành **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Đọc/ghi Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Trả về hoặc thiết lập thuộc tính quản lý. Đọc/ghi String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Xác định tổng số đoạn âm thanh hoặc video có trong tài liệu. Chỉ đọc Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Trả về hoặc thiết lập tên của ứng dụng. Đọc/ghi String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Xác định số slide trong bản trình bày có chứa ghi chú. Chỉ đọc Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Xác định tổng số đoạn văn được tìm thấy trong tài liệu nếu có. Chỉ đọc Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Trả về hoặc thiết lập định dạng dự kiến của bản trình bày. Đọc/ghi String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Trả về hoặc thiết lập số phiên bản của bản trình bày. Đọc/ghi Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. Đặt phần tử này thành **true** để cho phép thu phóng hình thu nhỏ tài liệu phù hợp với màn hình. Đặt phần tử này thành **false** để cho phép cắt hình thu nhỏ tài liệu chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Xác định xem bản trình bày có được chia sẻ giữa nhiều người hay không. Đọc/ghi Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Xác định tổng số slide trong tài liệu bản trình bày. Chỉ đọc Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Trả về hoặc thiết lập chủ đề của bản trình bày. Đọc/ghi String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Trả về hoặc thiết lập tiêu đề của bản trình bày. Đọc/ghi String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Xác định tiêu đề của mỗi phần tài liệu. Các phần này không phải là phần tài liệu mà là biểu diễn khái niệm của các phần tài liệu. Chỉ đọc string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Thời gian chỉnh sửa tổng cộng của bản trình bày. Đọc/ghi TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Xác định tổng số từ có trong tài liệu. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Xóa và đặt giá trị mặc định cho tất cả các thuộc tính builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Xóa tất cả các thuộc tính tùy chỉnh. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên được chỉ định. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Trả về tên thuộc tính tùy chỉnh tại chỉ mục được chỉ định. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lấy giá trị boolean có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lấy giá trị DateTime có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lấy giá trị double có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lấy giá trị float có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lấy giá trị integer có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lấy giá trị string có tên từ các thuộc tính tùy chỉnh. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Lấy một mảng các nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh (Metadata của Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Xóa một thuộc tính tùy chỉnh liên quan đến một tên được chỉ định. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Đặt một thuộc tính tùy chỉnh boolean có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Đặt một thuộc tính tùy chỉnh DateTime có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Đặt một thuộc tính tùy chỉnh double có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Đặt một thuộc tính tùy chỉnh float có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Đặt một thuộc tính tùy chỉnh integer có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Đặt một thuộc tính tùy chỉnh string có tên. |

### Xem thêm

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->