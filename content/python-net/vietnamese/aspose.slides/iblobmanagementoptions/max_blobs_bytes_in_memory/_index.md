---
title: max_blobs_bytes_in_memory property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## thuộc tính max_blobs_bytes_in_memory
Xác định kích thước tổng tối đa (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Theo mặc định, tất cả các BLOB
            are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary
            files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use
            this property to tailor behavior to your environment or requirements.

### Ghi chú

Thuộc tính này bị bỏ qua nếu [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) được đặt thành false, vì khi đó bộ nhớ là vị trí lưu trữ duy nhất khả dụng và việc giới hạn việc sử dụng BLOB trong bộ nhớ không có tác dụng.
            the only storage location available and limiting in-memory BLOB usage has no effect.

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
* lớp [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)