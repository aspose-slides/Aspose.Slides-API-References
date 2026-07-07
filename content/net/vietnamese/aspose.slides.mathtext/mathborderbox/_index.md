---
title: MathBorderBox
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Vẽ một đường viền hình chữ nhật hoặc một dạng viền khác quanh IMathElement.
type: docs
weight: 8610
url: /vi/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox lớp

Vẽ một đường viền hình chữ nhật hoặc một dạng viền khác quanh IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Tạo phần tử MathBorderBox với viền hình chữ nhật |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Tạo phần tử MathBorderBox |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Đối số cơ sở |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Ẩn Cạnh Dưới (mặc định là false) - xác định trạng thái ẩn hoặc hiện của cạnh dưới của hộp viền. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Ẩn Cạnh Trái (mặc định là false) - xác định trạng thái ẩn hoặc hiện của cạnh trái của hộp viền. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Ẩn Cạnh Phải (mặc định là false) - xác định trạng thái ẩn hoặc hiện của cạnh phải của hộp viền. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Ẩn Cạnh Trên (mặc định là false) - xác định trạng thái ẩn hoặc hiện của cạnh trên của hộp viền. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Gạch chéo từ dưới-trái tới trên-phải (mặc định là false). Xác định trạng thái ẩn hoặc hiện của đường gạch chéo chéo từ góc dưới-trái tới góc trên-phải của hộp viền. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Gạch chéo ngang (mặc định là false) - xác định trạng thái ẩn hoặc hiện của một đường gạch chéo ngang. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Gạch chéo từ trên-trái tới dưới-phải (mặc định là false). Xác định trạng thái ẩn hoặc hiện của đường gạch chéo chéo từ góc trên-trái tới góc dưới-phải của hộp viền. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Gạch chéo dọc (mặc định là false) - xác định trạng thái ẩn hoặc hiện của một đường gạch chéo dọc. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở phía trên của phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số của kiểu đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số của kiểu đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Đặt phần tử toán học trong ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Đóng gói một phần tử toán học trong các ký tự chỉ định như ngoặc hoặc các ký tự khác như khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân mà không có giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Nối một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Nối văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh trên đầu phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của độ đã cho từ đối số đã chỉ định |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của độ đã cho từ đối số đã chỉ định |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số dưới |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía phải |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được dùng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác. Một đối tượng đóng hộp có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở dưới của phần tử này |

### Ví dụ

Ví dụ:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathBorderBox](../imathborderbox)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->