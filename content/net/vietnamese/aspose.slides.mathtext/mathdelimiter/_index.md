---
title: MathDelimiter
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Xác định đối tượng dấu phân cách bao gồm các ký tự mở và đóng như dấu ngoặc tròn, dấu ngoặc nhọn, dấu ngoặc vuông và thanh dọc, cùng một hoặc nhiều phần tử toán học bên trong được tách bằng một ký tự xác định. Ví dụ 2 2x7C2
type: docs
weight: 8650
url: /vi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter lớp

Xác định đối tượng dấu phân cách, bao gồm các ký tự mở và đóng (như dấu ngoặc tròn, dấu ngoặc nhọn, dấu ngoặc vuông và thanh dọc), và một hoặc nhiều phần tử toán học bên trong, được tách bằng một ký tự xác định. Ví dụ: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Khởi tạo MathDelimiter với phần tử đã chỉ định làm đối số cơ sở duy nhất |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Một hoặc nhiều phần tử toán học được tách bằng các ký tự phân cách |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Đặc tính Delimiter Beginning Character chỉ định ký tự dấu phân cách mở đầu, hoặc ký tự mở. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Mặc định: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Xác định hình dạng của các dấu phân cách trong đối tượng delimiter. Khi là MathDelimiterShape.Centered, các dấu phân cách được căn giữa trục toán học của văn bản và vẫn được điều chỉnh để phù hợp với toàn bộ chiều cao của nội dung. Khi là MathDelimiterShape.Match, chiều cao và hình dạng của chúng được thay đổi để khớp chính xác với nội dung. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Đặc tính Delimiter Ending Character chỉ định ký tự dấu phân cách kết thúc, hoặc ký tự đóng. Dấu phân cách toán học là các ký tự bao quanh như dấu ngoặc tròn, dấu ngoặc vuông và dấu ngoặc nhọn. Mặc định: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Xác định việc mở rộng của BeginningCharacter, SeparatorCharacter, EndingCharacter. Khi true, các dấu phân cách mở rộng theo chiều dọc để khớp với chiều cao của toán hạng. Giá trị mặc định là true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Đặc tính Delimiter Separator Character chỉ định ký tự tách các đối số trong đối tượng delimiter. Mặc định: '&#x7C;'. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu trọng âm (một ký tự ở trên đầu phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm đã chỉ định bằng cách sử dụng thể hiện này làm đối số và đối số bổ sung đã chỉ định |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Phân tách các đối số bằng ký tự dấu phân cách đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo phân số với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại đã chỉ định với tử số này và mẫu số đã chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc tròn |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Bao quanh một phần tử toán học bằng các ký tự đã chỉ định như dấu ngoặc hoặc các ký tự khác như khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện hàm của một đối số bằng cách sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn phía dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn phía dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân không giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Nối một phần tử toán học và tạo một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Nối một đoạn văn bản toán học và tạo một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh ở trên đầu phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của số cho trước từ đối số đã chỉ định |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của số cho trước từ đối số đã chỉ định |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp phi trực quan (nhóm logic) được dùng để nhóm các thành phần của một phương trình hoặc các đoạn văn bản toán học khác. Một đối tượng trong hộp có thể (ví dụ) đóng vai trò mô phỏng toán tử có hoặc không có điểm căn chỉnh, làm điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở dưới cùng của phần tử này |

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathDelimiter](../imathdelimiter)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->