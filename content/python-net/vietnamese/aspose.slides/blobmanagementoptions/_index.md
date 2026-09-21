---
title: BlobManagementOptions class
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions lớp

Biểu thị các tùy chọn có thể được sử dụng để quản lý các quy tắc xử lý BLOB và các cài đặt BLOB khác.

Kiểu BlobManagementOptions cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/__init__/#) | Tạo các tùy chọn quản lý blob mặc định mới. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của tệp nguồn - file <br/>            hoặc luồng trong suốt thời gian tồn tại của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp <br/>            cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) <br/>            không thể được thay đổi trong suốt thời gian tồn tại của thể hiện Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Thuộc tính này xác định liệu các tệp tạm thời có thể được tạo ra khi làm việc với BLOBs hay không, điều này giảm đáng kể <br/>            việc tiêu thụ bộ nhớ nhưng yêu cầu quyền để tạo tệp.<br/>            Tất cả các tệp sẽ bị xóa sau khi công việc với bản trình chiếu hoàn thành. |
| [`temp_files_root_path`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Đường dẫn gốc nơi các tệp tạm thời sẽ được tạo. Thư mục tạm thời của hệ thống sẽ được sử dụng mặc định. <br/>            Quy trình lưu trữ cần có quyền <br/>            tạo tệp và thư mục tại đó. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/vi/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Xác định kích thước tối đa tổng cộng (tính bằng byte) mà tất cả các BLOB có thể chiếm trong bộ nhớ. Mặc định, tất cả BLOB<br/>            được tải vào bộ nhớ; chỉ khi đạt đến giới hạn này thì các cơ chế thay thế (như tệp tạm thời)<br/>            mới được sử dụng. Giữ BLOB trong bộ nhớ tối đa hoá hiệu năng nhưng có thể gây tiêu thụ bộ nhớ cao. Sử dụng<br/>            thuộc tính này để điều chỉnh hành vi phù hợp với môi trường hoặc yêu cầu của bạn. |

### Xem Thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)