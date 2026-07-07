---
title: MathArray
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định một mảng dọc gồm các phương trình hoặc bất kỳ đối tượng toán học nào
type: docs
weight: 8550
url: /vi/aspose.slides.mathtext/matharray/
---
## MathArray lớp

Chỉ định một mảng dọc gồm các phương trình hoặc bất kỳ đối tượng toán học nào

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## Hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Tạo một mảng toán học và đặt các phần tử đã cho vào trong nó |
| [MathArray](matharray#constructor)(IMathElement) | Tạo một mảng toán học và đặt phần tử đã cho vào trong nó |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | Tập hợp các mục của mảng |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Xác định căn chỉnh của mảng so với văn bản bao quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, trên hoặc trung tâm của đối tượng mảng. Giá trị mặc định: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Phân phối tối đa. Khi true, mảng được căn chỉnh tới chiều rộng tối đa của phần tử chứa (page, column, cell, etc.). |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Phân phối đối tượng. Khi true, nội dung của mảng được căn chỉnh tới chiều rộng tối đa của đối tượng mảng. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Khoảng cách giữa các hàng của mảng. Chỉ được sử dụng khi RowSpacingRule được đặt thành 3 Exactly, trong trường hợp này đơn vị đo là points hoặc Multiple, trong trường hợp này đơn vị đo là half-lines. Mặc định: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | Kiểu khoảng cách dọc giữa các phần tử mảng. Mặc định: SingleLineGap |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu nhấn (một ký tự ở trên phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử này và mẫu đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử này và mẫu đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử này và mẫu đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử này và mẫu đã chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự đã chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện một hàm của đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện một hàm của đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Lấy tích phân không giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Lấy tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Kết hợp một phần tử toán học và tạo một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Kết hợp một văn bản toán học và tạo một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh ở trên phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc toán học của cấp độ đã cho từ đối số đã chỉ định |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc toán học của cấp độ đã cho từ đối số đã chỉ định |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số phụ |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số phụ |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số phụ và chỉ số trên bên trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số phụ và chỉ số trên bên trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số phụ và chỉ số trên bên phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số phụ và chỉ số trên bên phải |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc đoạn văn bản toán học khác. Một đối tượng có khung có thể (ví dụ) đóng vai trò làm bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, làm điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở dưới phần tử này |

### Ví dụ

Example:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathArray](../imatharray)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập tin lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->