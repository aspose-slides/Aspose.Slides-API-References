---
title: apply_default_paragraph_indents_shifts method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Thiết lập các dịch chuyển mặc định khác không cho Indent và MarginLeft của đoạn văn khi bật dấu đầu dòng (giống như PowerPoint làm khi bật dấu đầu dòng/đánh số cho đoạn văn). Nếu tắt dấu đầu dòng thì chỉ thiết lập lại Indent và MarginLeft của đoạn văn (giống như PowerPoint làm khi tắt dấu đầu dòng/đánh số). Các dịch chuyển Indent được áp dụng dựa trên ngữ cảnh dấu đầu hiện tại - IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các dịch chuyển khác không được áp dụng cho Indent và MarginLeft thực tế của đoạn văn hiện tại (đảm bảo giá trị kết quả là giá trị cục bộ).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gọi phương thức này không quan trọng và sẽ ném **System.InvalidOperationException** trong các trường hợp sau:<br/>            nếu đối tượng cha được định dạng không phải là một đoạn văn (ví dụ gọi ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() sẽ ném ngoại lệ);<br/>            hoặc nếu đoạn văn chưa được thêm vào bất kỳ bộ sưu tập ITextFrame.Paragraphs nào (hãy thêm nó trước); |



### Xem thêm
* lớp [`BulletFormat`](/slides/python-net/vi/aspose.slides/bulletformat)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)