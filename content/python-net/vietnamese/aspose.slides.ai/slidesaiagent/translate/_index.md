---
title: translate method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Dịch một bài thuyết trình sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ).


```python
def translate(self, presentation, language):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) | Bài thuyết trình mục tiêu |
| language | **str** | Ngôn ngữ mục tiêu |

### Ghi chú
Ví dụ dưới đây sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) mặc định, được tạo bởi hàm khởi tạo **SlidesAIAgent.#ctor** không có tham số và kết nối tới LLM riêng của Aspose.  
Để sử dụng nhà cung cấp AI khác, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp `HttpClient` của bạn), truyền một triển khai [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) vào hàm khởi tạo **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Các triển khai khả dụng bao gồm:
* [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Đối tượng presentation không được cung cấp |
| **RuntimeError(Proxy error(ArgumentException))** | Giá trị ngôn ngữ không được để trống hoặc None |

### Xem thêm
* lớp [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* lớp [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* lớp [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)
* lớp [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* lớp [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)