---
title: group method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Đặt phần tử này vào một nhóm bằng dấu ngoặc nhọn dưới

### Trả về

Một thể hiện mới của kiểu [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Đặt phần tử này vào một nhóm bằng ký tự nhóm như dấu ngoặc nhọn dưới hoặc ký tự khác

### Trả về

Một thể hiện mới của kiểu [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| character | **char** | Ký tự nhóm như DẤU NHÁM ĐỎ DƯỚI (U+23DF) hoặc bất kỳ ký tự nào khác |
| position | [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions) | Vị trí của ký tự nhóm |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions) | Canh dọc của ký tự nhóm.<br/><br/>            Xác định cách căn chỉnh đối tượng so với đường cơ sở.<br/><br/>            Ví dụ, khi ký tự nhóm ở phía trên đối tượng, <br/><br/>            VerticalJustification của Top biểu thị rằng phần trên của đối tượng nằm trên đường cơ sở;<br/><br/>            khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên đường cơ sở |



### Xem thêm
* lớp [`IMathGroupingCharacter`](/slides/python-net/vi/aspose.slides.mathtext/imathgroupingcharacter)
* lớp [`MathLimit`](/slides/python-net/vi/aspose.slides.mathtext/mathlimit)
* liệt kê [`MathTopBotPositions`](/slides/python-net/vi/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)