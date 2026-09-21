---
title: enclose method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Bao một phần tử toán học trong dấu ngoặc

### Trả về

Phần tử toán học kiểu [`IMathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/imathdelimiter) bao gồm dấu ngoặc



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Bao một phần tử toán học trong các ký tự được chỉ định như dấu ngoặc hoặc các ký tự khác làm khung

### Trả về

Nếu `beginning_character` và `ending_character` là None,
            các thuộc tính tương ứng chỉ được gán giá trị và không tạo đối tượng mới (trả về thể hiện này).
            Nếu không, trả về phần tử toán học mới kiểu Delimiter bao gồm các ký tự được chỉ định làm khung
            và thể hiện của [`MathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter) được bao trong đó.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| beginning_character | **char** | Ký tự đầu (thường là ngoặc trái) |
| ending_character | **char** | Ký tự cuối (thường là ngoặc phải) |



### Xem thêm
* lớp [`IMathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/imathdelimiter)
* lớp [`MathDelimiter`](/slides/python-net/vi/aspose.slides.mathtext/mathdelimiter)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)