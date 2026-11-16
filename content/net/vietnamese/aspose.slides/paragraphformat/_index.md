---
title: ParagraphFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như IParagraphFormatEffectiveData./iparagraphformateffectivedata tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 9330
url: /vi/aspose.slides/paragraphformat/
---
## Lớp ParagraphFormat

Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Hàm tạo

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initializes a new instance of [`ParagraphFormat`](../paragraphformat) class. |

## Thuộc tính

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Trả về hoặc thiết lập việc căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. Đọc/ghi Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Trả về hoặc thiết lập việc căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Trả về hoặc thiết lập Thụt dòng đầu tiên/Thụt dòng treo cho đoạn văn không kế thừa. Thụt dòng treo có thể được định nghĩa với giá trị âm. Đọc/ghi Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Xác định liệu có sử dụng ngắt dòng Latin trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Trả về hoặc thiết lập lề trái trong một đoạn văn không kế thừa. Đọc/ghi Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Trả về hoặc thiết lập lề phải trong một đoạn văn không kế thừa. Đọc/ghi Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Trả về hoặc thiết lập khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Trả về hoặc thiết lập khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Trả về hoặc thiết lập khoảng cách giữa các dòng cơ sở trong một đoạn văn. Giá trị dương là phần trăm, giá trị âm là kích thước bằng điểm. Không áp dụng kế thừa. Đọc/ghi Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Trả về các tab trong một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [`ITabCollection`](../itabcollection). |

## Phương thức

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Lấy dữ liệu định dạng đoạn văn thực tế với việc kế thừa đã được áp dụng. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được định nghĩa cho một đoạn cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong hầu hết các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng thực tế bao gồm cả những giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](./geteffective) trả về một thể hiện [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Xem thêm

* lớp [PVIObject](../pviobject)
* giao diện [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* giao diện [IParagraphFormat](../iparagraphformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập tin lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->