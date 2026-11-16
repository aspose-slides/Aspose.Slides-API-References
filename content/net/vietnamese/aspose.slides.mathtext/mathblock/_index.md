---
title: MathBlock
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Xác định một thể hiện của văn bản toán học được chứa trong một MathParagraph và bắt đầu trên một dòng riêng. Tất cả các vùng toán học, bao gồm phương trình, biểu thức, mảng các phương trình hoặc biểu thức và công thức, đều được biểu diễn bằng khối toán học.
type: docs
weight: 8610
url: /vi/aspose.slides.mathtext/mathblock/
---
## MathBlock lớp

Xác định một thể hiện của văn bản toán học được chứa trong một MathParagraph và bắt đầu trên một dòng riêng. Tất cả các khu vực toán học, bao gồm phương trình, biểu thức, mảng các phương trình hoặc biểu thức, và công thức đều được biểu diễn bằng khối toán học.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Khởi tạo một thể hiện mới của lớp MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Tạo một khối toán học mới và đặt các phần tử được chỉ định vào nó |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Tạo một khối toán học mới và đặt phần tử được chỉ định vào nó |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Lấy số lượng phần tử toán học con thực sự chứa trong bộ sưu tập. Chỉ đọc Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Trả về false vì bộ sưu tập các phần tử con có thể được sửa đổi. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Lấy hoặc thiết lập IMathElement tại chỉ mục được chỉ định. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu nhấn (một ký tự ở trên cùng của phần tử này) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Thêm một phần tử toán học vào cuối bộ sưu tập. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm được chỉ định sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm được chỉ định sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm được chỉ định sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm được chỉ định sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Xác định bộ sưu tập có chứa giá trị cụ thể hay không. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Sao chép vào mảng được chỉ định. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Phân tách các phần tử con bằng ký tự phân cách (không có dấu ngoặc). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại được chỉ định với tử số này và mẫu số được chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc ký tự khác làm khung và phân tách bằng ký tự phân cách. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện hàm của một đối số sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới cùng. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới cùng hoặc ký tự khác |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Xác định chỉ mục của một phần tử toán học cụ thể trong bộ sưu tập. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Chèn một MathElement vào bộ sưu tập tại chỉ mục được chỉ định. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân không có giới hạn. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Nối một phần tử toán học với khối toán học này. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Nối một văn bản toán học với khối toán học này. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Nối một khối toán học khác với khối này. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một đường gạch trên đầu phần tử này. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của mức độ cho trước từ đối số được chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của mức độ cho trước từ đối số được chỉ định. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Thực hiện giới hạn dưới. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Thực hiện giới hạn dưới. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tạo chỉ số dưới. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tạo chỉ số dưới. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía trái. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía trái. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tạo chỉ số dưới và chỉ số trên ở phía phải. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tạo chỉ số dưới và chỉ số trên ở phía phải. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tạo chỉ số trên. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tạo chỉ số trên. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Thực hiện giới hạn trên. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Thực hiện giới hạn trên. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp viền. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp viền. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp phi thị (nhóm logic) được sử dụng để nhóm các thành phần của một phương trình hoặc một thể hiện khác của văn bản toán học. Một đối tượng được đóng khung có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, đóng vai trò là điểm ngắt dòng, hoặc được nhóm để không cho phép ngắt dòng bên trong. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Đặt các phần tử con vào một mảng dọc. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một đường gạch ở phía dưới của phần tử này. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Lưu nội dung của [`MathBlock`](../mathblock) này dưới dạng MathML |

### Ví dụ

Ví dụ:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathBlock](../imathblock)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->