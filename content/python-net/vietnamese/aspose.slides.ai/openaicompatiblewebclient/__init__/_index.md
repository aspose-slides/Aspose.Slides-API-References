---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Tạo một thể hiện của client web tương thích OpenAI.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| model | **str** | Tên mô hình được nhà cung cấp LLM hỗ trợ. |
| api_key | **str** | Khóa API (token). |
| base_url | **str** | URL cơ sở của LLM tương thích OpenAI. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị API key không được là None hoặc rỗng. |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị mô hình văn bản không được là None hoặc rỗng. |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị Base URL không được là None hoặc rỗng. |

### Xem Thêm
* lớp [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)
* module [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)