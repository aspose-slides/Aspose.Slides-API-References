---
title: Cell class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/cell/
---
## Lớp Cell

Biểu diễn một ô của bảng.

Kiểu Cell mở ra các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`offset_x`](/slides/python-net/vi/aspose.slides/cell/offset_x/) | Trả về khoảng cách từ phía trái của bảng tới phía trái của ô.<br/>            Chỉ đọc **float**. |
| [`offset_y`](/slides/python-net/vi/aspose.slides/cell/offset_y/) | Trả về khoảng cách từ phía trên của bảng tới phía trên của ô.<br/>            Chỉ đọc **float**. |
| [`first_row_index`](/slides/python-net/vi/aspose.slides/cell/first_row_index/) | Trả về chỉ số của hàng đầu tiên được ô bao phủ.<br/>            Chỉ đọc **int**. |
| [`first_column_index`](/slides/python-net/vi/aspose.slides/cell/first_column_index/) | Trả về chỉ số của cột đầu tiên được ô bao phủ.<br/>            Chỉ đọc **int**. |
| [`width`](/slides/python-net/vi/aspose.slides/cell/width/) | Trả về chiều rộng của ô.<br/>            Chỉ đọc **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/cell/height/) | Trả về chiều cao của ô.<br/>            Chỉ đọc **float**. |
| [`minimal_height`](/slides/python-net/vi/aspose.slides/cell/minimal_height/) | Trả về chiều cao tối thiểu của một ô.<br/>            Đây là tổng chiều cao tối thiểu của tất cả các hàng được ô bao phủ.<br/>            Chỉ đọc **float**. |
| [`margin_left`](/slides/python-net/vi/aspose.slides/cell/margin_left/) | Trả về hoặc thiết lập lề trái trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_right`](/slides/python-net/vi/aspose.slides/cell/margin_right/) | Trả về hoặc thiết lập lề phải trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_top`](/slides/python-net/vi/aspose.slides/cell/margin_top/) | Trả về hoặc thiết lập lề trên trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_bottom`](/slides/python-net/vi/aspose.slides/cell/margin_bottom/) | Trả về hoặc thiết lập lề dưới trong TextFrame.<br/>            Đọc/ghi **float**. |
| [`text_vertical_type`](/slides/python-net/vi/aspose.slides/cell/text_vertical_type/) | Trả về hoặc thiết lập loại văn bản dọc.<br/>            Đọc/ghi [`TextVerticalType`](/slides/python-net/vi/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/vi/aspose.slides/cell/text_anchor_type/) | Trả về hoặc thiết lập kiểu neo văn bản.<br/>            Đọc/ghi [`TextAnchorType`](/slides/python-net/vi/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/vi/aspose.slides/cell/anchor_center/) | Xác định việc hộp văn bản có được căn giữa bên trong ô hay không.<br/>            Đọc/ghi **bool**. |
| [`first_row`](/slides/python-net/vi/aspose.slides/cell/first_row/) | Lấy hàng đầu tiên của ô.<br/>            Chỉ đọc [`IRow`](/slides/python-net/vi/aspose.slides/irow). |
| [`first_column`](/slides/python-net/vi/aspose.slides/cell/first_column/) | Lấy cột đầu tiên của ô.<br/>            Chỉ đọc [`IColumn`](/slides/python-net/vi/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/vi/aspose.slides/cell/col_span/) | Trả về số cột lưới trong lưới bảng của bảng cha mà ô hiện tại sẽ phủ.<br/>            Thuộc tính này cho phép các ô<br/>            có vẻ như được hợp nhất, vì chúng phủ các ranh giới dọc<br/>            của các ô khác trong bảng.<br/>            Chỉ đọc **int**. |
| [`row_span`](/slides/python-net/vi/aspose.slides/cell/row_span/) | Trả về số hàng mà một ô đã hợp nhất phủ. Điều này được dùng kết hợp<br/>            với thuộc tính vMerge trên các ô khác để chỉ định ô bắt đầu<br/>            của một lần hợp nhất ngang.<br/>            Chỉ đọc **int**. |
| [`text_frame`](/slides/python-net/vi/aspose.slides/cell/text_frame/) | Trả về khung văn bản của ô.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`table`](/slides/python-net/vi/aspose.slides/cell/table/) | Trả về đối tượng Table cha của ô.<br/>            Chỉ đọc [`ITable`](/slides/python-net/vi/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/vi/aspose.slides/cell/is_merged_cell/) | Trả về true nếu ô đã được hợp nhất với bất kỳ ô đã điều chỉnh nào, ngược lại trả về false.<br/>            Chỉ đọc **bool**. |
| [`cell_format`](/slides/python-net/vi/aspose.slides/cell/cell_format/) | Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này.<br/>            Chỉ đọc [`ICellFormat`](/slides/python-net/vi/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/vi/aspose.slides/cell/slide/) | Trả về slide cha của ô.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/cell/presentation/) | Trả về bản trình chiếu cha của ô.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/vi/aspose.slides/cell/split_by_col_span/#int) | Chia ô thành hai ô theo chỉ số cột. |
| [`split_by_row_span(self, index)`](/slides/python-net/vi/aspose.slides/cell/split_by_row_span/#int) | Chia ô thành hai ô theo chỉ số hàng. |
| [`split_by_height(self, height)`](/slides/python-net/vi/aspose.slides/cell/split_by_height/#float) | Chia ô theo chiều cao. |
| [`split_by_width(self, width)`](/slides/python-net/vi/aspose.slides/cell/split_by_width/#float) | Chia ô theo chiều rộng. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)