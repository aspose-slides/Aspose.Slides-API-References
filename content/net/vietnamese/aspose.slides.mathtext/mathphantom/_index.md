---
title: MathPhantom
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một đối tượng toán học ảo ltmphantgt ảnh hưởng đến bố cục của phần tử con mà không nhất thiết hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ sở của nó trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dành chỗ. Tính khả dụng và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.
type: docs
weight: 8920
url: /vi/aspose.slides.mathtext/mathphantom/
---
## MathPhantom lớp

Biểu diễn một đối tượng toán học ảo (&lt;m:phant&gt;) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ sở của mình trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dành chỗ. Tính khả dụng và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Khởi tạo một thể hiện mới của lớp [`MathPhantom`](../mathphantom) bằng cách sử dụng phần tử toán học cơ sở được chỉ định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Đối số cơ sở |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Lấy hoặc đặt giá trị cho biết độ lên (chiều cao trên đường cơ sở) của phần tử cơ sở có nên được coi là zero. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Lấy hoặc đặt giá trị cho biết độ hạ (độ sâu dưới đường cơ sở) của phần tử cơ sở có nên được coi là zero. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở có nên được coi là zero. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Đặt dấu phụ (một ký tự ở phía trên phần tử này) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Thực hiện hàm chỉ định, sử dụng thể hiện này làm đối số và đối số bổ sung được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tạo một phân số với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số được chỉ định |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tạo một phân số loại chỉ định với tử số này và mẫu số được chỉ định |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bao quanh một phần tử toán học bằng dấu ngoặc đơn |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bao quanh một phần tử toán học bằng các ký tự chỉ định như dấu ngoặc hoặc các ký tự khác như khung |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Thực hiện một hàm với đối số, sử dụng thể hiện này làm tên hàm |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Thực hiện một hàm với đối số, sử dụng thể hiện này làm tên hàm |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Lấy các phần tử con |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Thực hiện tích phân không giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Thực hiện tích phân |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Thực hiện tích phân với vị trí giới hạn |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Thực hiện tích phân với vị trí giới hạn |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Nối một phần tử toán học và tạo một khối toán học |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Nối một văn bản toán học và tạo một khối toán học |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tạo một toán tử N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tạo một toán tử N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Đặt một thanh trên đầu phần tử này |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Xác định căn bậc của toán học với mức độ đã cho từ đối số được chỉ định. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Xác định căn bậc của toán học với mức độ đã cho từ đối số được chỉ định. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Đặt phần tử này vào một hộp biên |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Đặt phần tử này vào một hộp biên |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Đặt phần tử này vào một hộp không hiển thị (nhóm logic) được dùng để nhóm các thành phần của một phương trình hoặc một đoạn văn bản toán học khác. Một đối tượng được đóng khung có thể (ví dụ) hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm sao cho không cho phép ngắt dòng bên trong. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Đặt vào một mảng dọc |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Đặt một thanh ở phía dưới của phần tử này |

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Ẩn nội dung
phantom.ZeroWidth = false;     // Giữ lại chiều rộng
```

### Xem thêm

* lớp [MathElementBase](../mathelementbase)
* giao diện [IMathPhantom](../imathphantom)
* không gian tên [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->