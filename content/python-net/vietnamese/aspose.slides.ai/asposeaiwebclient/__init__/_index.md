---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Tạo một thể hiện của Aspose AI web client kết nối tới endpoint Aspose LLM mặc định.  
            Đây là client được sử dụng bởi hàm khởi tạo không tham số **SlidesAIAgent.#ctor**, vì vậy việc tạo  
            nó một cách tường minh chỉ cần thiết khi truyền client vào hàm khởi tạo **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**  
            trực tiếp.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Tạo một thể hiện của Aspose AI web client kết nối tới một URL endpoint tùy chỉnh. Sử dụng overload này khi bạn có URL do đội ngũ Aspose.Slides cung cấp; nếu không, hãy sử dụng overload **AsposeAIWebClient.#ctor** với URL mặc định.


```python
def __init__(self, url):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| url | **str** | URL endpoint của Aspose LLM, do đội ngũ Aspose.Slides cung cấp. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL không được để rỗng hoặc null. |



### Xem thêm
* lớp [`AsposeAIWebClient`](/slides/python-net/vi/aspose.slides.ai/asposeaiwebclient)
* mô-đun [`aspose.slides.ai`](/slides/python-net/vi/aspose.slides.ai)
* thư viện [`Aspose.Slides`](/slides/python-net)