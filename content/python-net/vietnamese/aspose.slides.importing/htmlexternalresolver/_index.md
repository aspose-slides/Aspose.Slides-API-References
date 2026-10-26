---
title: HtmlExternalResolver class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver lớp

Đối tượng Callback được sử dụng bởi quy trình nhập HTML để lấy các đối tượng được tham chiếu như hình ảnh.  
Sử dụng resolver này có thể tạo ra lỗ hổng khi tệp HTML do khách hàng cung cấp khiến phần mềm máy chủ truy cập tệp cục bộ hoặc tệp trên mạng. Hãy sử dụng một cách thận trọng. Khuyến nghị không chỉ định HtmlExternalResolver (chỉ các đối tượng nhúng sẽ được đọc) hoặc tạo một lớp con nào đó kiểm tra xem uri được chỉ định có hợp lệ hay không.

Kiểu HtmlExternalResolver công bố các thành viên sau:

## Hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/vi/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/vi/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |


### Xem thêm
* module [`aspose.slides.importing`](/slides/python-net/vi/aspose.slides.importing)
* thư viện [`Aspose.Slides`](/slides/python-net)