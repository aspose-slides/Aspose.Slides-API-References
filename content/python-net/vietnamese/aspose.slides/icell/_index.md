---
title: ICell class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/icell/
---
## Lớp ICell

Biểu diễn một ô trong một bảng.

Kiểu ICell cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`offset_x`](/slides/python-net/vi/aspose.slides/icell/offset_x/) | Trả về khoảng cách từ phía trái của bảng tới phía trái của ô.<br/>            Chỉ đọc **float**. |
| [`offset_y`](/slides/python-net/vi/aspose.slides/icell/offset_y/) | Trả về khoảng cách từ phía trên của bảng tới phía trên của ô.<br/>            Chỉ đọc **float**. |
| [`first_row_index`](/slides/python-net/vi/aspose.slides/icell/first_row_index/) | Trả về chỉ mục của hàng đầu tiên được ô bao phủ.<br/>            Chỉ đọc **int**. |
| [`first_column_index`](/slides/python-net/vi/aspose.slides/icell/first_column_index/) | Trả về chỉ mục của cột đầu tiên được ô bao phủ.<br/>            Chỉ đọc **int**. |
| [`width`](/slides/python-net/vi/aspose.slides/icell/width/) | Trả về chiều rộng của ô.<br/>            Chỉ đọc **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/icell/height/) | Trả về chiều cao của ô.<br/>            Chỉ đọc **float**. |
| [`minimal_height`](/slides/python-net/vi/aspose.slides/icell/minimal_height/) | Trả về chiều cao tối thiểu của ô.<br/>            Đây là tổng chiều cao tối thiểu của tất cả các hàng được ô bao phủ.<br/>            Chỉ đọc **float**. |
| [`margin_left`](/slides/python-net/vi/aspose.slides/icell/margin_left/) | Trả về hoặc đặt lề trái trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_right`](/slides/python-net/vi/aspose.slides/icell/margin_right/) | Trả về hoặc đặt lề phải trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_top`](/slides/python-net/vi/aspose.slides/icell/margin_top/) | Trả về hoặc đặt lề trên trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_bottom`](/slides/python-net/vi/aspose.slides/icell/margin_bottom/) | Trả về hoặc đặt lề dưới trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`text_vertical_type`](/slides/python-net/vi/aspose.slides/icell/text_vertical_type/) | Trả về hoặc đặt loại văn bản dọc.<br/>            Đọc/ghi [`TextVerticalType`](/slides/python-net/vi/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/vi/aspose.slides/icell/text_anchor_type/) | Trả về hoặc đặt loại neo văn bản.<br/>            Đọc/ghi [`TextAnchorType`](/slides/python-net/vi/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/vi/aspose.slides/icell/anchor_center/) | Xác định hộp văn bản có được căn giữa bên trong ô hay không.<br/>            Đọc/ghi **bool**. |
| [`first_column`](/slides/python-net/vi/aspose.slides/icell/first_column/) | Lấy cột đầu tiên của ô.<br/>            Chỉ đọc [`IColumn`](/slides/python-net/vi/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/vi/aspose.slides/icell/first_row/) | Lấy hàng đầu tiên của ô.<br/>            Chỉ đọc [`IRow`](/slides/python-net/vi/aspose.slides/irow). |
| [`col_span`](/slides/python-net/vi/aspose.slides/icell/col_span/) | Trả về số cột lưới trong lưới bảng của bảng cha mà ô hiện tại sẽ trải qua.<br/>            Thuộc tính này cho phép các ô có vẻ như được hợp nhất, vì chúng trải ngang qua ranh giới dọc<br/>            của các ô khác trong bảng.<br/>            Chỉ đọc **int**. |
| [`row_span`](/slides/python-net/vi/aspose.slides/icell/row_span/) | Trả về số hàng mà một ô đã hợp nhất trải qua. Điều này được sử dụng kết hợp<br/>            với thuộc tính vMerge trên các ô khác để chỉ định ô bắt đầu của một sự hợp nhất ngang.<br/>            Chỉ đọc **int**. |
| [`text_frame`](/slides/python-net/vi/aspose.slides/icell/text_frame/) | Trả về khung văn bản của ô.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`table`](/slides/python-net/vi/aspose.slides/icell/table/) | Trả về đối tượng Table cha của ô.<br/>            Chỉ đọc [`ITable`](/slides/python-net/vi/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/vi/aspose.slides/icell/is_merged_cell/) | Trả về true nếu ô được hợp nhất với bất kỳ ô đã điều chỉnh nào, ngược lại trả về false.<br/>            Chỉ đọc **bool**. |
| [`cell_format`](/slides/python-net/vi/aspose.slides/icell/cell_format/) | Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này.<br/>            Chỉ đọc [`ICellFormat`](/slides/python-net/vi/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/vi/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/icell/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/vi/aspose.slides/icell/split_by_col_span/#int) | Tách ô thành hai ô theo chỉ mục của cột. |
| [`split_by_row_span(self, index)`](/slides/python-net/vi/aspose.slides/icell/split_by_row_span/#int) | Tách ô thành hai ô theo chỉ mục của hàng. |
| [`split_by_height(self, height)`](/slides/python-net/vi/aspose.slides/icell/split_by_height/#float) | Tách ô theo chiều cao. |
| [`split_by_width(self, width)`](/slides/python-net/vi/aspose.slides/icell/split_by_width/#float) | Tách ô theo chiều rộng. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)