---
title: IMathMatrix
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Xác định đối tượng Matrix bao gồm các phần tử con được sắp xếp theo một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách tích hợp sẵn. Để đặt ma trận trong ngoặc, bạn nên sử dụng đối tượng phân cách IMathDelimiter. Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.
type: docs
weight: 8340
url: /vi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix giao diện

Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp theo một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách tích hợp sẵn. Để đặt ma trận trong ngoặc, bạn nên sử dụng đối tượng phân cách (IMathDelimiter). Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.

```csharp
public interface IMathMatrix : IMathElement
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Cho phép lấy giao diện IMathElement cơ bản [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Xác định cách căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Số cột trong ma trận |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 ("Exactly"), đơn vị được hiểu là twips (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 ("Multiple"), đơn vị được hiểu là số lần tăng 0.5 em. Trong các trường hợp khác bị bỏ qua. Mặc định: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Loại khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Ẩn các chỗ giữ chỗ cho các phần tử ma trận trống Mặc định: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Các phần tử của ma trận |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Chiều rộng cột tối thiểu tính bằng twips (1/20 điểm). Khoảng cách khe (còn gọi là “Column Gap” hoặc “Gap Width”) được cộng vào MinColumnWidth để xác định tổng khoảng cách cột của ma trận (khoảng cách giữa các cạnh tương ứng của các cột khác nhau). Mặc định: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Số hàng trong ma trận |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 ("Exactly"), đơn vị được hiểu là twips (1/20 điểm). Nếu RowGapRule được đặt thành 4 ("Multiple"), đơn vị được hiểu là nửa dòng. Mặc định: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Loại khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0) |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Xóa cột được chỉ định |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Xóa hàng được chỉ định |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Lấy căn chỉnh ngang của cột được chỉ định |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Chèn một cột mới sau cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Chèn một cột mới trước cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Chèn một hàng mới sau hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Chèn một hàng mới trước hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Đặt căn chỉnh ngang của cột được chỉ định |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Đặt căn chỉnh ngang của các cột được chỉ định |

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Xem thêm

* giao diện [IMathElement](../imathelement)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->