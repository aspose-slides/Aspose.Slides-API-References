---
title: IParagraphFormat
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Lớp này chứa các thuộc tính định dạng đoạn văn. Khác với IParagraphFormatEffectiveData./iparagraphformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 6610
url: /vi/aspose.slides/iparagraphformat/
---
## giao diện IParagraphFormat

Lớp này chứa các thuộc tính định dạng đoạn văn. Khác với [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

```csharp
public interface IParagraphFormat
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Trả về hoặc thiết lập căn chỉnh văn bản trong đoạn văn không kế thừa. Đọc/ghi [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Trả về định dạng dấu đầu dòng của đoạn văn. Chỉ đọc [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Trả về định dạng phần mặc định của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. Đọc/ghi Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Trả về hoặc thiết lập độ sâu của đoạn văn. Giá trị 0 nghĩa là giá trị chưa xác định. Đọc/ghi Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Xác định liệu ngắt dòng Đông Á có được sử dụng trong đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Trả về hoặc thiết lập căn chỉnh phông chữ trong đoạn văn không kế thừa. Đọc/ghi [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Xác định liệu dấu câu treo có được sử dụng trong đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Trả về hoặc thiết lập Khoảng cách dòng đầu/ Khoảng cách treo của đoạn văn không kế thừa. Khoảng cách treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Xác định liệu ngắt dòng La-tinh có được sử dụng trong đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Trả về hoặc thiết lập lề trái trong đoạn văn không kế thừa. Đọc/ghi Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Trả về hoặc thiết lập lề phải trong đoạn văn không kế thừa. Đọc/ghi Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Xác định liệu việc viết từ phải sang trái có được sử dụng trong đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Trả về hoặc thiết lập lượng khoảng trống sau dòng cuối cùng trong đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước của khoảng trắng tính bằng điểm. Đọc/ ghi Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Trả về hoặc thiết lập lượng khoảng trống trước dòng đầu tiên trong đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước của khoảng trắng tính bằng điểm. Đọc/ghi Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Trả về hoặc thiết lập lượng khoảng trống giữa các đường cơ sở trong đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm là kích thước tính bằng điểm. Không áp dụng kế thừa. Đọc/ghi Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Trả về các tabulation của đoạn văn. Không áp dụng kế thừa. Chỉ đọc [`ITabCollection`](../itabcollection). |

## Phương thức

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Lấy dữ liệu định dạng đoạn văn hiệu quả với việc kế thừa được áp dụng. |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được xác định cho đoạn văn cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả các giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](./geteffective) mà trả về một thể hiện [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Xem thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->