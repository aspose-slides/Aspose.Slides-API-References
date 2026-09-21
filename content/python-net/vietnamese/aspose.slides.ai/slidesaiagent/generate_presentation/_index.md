---
title: generate_presentation method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Tạo một đối tượng bản trình bày từ mô tả bằng văn bản. Cung cấp chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| description | **str** | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/vi/aspose.slides.ai/presentationcontentamounttype) | Lượng nội dung trong bản trình bày được tạo ra. |

### Ghi chú

Ví dụ dưới đây sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) mặc định, được tạo bởi constructor **SlidesAIAgent.#ctor** không có tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp `HttpClient` của bạn), truyền một triển khai [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) vào constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Các triển khai khả dụng bao gồm:

* [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lệnh trò chuyện AI không được là None hoặc rỗng. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Tạo một đối tượng bản trình bày từ mô tả bằng văn bản. Cung cấp chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| description | **str** | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/vi/aspose.slides.ai/presentationcontentamounttype) | Lượng nội dung trong bản trình bày được tạo ra. |
| presentation_template | [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) | Một bản trình bày được dùng làm mẫu cho bố cục và thiết kế, thay thế mẫu mặc định. |

### Ghi chú

Ví dụ dưới đây sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) mặc định, được tạo bởi constructor **SlidesAIAgent.#ctor** không có tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp `HttpClient` của bạn), truyền một triển khai [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) vào constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Các triển khai khả dụng bao gồm:

* [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Mẫu trình chiếu không được cung cấp. |
| **RuntimeError(Proxy error(ArgumentException))** | Lệnh trò chuyện AI không được là None hoặc rỗng. |

### Xem thêm
* lớp [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* lớp [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* lớp [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)
* lớp [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* liệt_kê [`PresentationContentAmountType`](/slides/python-net/vi/aspose.slides.ai/presentationcontentamounttype)
* lớp [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư_viện [`Aspose.Slides`](/slides/python-net)