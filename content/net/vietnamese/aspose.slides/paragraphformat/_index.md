---
title: ParagraphFormat
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như IParagraphFormatEffectiveData./iparagraphformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 9310
url: /vi/aspose.slides/paragraphformat/
---
## ParagraphFormat lớp

Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Khởi tạo một thể hiện mới của lớp [`ParagraphFormat`](../paragraphformat). |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Trả về hoặc đặt căn chỉnh văn bản trong một đoạn không kế thừa. Đọc/ghi [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện cơ sở IPresentationComponent. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Trả về hoặc đặt kích thước tabulation mặc định không kế thừa. Đọc/ghi Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Xác định xem ngắt dòng Đông Á có được sử dụng trong một đoạn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn không kế thừa. Đọc/ghi [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Xác định xem dấu câu treo có được sử dụng trong một đoạn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Trả về hoặc đặt thụt đầu dòng Dòng Đầu hoặc Thụt Treo trong một đoạn không kế thừa. Thụt Treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Xác định xem ngắt dòng La-tinh có được sử dụng trong một đoạn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Trả về hoặc đặt lề trái trong một đoạn không kế thừa. Đọc/ ghi Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Trả về hoặc đặt lề phải trong một đoạn không kế thừa. Đọc/ ghi Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Xác định xem viết từ phải sang trái có được sử dụng trong một đoạn hay không. Không áp dụng kế thừa. Đọc/ ghi [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Trả về hoặc đặt khoảng cách sau dòng cuối cùng trong một đoạn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ ghi Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Trả về hoặc đặt khoảng cách trước dòng đầu tiên trong một đoạn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ ghi Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Trả về hoặc đặt khoảng cách giữa các dòng cơ sở trong một đoạn. Giá trị dương là phần trăm, giá trị âm là kích thước bằng điểm. Không áp dụng kế thừa. Đọc/ ghi Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Trả về các tabulation của một đoạn. Không áp dụng kế thừa. Chỉ đọc [`ITabCollection`](../itabcollection). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng đã chỉ định. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Lấy dữ liệu định dạng đoạn văn hiệu quả với kế thừa đã được áp dụng. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được định nghĩa cho đoạn cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là “không xác định”.

Để lấy các giá trị tham số định dạng hiệu quả bao gồm các giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](./geteffective) mà trả về một thể hiện [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Xem thêm

* lớp [PVIObject](../pviobject)
* giao diện [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* giao diện [IParagraphFormat](../iparagraphformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->