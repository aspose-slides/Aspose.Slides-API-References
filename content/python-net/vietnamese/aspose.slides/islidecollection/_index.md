---
title: ISlideCollection class
second_title: Aspose.Slides cho Python thông qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides/islidecollection/
---
## ISlideCollection lớp

Biểu diễn một bộ sưu tập các slide.

Kiểu ISlideCollection cung cấp các thành viên sau:

Lấy phần tử tại chỉ mục xác định.
            Chỉ đọc [`ISlide`](/slides/python-net/vi/aspose.slides/islide).

## Chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides/islidecollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/vi/aspose.slides/islidecollection/add_clone/#islide) | Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/vi/aspose.slides/islidecollection/add_clone/#islide-isection) | Thêm một bản sao của slide đã chỉ định vào cuối phần đã chỉ định. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/vi/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/vi/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Thêm một bản sao của slide nguồn đã chỉ định vào cuối bộ sưu tập.<br/>            Bố cục phù hợp sẽ được chọn tự động từ master đã chỉ định <br/>            (bố cục phù hợp là bố cục có cùng Type hoặc Name như <br/>            bố cục của slide nguồn). Nếu không có bố cục phù hợp thì<br/>            bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout <br/>            là true) hoặc sẽ ném ra PptxEditException (nếu allowCloneMissingLayout<br/>            là false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_clone/#int-islide) | Chèn một bản sao của slide đã chỉ định vào vị trí xác định của bộ sưu tập. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Chèn một bản sao của slide đã chỉ định vào vị trí xác định của bộ sưu tập. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Chèn một bản sao của slide nguồn đã chỉ định vào vị trí xác định của bộ sưu tập.<br/>            Bố cục phù hợp sẽ được chọn tự động từ master đã chỉ định <br/>            (bố cục phù hợp là bố cục có cùng Type hoặc Name như <br/>            bố cục của slide nguồn). Nếu không có bố cục phù hợp thì<br/>            bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout <br/>            là true) hoặc sẽ ném ra PptxEditException (nếu allowCloneMissingLayout<br/>            là false). |
| [`to_array(self)`](/slides/python-net/vi/aspose.slides/islidecollection/to_array/#) | Tạo và trả về một mảng chứa tất cả các slide. |
| [`to_array(self, start_index, count)`](/slides/python-net/vi/aspose.slides/islidecollection/to_array/#int-int) | Tạo và trả về một mảng chứa tất cả các slide trong phạm vi đã chỉ định. |
| [`reorder(self, index, slide)`](/slides/python-net/vi/aspose.slides/islidecollection/reorder/#int-islide) | Di chuyển slide từ bộ sưu tập đến vị trí đã chỉ định. |
| [`reorder(self, index, slides)`](/slides/python-net/vi/aspose.slides/islidecollection/reorder/#int-listislide) | Di chuyển các slide từ bộ sưu tập đến vị trí đã chỉ định.<br/>            Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự chúng xuất hiện trong danh sách. |
| [`add_from_pdf(self, path)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_pdf/#str) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, cân nhắc các tùy chọn nhập PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_html(self, html_text)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_html/#str) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [`add_from_html(self, html_stream)`](/slides/python-net/vi/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-str) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [`add_empty_slide(self, layout)`](/slides/python-net/vi/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Thêm một slide trống mới vào cuối bộ sưu tập. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/vi/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Chèn một bản sao của slide đã chỉ định vào vị trí xác định của bộ sưu tập. |
| [`remove(self, value)`](/slides/python-net/vi/aspose.slides/islidecollection/remove/#islide) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides/islidecollection/remove_at/#int) | Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập. |
| [`index_of(self, slide)`](/slides/python-net/vi/aspose.slides/islidecollection/index_of/#islide) | Trả về chỉ mục của slide đã chỉ định trong bộ sưu tập. |


### Xem thêm
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)