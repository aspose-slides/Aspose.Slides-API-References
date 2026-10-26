---
title: set_license method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Cấp phép cho thành phần.

```python
def set_license(self, license_name):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| license_name | **str** | Có thể là tên tập tin đầy đủ hoặc ngắn hoặc tên của một tài nguyên được nhúng.<br/><br/>            Sử dụng chuỗi rỗng để chuyển sang chế độ đánh giá. |

### Ghi chú

Cố gắng tìm giấy phép ở các vị trí sau:

1. Đường dẫn cụ thể.

2. Thư mục của assembly thành phần.

3. Thư mục của assembly gọi của client.

4. Thư mục của entry assembly.

5. Một tài nguyên được nhúng trong assembly gọi của client.

**Note:** Trên .NET Compact Framework, chỉ cố gắng tìm giấy phép ở các vị trí sau:

1. Đường dẫn cụ thể.

2. Một tài nguyên được nhúng trong assembly gọi của client.

## set_license(self, stream) {#iorawiobase}
Cấp phép cho thành phần.

```python
def set_license(self, stream):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Một luồng chứa giấy phép. |

### Ghi chú

Sử dụng phương thức này để tải giấy phép từ một luồng.

### Xem thêm
* lớp [`License`](/slides/python-net/vi/aspose.slides/license)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)