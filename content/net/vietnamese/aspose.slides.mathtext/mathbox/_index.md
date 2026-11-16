---
title: MathBox
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng gói có thể hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử nên được đóng gói để ngăn ngắt dòng.
type: docs
weight: 8650
url: /vi/aspose.slides.mathtext/mathbox/
---
## MathBox lớp

Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng gói có thể hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử "==" nên được đóng gói để ngăn ngắt dòng.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Các hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Khởi tạo MathBox với phần tử được chỉ định làm đối số |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Khi đúng, bộ mô phỏng toán tử này hoạt động như một điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Đối số cơ bản |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Vi phân Khi đúng, hộp hoạt động như một vi phân (ví dụ, 𝑑𝑥 trong một tích phân), và nhận khoảng cách ngang phù hợp cho vi phân toán học. Mặc định: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Ngắt rõ ràng xác định liệu có dòng ngắt ở đầu của đối tượng Box hay không, sao cho dòng được cuộn lại tại đầu của đối tượng box. Xác định số của toán tử trên dòng trước của văn bản toán học sẽ được dùng làm điểm căn chỉnh cho dòng văn bản toán học hiện tại. Giá trị khả dụng: 1..255 Mặc định: 0 (không có ngắt rõ ràng) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Không ngắt Thuộc tính này xác định thuộc tính "không thể ngắt" trên hộp đối tượng. Khi đúng, không có dòng ngắt nào có thể xảy ra bên trong hộp. Điều này có thể quan trọng đối với các bộ mô phỏng toán tử bao gồm nhiều hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, việc ngắt dòng có thể xảy ra bên trong hộp. Mặc định: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Bộ mô phỏng toán tử. Khi đúng, hộp và nội dung của nó hoạt động như một toán tử duy nhất và thừa hưởng các thuộc tính của một toán tử. Điều này có nghĩa là, ví dụ, ký tự có thể đóng vai trò là điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Các bộ mô phỏng toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp thành một toán tử, chẳng hạn như '=='. Giá trị mặc định: false |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở trên phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm được chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm được chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm được chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm được chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm được chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học trong dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác như khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện một hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện một hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân mà không có giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMMathElement, IMMathElement, MathLimitLocations) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Nối một phần tử toán học và tạo thành một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Nối một văn bản toán học và tạo thành một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh ở trên của phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của số đã cho từ đối số được chỉ định. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMMathElement) | Lấy giới hạn dưới |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lấy giới hạn dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số dưới |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số dưới |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMMathElement, IMMathElement) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số dưới và chỉ số trên ở bên trái |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMMathElement, IMMathElement) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số dưới và chỉ số trên ở bên phải |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMMathElement) | Tạo chỉ số trên |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMMathElement) | Lấy giới hạn trên |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lấy giới hạn trên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác. Một đối tượng được đóng gói có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở dưới của phần tử này |

### Ví dụ

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathBox](../imathbox)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->