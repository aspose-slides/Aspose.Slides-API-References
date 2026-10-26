---
title: Hyperlink constructor
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Tạo một thể hiện của siêu liên kết.


```python
def __init__(self, url):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| url | **str** | URL của siêu liên kết. |


## __init__(self, slide) {#islide}
Tạo một thể hiện của siêu liên kết mà trỏ tới slide cụ thể.
            Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.


```python
def __init__(self, slide):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide mục tiêu. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Tạo một thể hiện của siêu liên kết bằng cách sử dụng một siêu liên kết khác làm nguồn, ghi đè các thuộc tính phụ.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink) | Siêu liên kết nguồn |
| target_frame | **str** | Khung mục tiêu |
| tooltip | **str** | Văn bản chú giải |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Xem thêm
* lớp [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)