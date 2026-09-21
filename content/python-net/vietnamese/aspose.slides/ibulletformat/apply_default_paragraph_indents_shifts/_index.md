---
title: apply_default_paragraph_indents_shifts method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Đặt các dịch chuyển không-zero mặc định cho Indent và MarginLeft thực tế của đoạn khi bật dấu đầu dòng (giống như PowerPoint làm khi bật dấu đầu dòng/đánh số trong đó). Nếu dấu đầu dòng bị tắt thì chỉ đặt lại Indent và MarginLeft của đoạn (giống như PowerPoint làm khi tắt dấu đầu dòng/đánh số trong đó). Các dịch chuyển Indent được áp dụng dựa trên ngữ cảnh dấu đầu dòng hiện tại — IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các dịch chuyển không-zero được áp dụng cho Indent và MarginLeft thực tế của đoạn hiện tại (để các giá trị kết quả trở thành giá trị cục bộ).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gọi phương thức này không quan trọng và ném **System.InvalidOperationException** trong các trường hợp sau:<br/>            nếu parent formatted object không phải là một paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception);<br/>            hoặc nếu paragraph không được thêm vào bất kỳ ITextFrame.Paragraphs collection nào (add it first); |



### Xem thêm
* lớp [`IBulletFormat`](/slides/python-net/vi/aspose.slides/ibulletformat)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)