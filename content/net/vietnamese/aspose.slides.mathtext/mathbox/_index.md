---
title: MathBox
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng hộp có thể hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử nên được đóng hộp để ngăn ngắt dòng.
type: docs
weight: 8630
url: /vi/aspose.slides.mathtext/mathbox/
---
## MathBox lớp

Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng hộp có thể hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử "==" nên được đóng hộp để ngăn ngắt dòng.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Bộ khởi tạo

| Tên | Mô tả |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Khởi tạo MathBox với phần tử được chỉ định làm đối số |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Khi true, bộ mô phỏng toán tử này đóng vai trò là điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Đối số cơ sở |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Khi true, hộp hoạt động như một vi phân (ví dụ, 𝑑𝑥 trong một tích phân), và nhận khoảng cách ngang phù hợp cho vi phân toán học. Mặc định: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break chỉ định có ngắt dòng tại đầu đối tượng Box hay không, sao cho dòng sẽ gập lại tại đầu đối tượng hộp. Xác định số thứ tự của toán tử trên dòng trước của văn bản toán học sẽ được dùng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học. Giá trị có thể: 1..255 Mặc định: 0 (không có explicit break) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Thuộc tính này chỉ định tính “không thể ngắt” trên hộp đối tượng. Khi true, không có ngắt dòng nào có thể xảy ra bên trong hộp. Điều này có thể quan trọng đối với các bộ mô phỏng toán tử gồm hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, có thể xảy ra ngắt dòng bên trong hộp. Mặc định: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Khi true, hộp và nội dung của nó hoạt động như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. Điều này có nghĩa, ví dụ, ký tự có thể đóng vai trò là điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Bộ mô phỏng toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp thành một toán tử, như '=='. Giá trị mặc định: false |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở trên phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực thi hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực thi hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực thi hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực thi hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực thi hàm được chỉ định bằng cách sử dụng đối tượng này làm đối số và đối số bổ sung được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử này và mẫu được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử này và mẫu được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử này và mẫu được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử này và mẫu được chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực thi hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực thi hàm của một đối số bằng cách sử dụng đối tượng này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn phía dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Lấy tích phân không giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Lấy tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Lấy tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Kết hợp một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Kết hợp một đoạn văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh ở trên phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc toán học của độ bậc cho trước từ đối số được chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc toán học của độ bậc cho trước từ đối số được chỉ định. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác. Một đối tượng được đóng hộp có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở phía dưới phần tử này |

### Ví dụ

Example:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathBox](../imathbox)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->