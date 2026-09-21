---
title: SlidesAIAgent constructor
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Khởi tạo một thể hiện mới của [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent) bằng cách sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định. Máy khách kết nối với LLM riêng của Aspose và không yêu cầu cấu hình bổ sung. Để sử dụng một máy khách AI khác, hãy sử dụng **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload thay thế.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Khởi tạo một thể hiện mới của [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent) với một máy khách AI tùy chỉnh. Sử dụng overload này để chỉ định nhà cung cấp AI, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp `HttpClient` của riêng bạn). Bất kỳ triển khai nào của [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) đều có thể được sử dụng, bao gồm:

* [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)

Để sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định, hãy sử dụng overload **SlidesAIAgent.#ctor** thay thế.

```python
def __init__(self, ai_client):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) | thể hiện AI client. Bất kỳ triển khai nào của [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) đều có thể được sử dụng. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | thể hiện AI client không được cung cấp. |

### Xem thêm
* class [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)