---
title: get_object_storing_location method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Xác định vị trí lưu trữ đối tượng.
            Phương thức này được gọi một lần cho mỗi id đối tượng.
            Không có đảm bảo rằng sẽ không có hai đối tượng có cùng dữ liệu, semanticName và contentType nhưng có id khác nhau.

### Trả về

Decision



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| id | **int** | Id của đối tượng. Id này là duy nhất trong toàn bộ thao tác lưu. |
| entity_data | **bytes** | Dữ liệu nhị phân của đối tượng. Tham số này có thể là None nếu dữ liệu nhị phân của đối tượng chưa được tạo. |
| semantic_name | **str** | Văn bản ngắn mô tả ý nghĩa của đối tượng. Controller có thể sử dụng nó như một phần của tên đối tượng bên ngoài, nhưng việc đảm bảo tên là duy nhất và chỉ chứa các ký tự cho phép thuộc về dispatcher. |
| content_type | **str** | Kiểu MIME của đối tượng. |
| recomended_extension | **str** | Phần mở rộng tên tệp, được đề xuất cho kiểu MIME này. |



### Xem thêm
* lớp [`ILinkEmbedController`](/slides/python-net/vi/aspose.slides.export/ilinkembedcontroller)
* liệt kê [`LinkEmbedDecision`](/slides/python-net/vi/aspose.slides.export/linkembeddecision)
* mô-đun [`aspose.slides.export`](/slides/python-net/vi/aspose.slides.export)
* thư viện [`Aspose.Slides`](/slides/python-net)