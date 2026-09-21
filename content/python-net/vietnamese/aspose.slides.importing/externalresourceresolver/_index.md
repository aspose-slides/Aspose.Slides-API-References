---
title: ExternalResourceResolver class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver lớp

Lớp Callback được sử dụng để giải quyết các tài nguyên bên ngoài trong quá trình nhập tài liệu Html, Svg.  
Sử dụng trình giải quyết này có thể tạo ra lỗ hổng khi tệp HTML hoặc SVG do khách hàng cung cấp sẽ làm phần mềm máy chủ truy cập tệp cục bộ hoặc trên mạng. Hãy sử dụng một cách thận trọng. Được khuyến nghị không chỉ định ExternalResourceResolver (chỉ đọc các đối tượng nhúng) hoặc tạo một lớp con nào đó để kiểm tra xem uri được chỉ định có hợp lệ hay không.

Kiểu ExternalResourceResolver cung cấp các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/vi/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Giải quyết URI tuyệt đối từ các URI nền và tương đối. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/vi/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Ánh xạ một URI tới đối tượng chứa tài nguyên thực tế. |


### Xem thêm
* module [`aspose.slides.importing`](/slides/python-net/vi/aspose.slides.importing)
* thư viện [`Aspose.Slides`](/slides/python-net)