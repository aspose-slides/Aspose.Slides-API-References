---
title: group method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Đặt phần tử này vào một nhóm bằng cách sử dụng dấu ngoặc nhọn dưới

### Trả về

Một thể hiện mới của kiểu [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Đặt phần tử này vào một nhóm bằng một ký tự nhóm như dấu ngoặc nhọn dưới hoặc một ký tự khác

### Trả về

Một thể hiện mới của kiểu [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| character | **char** | Ký tự nhóm như BOTTOM CURLY BRACKET (U+23DF) hoặc bất kỳ ký tự nào khác |
| position | [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions) |  |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions) | Căn chỉnh dọc của ký tự nhóm.<br/><br/>            Xác định vị trí căn chỉnh của đối tượng so với đường cơ sở.<br/><br/>            Ví dụ, khi ký tự nhóm ở trên đối tượng, <br/><br/>            VerticalJustification of Top chỉ ra rằng phần trên của đối tượng nằm trên đường cơ sở;<br/><br/>            khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở |

### Xem thêm
* lớp [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)
* lớp [`MathMatrix`](/slides/python-net/vi/aspose.slides.mathtext/mathmatrix)
* enumeration [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)