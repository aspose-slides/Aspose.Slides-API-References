---
title: set_size method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Thiết lập kích thước slide theo kiểu và phóng to nội dung hiện có.

```python
def set_size(self, type, scale_type):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/vi/aspose.slides/slidesizetype) | Kích thước slide được định trước sẽ áp dụng. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype) | Chế độ phóng to nội dung sẽ được sử dụng. |

### Ghi chú

Gán bất kỳ giá trị nào khác [`SlideSizeType.CUSTOM`](/slides/python-net/vi/aspose.slides/slidesizetype/CUSTOM) sẽ điều chỉnh [`ISlideSize.size`](/slides/python-net/vi/aspose.slides/islidesize/size) dựa trên loại đã chọn, trong khi vẫn giữ [`ISlideSize.orientation`](/slides/python-net/vi/aspose.slides/islidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Thiết lập kích thước slide một cách rõ ràng và phóng to nội dung hiện có.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| width | **float** | Chiều rộng slide mới, tính bằng điểm. |
| height | **float** | Chiều cao slide mới, tính bằng điểm. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype) | Chế độ phóng to nội dung sẽ được sử dụng. |

### Ghi chú

Điều này sẽ đặt lại thuộc tính [`ISlideSize.type`](/slides/python-net/vi/aspose.slides/islidesize/type) thành [`SlideSizeType.CUSTOM`](/slides/python-net/vi/aspose.slides/slidesizetype/CUSTOM) và thiết lập [`ISlideSize.orientation`](/slides/python-net/vi/aspose.slides/islidesize/orientation).

### Xem thêm
* lớp [`ISlideSize`](/slides/python-net/vi/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/vi/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/vi/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)