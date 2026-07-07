---
title: Aspose.Slides.MathText
second_title: Tham chiếu API .NET cho Aspose.Sildes
description: Chứa các lớp để làm việc với văn bản toán học trong bản trình bày Microsoft PowerPoint.
type: docs
weight: 140
url: /vi/aspose.slides.mathtext/
---
Chứa các lớp để làm việc với văn bản toán học trong bản trình bày Microsoft PowerPoint.

## Lớp

| Lớp | Mô tả |
| --- | --- |
| [BaseScript](./basescript) | Kịch bản toán học |
| [MathAccent](./mathaccent) | Xác định hàm accent, bao gồm một cơ sở và một dấu phụ kết hợp. Ví dụ: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Cho phép tạo một dấu phụ toán học |
| [MathArray](./matharray) | Xác định một mảng dọc của các phương trình hoặc bất kỳ đối tượng toán học nào |
| [MathArrayFactory](./matharrayfactory) | Cho phép tạo một mảng toán học |
| [MathBar](./mathbar) | Xác định hàm bar, bao gồm một đối số cơ sở và một overbar hoặc underbar |
| [MathBarFactory](./mathbarfactory) | Cho phép tạo một math bar |
| [MathBlock](./mathblock) | Xác định một thể hiện của văn bản toán học được chứa trong MathParagraph và bắt đầu trên dòng riêng của nó. Tất cả các vùng toán học, bao gồm phương trình, biểu thức, mảng phương trình hoặc biểu thức, và công thức đều được biểu diễn bằng math block. |
| [MathBlockFactory](./mathblockfactory) | Cho phép tạo một math block |
| [MathBorderBox](./mathborderbox) | Vẽ một đường viền hình chữ nhật hoặc loại viền khác quanh IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Cho phép tạo một math border box |
| [MathBox](./mathbox) | Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng khung có thể hoạt động như một trình mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử "==" nên được đóng khung để ngăn ngắt dòng. |
| [MathBoxFactory](./mathboxfactory) | Cho phép tạo một math box |
| [MathDelimiter](./mathdelimiter) | Xác định đối tượng delimiter, bao gồm các ký tự mở và đóng (chẳng hạn như ngoặc tròn, dấu ngoặc nhọn, ngoặc vuông và dấu gạch đứng), và một hoặc nhiều phần tử toán học bên trong, được phân tách bằng một ký tự chỉ định. Ví dụ: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Cho phép tạo một math delimiter |
| [MathElementBase](./mathelementbase) | Lớp cơ sở cho IMathElement với triển khai một số phương thức chung cho tất cả các lớp kế thừa. Chỉ dành cho sử dụng nội bộ. Lớp kế thừa phải là IMathElement. |
| [MathematicalText](./mathematicaltext) | Văn bản toán học |
| [MathematicalTextFactory](./mathematicaltextfactory) | Cho phép tạo một phần tử MathematicalText |
| [MathFraction](./mathfraction) | Xác định đối tượng fraction, bao gồm một tử và một mẫu được ngăn cách bằng một thanh phân số. Thanh phân có thể ngang hoặc chéo, tùy thuộc vào thuộc tính của fraction. Đối tượng fraction cũng được sử dụng để đại diện cho hàm stack, đặt một phần tử lên trên phần tử khác mà không có thanh phân số. |
| [MathFractionFactory](./mathfractionfactory) | Cho phép tạo một math fraction |
| [MathFunction](./mathfunction) | Xác định một hàm của một đối số. |
| [MathFunctionFactory](./mathfunctionfactory) | Cho phép tạo một math function |
| [MathGroupingCharacter](./mathgroupingcharacter) | Xác định ký hiệu nhóm phía trên hoặc phía dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Cho phép tạo một ký hiệu nhóm toán học |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chữ chỉ số dưới và trên được đặt bên trái của cơ sở. |
| [MathLimit](./mathlimit) | Xác định đối tượng Limit, bao gồm văn bản trên dòng cơ bản và văn bản kích thước giảm ngay trên hoặc dưới nó. |
| [MathLimitFactory](./mathlimitfactory) | Cho phép tạo IMathLimit |
| [MathMatrix](./mathmatrix) | Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp trong một hoặc nhiều hàng và cột. Lưu ý rằng ma trận không có delimiter tích hợp. Để đặt ma trận trong ngoặc, bạn nên sử dụng đối tượng delimiter (IMathDelimiter). Các đối số null có thể được dùng để tạo khoảng trống trong ma trận. |
| [MathMatrixFactory](./mathmatrixfactory) | Cho phép tạo một math matrix |
| [MathNaryOperator](./mathnaryoperator) | Xác định một đối tượng toán học N-ary, chẳng hạn như Summation, Union, Intersection, Integral. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ về toán tử N-ary là: Summation, Union, Intersection, Integral. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Cho phép tạo IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Đoạn văn toán học là một container cho các math block (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Cho phép tạo một math paragraph |
| [MathPhantom](./mathphantom) | Biểu diễn một đối tượng phantom math (&lt;m:phant&gt;) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một phantom có thể ẩn biểu thức cơ sở trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc giữ chỗ. Tính hiển thị và hành vi hình học được kiểm soát bằng các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp. |
| [MathPortion](./mathportion) | Biểu diễn một phần có ngữ cảnh toán học bên trong. |
| [MathRadical](./mathradical) | Xác định hàm radical, bao gồm một cơ sở và một bậc tùy chọn. Ví dụ về đối tượng radical là √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Cho phép tạo một math radical |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chữ chỉ số dưới và trên được đặt bên phải của cơ sở. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Cho phép tạo IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Xác định đối tượng subscript, bao gồm một cơ sở và chữ chỉ số dưới kích thước giảm được đặt bên dưới và bên phải. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Cho phép tạo IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Xác định đối tượng superscript, bao gồm một cơ sở và chữ chỉ số trên kích thước giảm được đặt phía trên và bên phải. |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Cho phép tạo IMathSuperscriptElement |

## Giao diện

| Giao diện | Mô tả |
| --- | --- |
| [IMathAccent](./imathaccent) | Xác định hàm accent, bao gồm một cơ sở và một dấu phụ kết hợp. Ví dụ: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Cho phép tạo một dấu phụ toán học |
| [IMathArray](./imatharray) | Xác định một mảng dọc của các phương trình hoặc bất kỳ đối tượng toán học nào |
| [IMathArrayFactory](./imatharrayfactory) | Cho phép tạo một mảng toán học |
| [IMathBar](./imathbar) | Xác định hàm bar, bao gồm một đối số cơ sở và một overbar hoặc underbar |
| [IMathBarFactory](./imathbarfactory) | Cho phép tạo một bar toán học |
| [IMathBlock](./imathblock) | Xác định một thể hiện của văn bản toán học được chứa trong MathParagraph và bắt đầu trên dòng riêng của nó. Tất cả các vùng toán học, bao gồm phương trình, biểu thức, mảng phương trình hoặc biểu thức, và công thức đều được biểu diễn bằng math block. |
| [IMathBlockCollection](./imathblockcollection) | Tập hợp các math block (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Cho phép tạo một math block |
| [IMathBorderBox](./imathborderbox) | Vẽ một đường viền hình chữ nhật hoặc loại viền khác quanh IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Cho phép tạo một math border box |
| [IMathBox](./imathbox) | Xác định việc đóng gói logic (boxing) của phần tử toán học. Ví dụ, một đối tượng được đóng khung có thể hoạt động như một trình mô phỏng toán tử có hoặc không có điểm căn chỉnh, hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử "==" nên được đóng khung để ngăn ngắt dòng. |
| [IMathBoxFactory](./imathboxfactory) | Cho phép tạo một math box |
| [IMathDelimiter](./imathdelimiter) | Xác định đối tượng delimiter, bao gồm các ký tự mở và đóng (chẳng hạn như ngoặc tròn, dấu ngoặc nhọn, ngoặc vuông và dấu gạch đứng), và một hoặc nhiều phần tử toán học bên trong, được phân tách bằng một ký tự chỉ định. Ví dụ: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Cho phép tạo một math delimiter |
| [IMathElement](./imathelement) | Giao diện cơ sở của bất kỳ phần tử toán học nào: fraction, mathematical text, function, expression có nhiều phần tử, v.v. |
| [IMathElementCollection](./imathelementcollection) | Biểu diễn một tập hợp các phần tử toán học (MathElement). |
| [IMathematicalText](./imathematicaltext) | Văn bản toán học |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Cho phép tạo một phần tử MathematicalText |
| [IMathFraction](./imathfraction) | Xác định đối tượng fraction, bao gồm một tử và một mẫu được ngăn cách bằng một thanh phân số. Thanh phân có thể ngang hoặc chéo, tùy thuộc vào thuộc tính của fraction. Đối tượng fraction cũng được sử dụng để đại diện cho hàm stack, đặt một phần tử lên trên phần tử khác mà không có thanh phân số. |
| [IMathFractionFactory](./imathfractionfactory) | Cho phép tạo một math fraction |
| [IMathFunction](./imathfunction) | Xác định một hàm của một đối số. |
| [IMathFunctionFactory](./imathfunctionfactory) | Cho phép tạo một math function |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Xác định ký hiệu nhóm phía trên hoặc phía dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Cho phép tạo một ký hiệu nhóm toán học |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chữ chỉ số dưới và trên được đặt bên trái của cơ sở. |
| [IMathLimit](./imathlimit) | Xác định đối tượng Limit, bao gồm văn bản trên dòng cơ bản và văn bản kích thước giảm ngay trên hoặc dưới nó. |
| [IMathLimitFactory](./imathlimitfactory) | Cho phép tạo IMathLimit |
| [IMathMatrix](./imathmatrix) | Xác định đối tượng Matrix, bao gồm các phần tử con được sắp xếp trong một hoặc nhiều hàng và cột. Lưu ý rằng ma trận không có delimiter tích hợp. Để đặt ma trận trong ngoặc, bạn nên sử dụng đối tượng delimiter (IMathDelimiter). Các đối số null có thể được dùng để tạo khoảng trống trong ma trận. |
| [IMathMatrixFactory](./imathmatrixfactory) | Cho phép tạo một math matrix |
| [IMathNaryOperator](./imathnaryoperator) | Xác định một đối tượng toán học N-ary, chẳng hạn như Summation, Union, Intersection, Integral. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ về toán tử N-ary là: Summation, Union, Intersection, Integral. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Cho phép tạo IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Xác định các thuộc tính của IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Đoạn văn toán học là một container cho các math block (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Cho phép tạo một math paragraph |
| [IMathPhantom](./imathphantom) | Biểu diễn một đối tượng phantom math (&lt;m:phant&gt;) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một phantom có thể ẩn biểu thức cơ sở trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc giữ chỗ. Tính hiển thị và hành vi hình học được kiểm soát bằng các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp. |
| [IMathPortion](./imathportion) | Biểu diễn một phần có ngữ cảnh toán học bên trong. |
| [IMathRadical](./imathradical) | Xác định hàm radical, bao gồm một cơ sở và một bậc tùy chọn. Ví dụ về đối tượng radical là √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Cho phép tạo một math radical |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Xác định đối tượng Sub-Superscript, bao gồm một cơ sở và chữ chỉ số dưới và trên được đặt bên phải của cơ sở. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Cho phép tạo IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Xác định đối tượng subscript, bao gồm một cơ sở và chữ chỉ số dưới kích thước giảm được đặt bên dưới và bên phải. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Cho phép tạo IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Xác định đối tượng superscript, bao gồm một cơ sở và chữ chỉ số trên kích thước giảm được đặt phía trên và bên phải |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Cho phép tạo IMathSuperscriptElement |

## Liệt kê

| Liệt kê | Mô tả |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Vị trí và kích thước của các delimiter so với nội dung của các toán hạng |
| [MathFractionTypes](./mathfractiontypes) | Các loại Fraction |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Các hàm toán học thông thường của một đối số |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Các hàm toán học thông thường của hai đối số |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Căn chỉnh ngang |
| [MathIntegralTypes](./mathintegraltypes) | Các loại tích phân toán học |
| [MathJustification](./mathjustification) | Xác định việc căn chỉnh của math paragraph (một loạt các thể hiện liên tiếp của văn bản toán học trong cùng một đoạn). |
| [MathLimitLocations](./mathlimitlocations) | Vị trí của các giới hạn (subscript/superscript) trong các toán tử n-ary. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Các loại toán tử Nary IMathNaryOperator (ngoại trừ các tích phân) Đối với tích phân [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Kiểu khoảng cách dọc giữa các cột trong ma trận hoặc mảng |
| [MathSpacingRules](./mathspacingrules) | Các loại khoảng cách (khoảng cách ngang) giữa các cột của ma trận |
| [MathTopBotPositions](./mathtopbotpositions) | Liệt kê vị trí trên/dưới |
| [MathVerticalAlignment](./mathverticalalignment) | Căn chỉnh dọc |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->