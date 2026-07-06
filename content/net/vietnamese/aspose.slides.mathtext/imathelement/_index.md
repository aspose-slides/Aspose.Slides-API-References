---
title: IMathElement
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Giao diện cơ sở của bất kỳ phần tử toán học nào như phân số, văn bản toán học, hàm, biểu thức có nhiều phần tử, v.v.
type: docs
weight: 8230
url: /vi/aspose.slides.mathtext/imathelement/
---
## IMathElement giao diện

Giao diện cơ sở của bất kỳ phần tử toán học nào: phân số, văn bản toán học, hàm, biểu thức có nhiều phần tử, v.v.

```csharp
public interface IMathElement
```

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Đặt dấu nhấn (một ký tự ở trên cùng của phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Sử dụng hàm được chỉ định với đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Sử dụng hàm được chỉ định với đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Sử dụng hàm được chỉ định với đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Sử dụng hàm được chỉ định với đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Sử dụng hàm được chỉ định với đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Bao một phần tử toán học trong ngoặc |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Bao phần tử này trong các ký tự được chỉ định như ngoặc hoặc các ký tự khác làm khung |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Sử dụng hàm của một đối số với đối tượng này làm tên hàm |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Sử dụng hàm của một đối số với đối tượng này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Đặt phần tử này vào một nhóm sử dụng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Lấy tích phân không có giới hạn |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Lấy tích phân |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Kết hợp một phần tử toán học và tạo khối toán học |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Kết hợp một văn bản toán học và tạo khối toán học |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Tạo toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Đặt một thanh ở trên cùng của phần tử này |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Xác định căn bậc của độ đã cho từ đối số được chỉ định. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Xác định căn bậc của độ đã cho từ đối số được chỉ định. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Tạo chỉ số dưới |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Tạo chỉ số dưới |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía phải |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc các trường hợp khác của văn bản toán học. Một đối tượng được đóng khung có thể (ví dụ) đóng vai trò như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò là điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Đặt một thanh ở đáy của phần tử này |

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Xem thêm

* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->