---
title: SlidesAIAgent class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent lớp

Cung cấp các tính năng AI cho việc xử lý bản trình chiếu.

Kiểu SlidesAIAgent cung cấp các thành viên sau:

## Các hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Khởi tạo một thể hiện mới của [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent) với một client AI tùy chỉnh.<br/>            Sử dụng phương thức overload này để chỉ định nhà cung cấp AI, cung cấp LLM của riêng bạn, hoặc tùy chỉnh<br/>            kết nối (ví dụ, bằng cách cung cấp `HttpClient` của riêng bạn).<br/>            Bất kỳ triển khai nào của [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) đều có thể được sử dụng, bao gồm:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Để sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định,<br/>            hãy dùng overload **SlidesAIAgent.#ctor** thay thế. |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent/__init__/#) | Khởi tạo một thể hiện mới của [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent) bằng cách sử dụng [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định. Client kết nối tới LLM của Aspose và không yêu cầu cấu hình bổ sung.<br/>            Để sử dụng client AI khác, hãy dùng overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** thay thế. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Tạo một thể hiện bản trình chiếu từ mô tả bằng văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Tạo một thể hiện bản trình chiếu từ mô tả bằng văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu. |
| [`translate(self, presentation, language)`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Dịch một bản trình chiếu sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ). |

### Xem Thêm
* lớp [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* lớp [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient)
* lớp [`OpenAICompatibleWebClient`](/slides/python-net/vi/aspose.slides.ai/openaicompatiblewebclient)
* lớp [`OpenAIWebClient`](/slides/python-net/vi/aspose.slides.ai/openaiwebclient)
* lớp [`SlidesAIAgent`](/slides/python-net/vi/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)