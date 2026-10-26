---
title: OpenAIWebClient constructor
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Tạo một thể hiện của client web OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| model | **str** | Mô hình ngôn ngữ OpenAI. Các giá trị khả dụng:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Khóa API OpenAI. |
| organization_id | **str** | ID tổ chức (tùy chọn). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị khóa API không được là None hoặc rỗng. |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị mô hình văn bản không được là None hoặc rỗng. |



### Xem thêm
* lớp [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* mô-đun [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)