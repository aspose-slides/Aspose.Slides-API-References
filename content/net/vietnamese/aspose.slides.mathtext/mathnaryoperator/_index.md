---
title: MathNaryOperator
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định một đối tượng toán học N-ary như Tổng và Tích phân. Nó bao gồm một toán tử, một cơ sở hoặc toán hạng và các giới hạn trên và dưới tùy chọn. Các ví dụ của toán tử N-ary gồm Tổng, Hợp, Giao, Tích phân
type: docs
weight: 8870
url: /vi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator lớp

Xác định một đối tượng toán học N-ary, chẳng hạn như Tổng và Tích phân. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ của toán tử N-ary bao gồm: Tổng, Hợp, Giao, Tích phân

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Khởi tạo một thể hiện mới của lớp MathNaryOperator. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Đối số cơ sở |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Ký tự toán tử mở rộng theo chiều dọc để khớp với chiều cao toán hạng |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Ẩn chỉ số dưới |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Ẩn chỉ số trên |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | Vị trí của các giới hạn (chỉ số dưới và chỉ số trên) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Ký tự toán tử N-ary Ví dụ: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Xác định đối số chỉ số dưới, ví dụ trong trường hợp của tích phân, thiết lập giới hạn dưới |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Xác định đối số chỉ số trên, ví dụ trong trường hợp của tích phân, thiết lập giới hạn trên |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở phía trên phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số và đối số bổ sung chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số và đối số bổ sung chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự chỉ định như ngoặc đơn hoặc các ký tự khác như khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện một hàm của đối số, sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện một hàm của đối số, sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm dùng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm dùng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân không giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Kết hợp một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Kết hợp văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh trên đầu phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của số đã cho từ đối số chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của số đã cho từ đối số chỉ định. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác. Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở dưới phần tử này |

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathNaryOperator](../imathnaryoperator)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->