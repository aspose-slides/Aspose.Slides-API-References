---
title: MathMatrix
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Xác định đối tượng Matrix bao gồm các phần tử con được sắp xếp theo một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách tích hợp. Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng delimiter IMathDelimiter. Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.
type: docs
weight: 8850
url: /vi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix lớp

Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp theo một hoặc nhiều hàng và cột. Cần lưu ý rằng ma trận không có dấu phân cách được tích hợp. Để đặt ma trận trong dấu ngoặc, bạn nên sử dụng đối tượng delimiter (IMathDelimiter). Các đối số null có thể được sử dụng để tạo khoảng trống trong ma trận.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Các hàm tạo

| Tên | Mô tả |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Khởi tạo một thể hiện mới của lớp MathMatrix. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Xác định căn dọc so với văn bản xung quanh. Các giá trị có thể là top, bottom và center. Mặc định: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Số cột trong ma trận |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Giá trị của khoảng cách ngang giữa các cột của ma trận; Nếu ColumnGapRule được đặt thành 3 ("Exactly"), đơn vị sẽ được hiểu là twip (1/20 điểm). Nếu ColumnGapRule được đặt thành 4 ("Multiple"), đơn vị sẽ được hiểu là số bội của 0.5 em. Trong các trường hợp khác bị bỏ qua. Mặc định: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Loại khoảng cách ngang giữa các cột của ma trận; Đơn vị khoảng cách ngang có thể là ems hoặc points (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Ẩn các dấu giữ chỗ cho các phần tử ma trận trống. Mặc định: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Phần tử của ma trận |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Độ rộng tối thiểu của cột tính bằng twip (1/20 điểm). Khoảng cách khoảng trống (cũng được gọi là “Column Gap” hoặc “Gap Width”) được cộng vào MinColumnWidth để xác định Tổng khoảng cách cột Ma trận (khoảng cách giữa các cạnh cùng của các cột khác nhau). Mặc định: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Số hàng trong ma trận |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Giá trị của khoảng cách dọc giữa các hàng của ma trận; Nếu RowGapRule được đặt thành 3 ("Exactly"), đơn vị được hiểu là twip (1/20 điểm). Nếu RowGapRule được đặt thành 4 ("Multiple"), đơn vị được hiểu là nửa dòng. Mặc định: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Loại khoảng cách dọc giữa các hàng của ma trận; Đơn vị khoảng cách dọc có thể là lines hoặc points (được lưu dưới dạng twips). Mặc định: SingleSpacingGap (0) |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự trên đầu phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Xóa cột được chỉ định |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Xóa hàng được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số kiểu được chỉ định với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số kiểu được chỉ định với tử số này và mẫu số được chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác để tạo khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện một hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện một hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Lấy các phần tử con |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Lấy căn chỉnh ngang của cột được chỉ định |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn phía dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Chèn một cột mới sau cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Chèn một cột mới trước cột được chỉ định. Ban đầu tất cả các phần tử trong cột mới đều là null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Chèn một hàng mới sau hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Chèn một hàng mới trước hàng được chỉ định. Ban đầu tất cả các phần tử trong hàng mới đều là null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân không có giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Kết hợp một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Kết hợp một văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh trên đầu phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của số đã cho từ đối số được chỉ định |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của số đã cho từ đối số được chỉ định |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Đặt căn chỉnh ngang của cột được chỉ định |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Đặt căn chỉnh ngang của các cột được chỉ định |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số dưới |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên phía trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số dưới và chỉ số trên phía trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên phía phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số dưới và chỉ số trên phía phải |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được dùng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác. Một đối tượng trong hộp có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò là điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở đáy phần tử này |

### Ví dụ

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathMatrix](../imathmatrix)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->