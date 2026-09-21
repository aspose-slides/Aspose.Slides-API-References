---
title: PPImage class
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/ppimage/
---
## PPImage lớp

Đại diện cho một hình ảnh trong bản trình bày.

Kiểu PPImage cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`binary_data`](/slides/python-net/vi/aspose.slides/ppimage/binary_data/) | Trả về bản sao dữ liệu của hình ảnh.<br/>            Chỉ đọc **int**[]. |
| [`image`](/slides/python-net/vi/aspose.slides/ppimage/image/) | Trả về bản sao của hình ảnh.<br/>            Chỉ đọc [`IImage`](/slides/python-net/vi/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/vi/aspose.slides/ppimage/svg_image/) | Trả về hoặc đặt đối tượng ISvgImage [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/vi/aspose.slides/ppimage/content_type/) | Trả về loại MIME của hình ảnh, được mã hóa trong [`PPImage.binary_data`](/slides/python-net/vi/aspose.slides/ppimage/binary_data).<br/>            Chỉ đọc **str**. |
| [`width`](/slides/python-net/vi/aspose.slides/ppimage/width/) | Trả về chiều rộng của hình ảnh.<br/>            Chỉ đọc **int**. |
| [`height`](/slides/python-net/vi/aspose.slides/ppimage/height/) | Trả về chiều cao của hình ảnh.<br/>            Chỉ đọc **int**. |
| [`x`](/slides/python-net/vi/aspose.slides/ppimage/x/) | Trả về độ lệch X của hình ảnh.<br/>            Chỉ đọc **int**. |
| [`y`](/slides/python-net/vi/aspose.slides/ppimage/y/) | Trả về độ lệch Y của hình ảnh.<br/>            Chỉ đọc **int**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/vi/aspose.slides/ppimage/replace_image/#bytes) | Thay thế dữ liệu hình ảnh.<br/>            Dữ liệu của hình ảnh mới.Khi tham số newImageData là None. |
| [`replace_image(self, new_image)`](/slides/python-net/vi/aspose.slides/ppimage/replace_image/#iimage) | Thay thế dữ liệu hình ảnh. Lưu ý: khi Image là metafile - nó sẽ được raster hóa. Sử dụng ReplaceImage(byte[]) thay thế<br/>            Hình ảnh mới.Khi tham số newImage là None. |
| [`replace_image(self, new_image)`](/slides/python-net/vi/aspose.slides/ppimage/replace_image/#ippimage) | Thay thế dữ liệu hình ảnh.<br/>            IPPImage mới.Khi tham số newImage là None. |

### Xem Thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)