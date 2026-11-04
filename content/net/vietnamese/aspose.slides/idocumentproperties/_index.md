---
title: IDocumentProperties
second_title: Aspose.Sildes cho .NET Tham khảo API
description: Đại diện cho các thuộc tính của một bản trình chiếu.
type: docs
weight: 5730
url: /vi/aspose.slides/idocumentproperties/
---
## IDocumentProperties giao diện

Đại diện cho các thuộc tính của một bản trình chiếu.

```csharp
public interface IDocumentProperties
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Trả về hoặc đặt mẫu của một ứng dụng. Đọc/ghi String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Trả về phiên bản ứng dụng. Chỉ đọc String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Trả về hoặc đặt tác giả của một bản trình chiếu. Đọc/ghi String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Trả về hoặc đặt danh mục của một bản trình chiếu. Đọc/ghi String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Trả về hoặc đặt nhận xét của một bản trình chiếu. Đọc/ghi String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Trả về hoặc đặt thuộc tính công ty. Đọc/ghi String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Trả về hoặc đặt trạng thái nội dung của một bản trình chiếu. Đọc/ghi String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Trả về hoặc đặt kiểu nội dung của một bản trình chiếu. Đọc/ghi String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Trả về số lượng thuộc tính tùy chỉnh thực sự có trong một bộ sưu tập. Chỉ đọc Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Trả về ngày tạo của một bản trình chiếu. Giá trị ở múi giờ UTC. Đọc/ghi DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Cho biết việc nhóm các phần tài liệu và số phần trong mỗi nhóm. Chỉ đọc IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Xác định số slide ẩn trong tài liệu bản trình chiếu. Chỉ đọc Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Trả về hoặc đặt thuộc tính tài liệu HyperlinkBase. Đọc/ghi String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật độc quyền trong phần này. Nhà sản xuất tiếp theo mở tài liệu này sẽ cập nhật các mối quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Đọc/ghi Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Trả về hoặc đặt thuộc tính tùy chỉnh liên kết với một tên đã chỉ định. Đọc/ghi Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Trả về hoặc đặt từ khóa của một bản trình chiếu. Đọc/ghi String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Trả về ngày lần cuối bản trình chiếu được in. Đọc/ghi DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Trả về hoặc đặt tên của người cuối cùng đã sửa đổi bản trình chiếu. Đọc/ghi String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Trả về ngày bản trình chiếu được sửa đổi lần cuối. Giá trị ở múi giờ UTC.P Chỉ đọc trong trường hợp Presentation.DocumentProperties (bởi vì nó sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể thay đổi thông qua thể hiện DocumentProperties trả về bởi phương thức [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Vui lòng xem ví dụ trong tóm tắt phương thức [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Cho biết liệu các siêu liên kết trong tài liệu có cập nhật hay không. Đặt phần tử này thành **true** để chỉ ra các siêu liên kết đã được cập nhật. Đặt phần tử này thành **false** để chỉ ra các siêu liên kết đã lỗi thời. Đọc/ghi Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Trả về hoặc đặt thuộc tính quản lý. Đọc/ghi String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Xác định tổng số đoạn âm thanh hoặc video có trong tài liệu. Chỉ đọc Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Trả về hoặc đặt tên của ứng dụng. Đọc/ghi String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Xác định số slide trong bản trình chiếu có chứa ghi chú. Chỉ đọc Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Xác định tổng số đoạn văn được tìm thấy trong tài liệu (nếu áp dụng). Chỉ đọc Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Trả về hoặc đặt định dạng dự định của một bản trình chiếu. Đọc/ghi String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Trả về hoặc đặt số hiệu bản sửa đổi của bản trình chiếu. Đọc/ghi Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. Đặt phần tử này thành **true** để bật việc thu phóng hình thu nhỏ tài liệu theo màn hình. Đặt phần tử này thành **false** để bật việc cắt hình thu nhỏ tài liệu chỉ hiển thị các phần phù hợp với màn hình. Đọc/ghi Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Xác định liệu bản trình chiếu có được chia sẻ giữa nhiều người hay không. Đọc/ghi Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Xác định tổng số slide trong tài liệu bản trình chiếu. Chỉ đọc Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Trả về hoặc đặt chủ đề của một bản trình chiếu. Đọc/ghi String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Trả về hoặc đặt tiêu đề của một bản trình chiếu. Đọc/ghi String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Xác định tiêu đề của mỗi phần tài liệu. Các phần này không phải là phần tài liệu mà là các biểu diễn khái niệm của các đoạn trong tài liệu. Chỉ đọc string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. Đọc/ghi TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Xác định tổng số từ có trong tài liệu. Chỉ đọc Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Xóa và đặt giá trị mặc định cho tất cả các thuộc tính builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Xóa tất cả các thuộc tính tùy chỉnh. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên đã chỉ định. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Trả về tên thuộc tính tùy chỉnh tại chỉ mục đã chỉ định. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lấy giá trị boolean có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lấy giá trị DateTime có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lấy giá trị double có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lấy giá trị float có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lấy giá trị integer có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lấy giá trị string có tên từ các thuộc tính tùy chỉnh. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Lấy một mảng các nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Xóa một thuộc tính tùy chỉnh liên kết với một tên đã chỉ định. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Đặt một thuộc tính tùy chỉnh boolean có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Đặt một thuộc tính tùy chỉnh DateTime có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Đặt một thuộc tính tùy chỉnh double có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Đặt một thuộc tính tùy chỉnh float có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Đặt một thuộc tính tùy chỉnh integer có tên. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Đặt một thuộc tính tùy chỉnh string có tên. |

### Xem thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->