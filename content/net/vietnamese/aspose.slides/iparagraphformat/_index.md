---
title: IParagraphFormat
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như IParagraphFormatEffectiveData./iparagraphformateffectivedata, tất cả các thuộc tính của lớp này có thể ghi được.
type: docs
weight: 6590
url: /vi/aspose.slides/iparagraphformat/
---
## IParagraphFormat giao diện

Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi được.

```csharp
public interface IParagraphFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Trả về hoặc đặt căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Trả về định dạng dấu đầu dòng của đoạn văn. Chỉ đọc [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Trả về định dạng phần mặc định của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Trả về hoặc đặt kích thước tabulation mặc định không kế thừa. Đọc/ghi Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Trả về hoặc đặt độ sâu của đoạn văn. Giá trị 0 có nghĩa là giá trị không xác định. Đọc/ghi Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Trả về hoặc đặt Thụt đầu dòng/Thụt lề treo của đoạn văn không kế thừa. Thụt lề treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Xác định liệu có sử dụng ngắt dòng Latin trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Trả về hoặc đặt lề trái trong một đoạn văn không kế thừa. Đọc/ghi Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Trả về hoặc đặt lề phải trong một đoạn văn không kế thừa. Đọc/ghi Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Trả về hoặc đặt lượng không gian sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên là. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Trả về hoặc đặt lượng không gian trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương chỉ phần trăm kích thước phông chữ mà khoảng trắng nên là. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Trả về hoặc đặt lượng không gian giữa các dòng cơ sở trong một đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm là kích thước tính bằng điểm. Không áp dụng kế thừa. Đọc/ghi Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Trả về các tabulation của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [`ITabCollection`](../itabcollection). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Lấy dữ liệu định dạng đoạn văn hiệu quả với việc kế thừa được áp dụng. |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được định nghĩa cho đoạn văn cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong hầu hết các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả những giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](./geteffective) mà trả về một thể hiện [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Xem thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->