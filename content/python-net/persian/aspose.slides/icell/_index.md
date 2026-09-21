---
title: ICell class
second_title: Aspose.Slides برای Python از طریق .NET API مرجع
description: 
type: docs
url: /fa/aspose.slides/icell/
---
## ICell کلاس

نمایش یک سلول در جدول.

نوع ICell اعضای زیر را ارائه می‌دهد:

## خصوصیات

| خاصیت | توضیح |
| :- | :- |
| [`offset_x`](/slides/python-net/fa/aspose.slides/icell/offset_x/) | فاصله‌ای را از سمت چپ جدول تا سمت چپ سلول برمی‌گرداند.<br/>            فقط خواندنی **float**. |
| [`offset_y`](/slides/python-net/fa/aspose.slides/icell/offset_y/) | فاصله‌ای را از سمت بالای جدول تا سمت بالای سلول برمی‌گرداند.<br/>            فقط خواندنی **float**. |
| [`first_row_index`](/slides/python-net/fa/aspose.slides/icell/first_row_index/) | نمایهٔ اولین ردیفی که توسط سلول پوشش داده می‌شود را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`first_column_index`](/slides/python-net/fa/aspose.slides/icell/first_column_index/) | نمایهٔ اولین ستونی که توسط سلول پوشش داده می‌شود را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`width`](/slides/python-net/fa/aspose.slides/icell/width/) | عرض سلول را برمی‌گرداند.<br/>            فقط خواندنی **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/icell/height/) | ارتفاع سلول را برمی‌گرداند.<br/>            فقط خواندنی **float**. |
| [`minimal_height`](/slides/python-net/fa/aspose.slides/icell/minimal_height/) | حداقل ارتفاع سلول را برمی‌گرداند.<br/>            این مقدار مجموع حداقل ارتفاع تمام ردیف‌هایی است که توسط سلول پوشش داده شده‌اند.<br/>            فقط خواندنی **float**. |
| [`margin_left`](/slides/python-net/fa/aspose.slides/icell/margin_left/) | حاشیهٔ چپ در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_right`](/slides/python-net/fa/aspose.slides/icell/margin_right/) | حاشیهٔ راست در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_top`](/slides/python-net/fa/aspose.slides/icell/margin_top/) | حاشیهٔ بالا در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_bottom`](/slides/python-net/fa/aspose.slides/icell/margin_bottom/) | حاشیهٔ پایین در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`text_vertical_type`](/slides/python-net/fa/aspose.slides/icell/text_vertical_type/) | نوع متن عمودی را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`TextVerticalType`](/slides/python-net/fa/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/fa/aspose.slides/icell/text_anchor_type/) | نوع لنگر متن را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`TextAnchorType`](/slides/python-net/fa/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/fa/aspose.slides/icell/anchor_center/) | تعیین می‌کند که آیا جعبه متن درون سلول مرکز شده است یا خیر.<br/>            خواندنی/نوشتنی **bool**. |
| [`first_column`](/slides/python-net/fa/aspose.slides/icell/first_column/) | ستون اول سلول را دریافت می‌کند.<br/>            فقط خواندنی [`IColumn`](/slides/python-net/fa/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/fa/aspose.slides/icell/first_row/) | ردیف اول سلول را دریافت می‌کند.<br/>            فقط خواندنی [`IRow`](/slides/python-net/fa/aspose.slides/irow). |
| [`col_span`](/slides/python-net/fa/aspose.slides/icell/col_span/) | تعداد ستون‌های شبکه در جدول والد را برمی‌گرداند که باید توسط سلول فعلی پوشش داده شود.<br/>            این ویژگی به سلول‌ها اجازه می‌دهد ظاهر ادغام داشته باشند، زیرا آن‌ها مرزهای عمودی سلول‌های دیگر در جدول را می‌پوشانند.<br/>            فقط خواندنی **int**. |
| [`row_span`](/slides/python-net/fa/aspose.slides/icell/row_span/) | تعداد ردیف‌هایی را که یک سلول ادغام‌شده پوشش می‌دهد برمی‌گرداند. این مقدار همراه با ویژگی vMerge در سلول‌های دیگر برای تعیین سلول آغازگر ادغام افقی استفاده می‌شود.<br/>            فقط خواندنی **int**. |
| [`text_frame`](/slides/python-net/fa/aspose.slides/icell/text_frame/) | قاب متنی سلول را برمی‌گرداند.<br/>            فقط خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`table`](/slides/python-net/fa/aspose.slides/icell/table/) | شیء Table والد برای یک سلول را برمی‌گرداند.<br/>            فقط خواندنی [`ITable`](/slides/python-net/fa/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/fa/aspose.slides/icell/is_merged_cell/) | اگر سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد true و در غیر این صورت false برمی‌گرداند.<br/>            فقط خواندنی **bool**. |
| [`cell_format`](/slides/python-net/fa/aspose.slides/icell/cell_format/) | شیء CellFormat را که شامل ویژگی‌های قالب‌بندی برای این سلول است برمی‌گرداند.<br/>            فقط خواندنی [`ICellFormat`](/slides/python-net/fa/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/fa/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/icell/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/fa/aspose.slides/icell/split_by_col_span/#int) | سلول را به دو سلول با استفاده از اندیس ستون تقسیم می‌کند. |
| [`split_by_row_span(self, index)`](/slides/python-net/fa/aspose.slides/icell/split_by_row_span/#int) | سلول را به دو سلول با استفاده از اندیس ردیف تقسیم می‌کند. |
| [`split_by_height(self, height)`](/slides/python-net/fa/aspose.slides/icell/split_by_height/#float) | سلول را بر حسب ارتفاع تقسیم می‌کند. |
| [`split_by_width(self, width)`](/slides/python-net/fa/aspose.slides/icell/split_by_width/#float) | سلول را بر حسب عرض تقسیم می‌کند. |


### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)