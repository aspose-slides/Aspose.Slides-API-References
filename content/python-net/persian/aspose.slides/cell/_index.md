---
title: Cell class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/cell/
---
## کلاس Cell

نمایانگر یک سلول در جدول است.

نوع Cell اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`offset_x`](/slides/python-net/fa/aspose.slides/cell/offset_x/) | فاصله‌ای از سمت چپ جدول تا سمت چپ سلول را باز می‌گرداند.<br/>            فقط‌خواندنی **float**. |
| [`offset_y`](/slides/python-net/fa/aspose.slides/cell/offset_y/) | فاصله‌ای از سمت بالای جدول تا سمت بالای سلول را باز می‌گرداند.<br/>            فقط‌خواندنی **float**. |
| [`first_row_index`](/slides/python-net/fa/aspose.slides/cell/first_row_index/) | اندیس اولین ردیفی که توسط سلول پوشش داده می‌شود را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`first_column_index`](/slides/python-net/fa/aspose.slides/cell/first_column_index/) | اندیس اولین ستونی که توسط سلول پوشش داده می‌شود را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`width`](/slides/python-net/fa/aspose.slides/cell/width/) | عرض سلول را باز می‌گرداند.<br/>            فقط‌خواندنی **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/cell/height/) | ارتفاع سلول را باز می‌گرداند.<br/>            فقط‌خواندنی **float**. |
| [`minimal_height`](/slides/python-net/fa/aspose.slides/cell/minimal_height/) | حداقل ارتفاع یک سلول را باز می‌گرداند.<br/>            این مجموع ارتفاع‌های حداقل تمام ردیف‌هایی است که توسط سلول پوشش داده می‌شوند.<br/>            فقط‌خواندنی **float**. |
| [`margin_left`](/slides/python-net/fa/aspose.slides/cell/margin_left/) | مارجین چپ در یک TextFrame را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`margin_right`](/slides/python-net/fa/aspose.slides/cell/margin_right/) | مارجین راست در یک TextFrame را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`margin_top`](/slides/python-net/fa/aspose.slides/cell/margin_top/) | مارجین بالا در یک TextFrame را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`margin_bottom`](/slides/python-net/fa/aspose.slides/cell/margin_bottom/) | مارجین پایین در یک TextFrame را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`text_vertical_type`](/slides/python-net/fa/aspose.slides/cell/text_vertical_type/) | نوع متن عمودی را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`TextVerticalType`](/slides/python-net/fa/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/fa/aspose.slides/cell/text_anchor_type/) | نوع لنگر متن را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`TextAnchorType`](/slides/python-net/fa/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/fa/aspose.slides/cell/anchor_center/) | مشخص می‌کند که آیا جعبه متن در داخل سلول مرکزیت دارد یا نه.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`first_row`](/slides/python-net/fa/aspose.slides/cell/first_row/) | اولین ردیف سلول را دریافت می‌کند.<br/>            فقط‌خواندنی [`IRow`](/slides/python-net/fa/aspose.slides/irow). |
| [`first_column`](/slides/python-net/fa/aspose.slides/cell/first_column/) | اولین ستون سلول را دریافت می‌کند.<br/>            فقط‌خواندنی [`IColumn`](/slides/python-net/fa/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/fa/aspose.slides/cell/col_span/) | تعداد ستون‌های شبکه در جدول والد را باز می‌گرداند که باید توسط سلول جاری پوشانده شود.<br/>            این ویژگی به سلول‌ها امکان می‌دهد تا ظاهری مشابه ادغام داشته باشند؛ زیرا مرزهای عمودی سلول‌های دیگر جدول را پوشش می‌دهند.<br/>            فقط‌خواندنی **int**. |
| [`row_span`](/slides/python-net/fa/aspose.slides/cell/row_span/) | تعداد ردیف‌هایی را که یک سلول ادغام‌شده پوشش می‌دهد، باز می‌گرداند. این مقدار در ترکیب<br/>            با ویژگی vMerge در سلول‌های دیگر برای تعیین سلول شروع<br/>            یک ادغام افقی استفاده می‌شود.<br/>            فقط‌خواندنی **int**. |
| [`text_frame`](/slides/python-net/fa/aspose.slides/cell/text_frame/) | قاب متن یک سلول را باز می‌گرداند.<br/>            فقط‌خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`table`](/slides/python-net/fa/aspose.slides/cell/table/) | شیء Table والد برای یک سلول را باز می‌گرداند.<br/>            فقط‌خواندنی [`ITable`](/slides/python-net/fa/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/fa/aspose.slides/cell/is_merged_cell/) | اگر سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد، مقدار true و در غیر اینصورت false را باز می‌گرداند.<br/>            فقط‌خواندنی **bool**. |
| [`cell_format`](/slides/python-net/fa/aspose.slides/cell/cell_format/) | شیء CellFormat که شامل ویژگی‌های قالب‌بندی برای این سلول است را باز می‌گرداند.<br/>            فقط‌خواندنی [`ICellFormat`](/slides/python-net/fa/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/fa/aspose.slides/cell/slide/) | اسلاید والد سلول را باز می‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/cell/presentation/) | ارائه (presentation) والد سلول را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |

## متدها

| متد | توضیح |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/fa/aspose.slides/cell/split_by_col_span/#int) | سلول را با استفاده از اندیس ستون به دو سلول تقسیم می‌کند. |
| [`split_by_row_span(self, index)`](/slides/python-net/fa/aspose.slides/cell/split_by_row_span/#int) | سلول را با استفاده از اندیس ردیف به دو سلول تقسیم می‌کند. |
| [`split_by_height(self, height)`](/slides/python-net/fa/aspose.slides/cell/split_by_height/#float) | سلول را بر اساس ارتفاع تقسیم می‌کند. |
| [`split_by_width(self, width)`](/slides/python-net/fa/aspose.slides/cell/split_by_width/#float) | سلول را بر اساس عرض تقسیم می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)