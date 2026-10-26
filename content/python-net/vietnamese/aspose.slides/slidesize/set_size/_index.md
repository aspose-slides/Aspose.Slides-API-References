---
title: set_size method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Đặt kích thước slide theo kiểu và thu phóng nội dung hiện có.

```python
def set_size(self, type, scale_type):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/vi/aspose.slides/slidesizetype) | Kích thước slide định trước để áp dụng. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype) | Chế độ thu phóng nội dung để sử dụng. |

### Ghi chú

Gán bất kỳ giá trị nào khác [`SlideSizeType.CUSTOM`](/slides/python-net/vi/aspose.slides/slidesizetype/CUSTOM) sẽ điều chỉnh [`SlideSize.size`](/slides/python-net/vi/aspose.slides/slidesize/size) dựa trên loại được chọn, trong khi vẫn giữ [`SlideSize.orientation`](/slides/python-net/vi/aspose.slides/slidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Đặt kích thước slide một cách rõ ràng và thu phóng nội dung hiện có.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| width | **float** | Chiều rộng slide mới, tính bằng điểm. |
| height | **float** | Chiều cao slide mới, tính bằng điểm. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype) | Chế độ thu phóng nội dung để sử dụng. |

### Ghi chú

Điều này đặt lại thuộc tính [`SlideSize.type`](/slides/python-net/vi/aspose.slides/slidesize/type) thành [`SlideSizeType.CUSTOM`](/slides/python-net/vi/aspose.slides/slidesizetype/CUSTOM) và thiết lập [`SlideSize.orientation`](/slides/python-net/vi/aspose.slides/slidesize/orientation).

### Xem thêm
* lớp [`SlideSize`](/slides/python-net/vi/aspose.slides/slidesize)
* liệt kê [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype)
* liệt kê [`SlideSizeType`](/slides/python-net/vi/aspose.slides/slidesizetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)