---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory thuộc tính
Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả BLOBs có thể chiếm trong bộ nhớ. Theo mặc định, tất cả BLOBs được tải vào bộ nhớ; chỉ khi đạt đến giới hạn này thì các cơ chế thay thế (chẳng hạn như tệp tạm thời) mới được sử dụng. Giữ BLOBs trong bộ nhớ tối ưu hiệu năng nhưng có thể gây sử dụng bộ nhớ cao. Sử dụng thuộc tính này để điều chỉnh hành vi cho môi trường hoặc yêu cầu của bạn.


### Ghi chú

Thuộc tính này bị bỏ qua nếu [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất có sẵn và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có tác dụng.

### Định nghĩa:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Xem thêm
* lớp [`BlobManagementOptions`](/slides/python-net/vi/aspose.slides/blobmanagementoptions)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)