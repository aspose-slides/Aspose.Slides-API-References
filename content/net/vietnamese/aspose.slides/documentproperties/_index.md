---
title: DocumentProperties
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Biểu diễn các thuộc tính của một bản trình chiếu.
type: docs
weight: 2810
url: /vi/aspose.slides/documentproperties/
---
## Lớp DocumentProperties

Đại diện cho các thuộc tính của một bản trình chiếu.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Các hàm tạo

| Tên | Mô tả |
| --- | --- |
| [DocumentProperties](documentproperties)() | Khởi tạo một thể hiện mới của lớp [`DocumentProperties`](../documentproperties). |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Trả về hoặc đặt mẫu của một ứng dụng. Read/write String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Trả về phiên bản ứng dụng. Read-only String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Trả về hoặc đặt tác giả của một bản trình chiếu. Read/write String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Trả về hoặc đặt danh mục của một bản trình chiếu. Read/write String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Trả về hoặc đặt các chú thích của một bản trình chiếu. Read/write String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Trả về hoặc đặt thuộc tính công ty. Read/write String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Trả về hoặc đặt trạng thái nội dung của một bản trình chiếu. Read/write String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Trả về hoặc đặt kiểu nội dung của một bản trình chiếu. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Trả về số lượng thuộc tính tùy chỉnh thực sự có trong một bộ sưu tập. Read-only Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Trả về ngày tạo của một bản trình chiếu. Các giá trị ở múi giờ UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Cho biết cách nhóm các phần tài liệu và số lượng phần trong mỗi nhóm. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Trả về số lượng slide ẩn trong tài liệu bản trình chiếu. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Trả về hoặc đặt thuộc tính tài liệu HyperlinkBase. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Chỉ định rằng một hoặc nhiều siêu liên kết trong phần này đã được nhà sản xuất cập nhật một cách độc quyền trong phần này. Người sản xuất tiếp theo mở tài liệu này sẽ cập nhật các mối quan hệ siêu liên kết với các siêu liên kết mới được chỉ định trong phần này. Read/write Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Trả về hoặc đặt thuộc tính tùy chỉnh liên kết với một tên nhất định. Read/write Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Trả về hoặc đặt các từ khóa của một bản trình chiếu. Read/write String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Trả về ngày khi bản trình chiếu được in lần cuối. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Trả về hoặc đặt tên của người cuối cùng đã sửa đổi một bản trình chiếu. Read/write String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Trả về ngày bản trình chiếu được sửa đổi lần cuối. Các giá trị ở múi giờ UTC. Chỉ đọc trong trường hợp Presentation.DocumentProperties (vì nó sẽ được cập nhật nội bộ trong quá trình lưu đối tượng IPresentation). Có thể được thay đổi thông qua thể hiện DocumentProperties trả về bởi phương thức [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Vui lòng xem ví dụ trong tóm tắt phương thức [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Cho biết liệu các siêu liên kết trong tài liệu có cập nhật mới nhất hay không. Đặt phần tử này thành **true** để chỉ ra rằng các siêu liên kết đã được cập nhật. Đặt phần tử này thành **false** để chỉ ra rằng các siêu liên kết đã lỗi thời. Read/write Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Trả về hoặc đặt thuộc tính người quản lý. Read/write String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Trả về tổng số đoạn âm thanh hoặc video có trong tài liệu. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Trả về hoặc đặt tên của ứng dụng. Read/write String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Trả về số lượng slide trong bản trình chiếu có chứa ghi chú. Read-only Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Trả về tổng số đoạn văn được tìm thấy trong tài liệu nếu có. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Trả về hoặc đặt định dạng dự kiến của một bản trình chiếu. Read/write String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Trả về hoặc đặt số phiên bản của bản trình chiếu. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Cho biết chế độ hiển thị của hình thu nhỏ tài liệu. Đặt phần tử này thành **true** để bật việc co dãn hình thu nhỏ tài liệu phù hợp với màn hình. Đặt phần tử này thành **false** để bật việc cắt hình thu nhỏ tài liệu chỉ hiển thị các phần phù hợp với màn hình. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Xác định liệu bản trình chiếu có được chia sẻ giữa nhiều người hay không. Read/write Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Trả về tổng số slide trong tài liệu bản trình chiếu. Read-only Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Trả về hoặc đặt chủ đề của một bản trình chiếu. Read/write String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Trả về hoặc đặt tiêu đề của một bản trình chiếu. Read/write String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Xác định tiêu đề của mỗi phần tài liệu. Các phần này không phải là phần tài liệu mà là biểu diễn khái niệm của các phần tài liệu. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Thời gian chỉnh sửa tổng cộng của một bản trình chiếu. Read/write TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Trả về tổng số từ chứa trong tài liệu. Read-only Int32. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Xóa và đặt các giá trị mặc định cho tất cả các thuộc tính builtIn. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Xóa tất cả các thuộc tính tùy chỉnh. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Sao chép đối tượng hiện tại |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Sao chép đối tượng hiện tại |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Kiểm tra sự tồn tại của một thuộc tính tùy chỉnh với tên đã chỉ định. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Trả về tên thuộc tính tùy chỉnh tại chỉ mục đã chỉ định. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lấy giá trị boolean có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lấy giá trị DateTime có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lấy giá trị double có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lấy giá trị float có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lấy giá trị integer có tên từ các thuộc tính tùy chỉnh. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lấy giá trị string có tên từ các thuộc tính tùy chỉnh. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Lấy một mảng các nhãn nhạy cảm từ các thuộc tính tài liệu tùy chỉnh (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Xóa một thuộc tính tùy chỉnh liên kết với một tên đã chỉ định. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Đặt một thuộc tính tùy chỉnh boolean có tên. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Đặt một thuộc tính tùy chỉnh DateTime có tên. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Đặt một thuộc tính tùy chỉnh double có tên. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Đặt một thuộc tính tùy chỉnh float có tên. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Đặt một thuộc tính tùy chỉnh integer có tên. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Đặt một thuộc tính tùy chỉnh string có tên. |

### Ví dụ

Ví dụ sau đây cho thấy cách truy cập các Thuộc tính tích hợp sẵn của PowerPoint Presentation.

```csharp
[C#]
// Khởi tạo lớp Presentation đại diện cho bản trình chiếu
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Tạo một tham chiếu tới đối tượng IDocumentProperties liên kết với Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Hiển thị các thuộc tính tích hợp sẵn
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Ví dụ sau đây cho thấy cách sửa đổi các Thuộc tính tích hợp sẵn của PowerPoint Presentation.

```csharp
[C#]
// Khởi tạo lớp Presentation đại diện cho Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Tạo một tham chiếu tới đối tượng IDocumentProperties liên kết với Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Đặt các thuộc tính tích hợp sẵn
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Lưu bản trình chiếu của bạn vào một tệp
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IDocumentProperties](../idocumentproperties)
* giao diện [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->