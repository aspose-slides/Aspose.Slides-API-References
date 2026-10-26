---
title: set_license method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Cấp phép cho thành phần.

```python
def set_license(self, license_name):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| license_name | **str** | Có thể là tên tệp đầy đủ hoặc ngắn hoặc tên của tài nguyên được nhúng.<br/><br/>            Sử dụng chuỗi trống để chuyển sang chế độ đánh giá. |

### Ghi chú

Cố gắng tìm giấy phép ở các vị trí sau:

1. Đường dẫn cụ thể.
2. Thư mục của assembly thành phần.
3. Thư mục của assembly gọi của client.
4. Thư mục của entry assembly.
5. Một tài nguyên nhúng trong assembly gọi của client.

**Ghi chú:** Trên .NET Compact Framework, cố gắng tìm giấy phép chỉ ở các vị trí sau:

1. Đường dẫn cụ thể.
2. Một tài nguyên nhúng trong assembly gọi của client.

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

Sử dụng phương pháp này để tải giấy phép từ một luồng.

### Xem thêm
* lớp [`ILicense`](/slides/python-net/vi/aspose.slides/ilicense)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)