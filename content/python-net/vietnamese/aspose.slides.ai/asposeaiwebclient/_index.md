---
title: AsposeAIWebClient class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient lớp

Một triển khai [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient) tích hợp sẵn kết nối đến LLM riêng của Aspose. 
Đây là client mặc định được sử dụng bởi constructor **SlidesAIAgent.#ctor** không có tham số.

The AsposeAIWebClient type exposes the following members:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient/__init__/#) | Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định.<br/>            Đây là client được sử dụng bởi constructor **SlidesAIAgent.#ctor** không có tham số, do đó việc tạo<br/>            nó một cách rõ ràng chỉ cần thiết khi truyền client vào constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            trực tiếp. |
| [`__init__(self, url)`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh. Sử dụng overload này khi bạn có URL do nhóm Aspose.Slides cung cấp; nếu không, sử dụng overload **AsposeAIWebClient.#ctor** với URL mặc định. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Tạo một thể hiện cuộc trò chuyện. Khác với các cuộc gọi AI thông thường, các cuộc trò chuyện giữ lại toàn bộ ngữ cảnh. |


### Xem thêm
* lớp [`IAIWebClient`](/slides/python-net/vi/aspose.slides.ai/iaiwebclient)
* mô-đun [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)