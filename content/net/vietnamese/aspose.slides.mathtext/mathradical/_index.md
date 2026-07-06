---
title: MathRadical
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định hàm căn bậc bao gồm một cơ số và một cấp tùy chọn. Ví dụ về đối tượng căn bậc là .
type: docs
weight: 8940
url: /vi/aspose.slides.mathtext/mathradical/
---
## Lớp MathRadical

Xác định hàm căn bậc, bao gồm một cơ số và một cấp tùy chọn. Ví dụ về đối tượng căn bậc là √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | Khởi tạo một thể hiện mới của lớp MathRadical. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Đối số cơ sở |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Đối số cấp |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Ẩn cấp. Khi là true, cấp không được hiển thị, như √𝑥 |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở trên cùng của phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Sử dụng hàm đã chỉ định, dùng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Sử dụng hàm đã chỉ định, dùng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Sử dụng hàm đã chỉ định, dùng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Sử dụng hàm đã chỉ định, dùng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Sử dụng hàm đã chỉ định, dùng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như ngoặc hoặc ký tự khác |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Lấy một hàm của một đối số, sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Lấy một hàm của một đối số, sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Lấy tích phân không có giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Lấy tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Kết hợp một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Kết hợp một văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt thanh ở trên của phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc toán học của cấp đã cho từ đối số đã chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc toán học của cấp đã cho từ đối số đã chỉ định. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số dưới |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên bên trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số dưới và chỉ số trên bên trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên bên phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số dưới và chỉ số trên bên phải |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn toán học khác. Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt thanh ở dưới của phần tử này |

### Ví dụ

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathRadical](../imathradical)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* bộ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->