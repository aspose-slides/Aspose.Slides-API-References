---
title: Cell class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/cell/
---
## فئة Cell

يمثل خلية في جدول.

يعرض نوع Cell الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`offset_x`](/slides/python-net/ar/aspose.slides/cell/offset_x/) | يرجع مسافة من الجانب الأيسر للجدول إلى الجانب الأيسر للخلية.<br/>            للقراءة فقط **float**. |
| [`offset_y`](/slides/python-net/ar/aspose.slides/cell/offset_y/) | يرجع مسافة من الجانب العلوي للجدول إلى الجانب العلوي للخلية.<br/>            للقراءة فقط **float**. |
| [`first_row_index`](/slides/python-net/ar/aspose.slides/cell/first_row_index/) | يرجع فهرس الصف الأول الذي تغطيه الخلية.<br/>            للقراءة فقط **int**. |
| [`first_column_index`](/slides/python-net/ar/aspose.slides/cell/first_column_index/) | يرجع فهرس العمود الأول الذي تغطيه الخلية.<br/>            للقراءة فقط **int**. |
| [`width`](/slides/python-net/ar/aspose.slides/cell/width/) | يرجع عرض الخلية.<br/>            للقراءة فقط **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/cell/height/) | يرجع ارتفاع الخلية.<br/>            للقراءة فقط **float**. |
| [`minimal_height`](/slides/python-net/ar/aspose.slides/cell/minimal_height/) | يرجع الحد الأدنى لارتفاع الخلية.<br/>            هذا هو مجموع الارتفاعات الدنيا لجميع الصفوف التي تغطيها الخلية.<br/>            للقراءة فقط **float**. |
| [`margin_left`](/slides/python-net/ar/aspose.slides/cell/margin_left/) | يرجع أو يضبط الهامش الأيسر في TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_right`](/slides/python-net/ar/aspose.slides/cell/margin_right/) | يرجع أو يضبط الهامش الأيمن في TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_top`](/slides/python-net/ar/aspose.slides/cell/margin_top/) | يرجع أو يضبط الهامش العلوي في TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_bottom`](/slides/python-net/ar/aspose.slides/cell/margin_bottom/) | يرجع أو يضبط الهامش السفلي في TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`text_vertical_type`](/slides/python-net/ar/aspose.slides/cell/text_vertical_type/) | يرجع أو يضبط نوع النص العمودي.<br/>            للقراءة والكتابة [`TextVerticalType`](/slides/python-net/ar/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ar/aspose.slides/cell/text_anchor_type/) | يرجع أو يضبط نوع تثبيت النص.<br/>            للقراءة والكتابة [`TextAnchorType`](/slides/python-net/ar/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ar/aspose.slides/cell/anchor_center/) | يحدد ما إذا كان مربع النص مركزيًا داخل الخلية أم لا.<br/>            للقراءة والكتابة **bool**. |
| [`first_row`](/slides/python-net/ar/aspose.slides/cell/first_row/) | يحصل على الصف الأول للخلية.<br/>            للقراءة فقط [`IRow`](/slides/python-net/ar/aspose.slides/irow). |
| [`first_column`](/slides/python-net/ar/aspose.slides/cell/first_column/) | يحصل على العمود الأول للخلية.<br/>            للقراءة فقط [`IColumn`](/slides/python-net/ar/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/ar/aspose.slides/cell/col_span/) | يرجع عدد أعمدة الشبكة في شبكة جدول الجدول الأب التي سيغطيها الخلية الحالية.<br/>            تسمح هذه الخاصية للخلية بأن تبدو كأنها مدمجة، حيث تمتد عبر حدود عمودية لخلايا أخرى في الجدول.<br/>            للقراءة فقط **int**. |
| [`row_span`](/slides/python-net/ar/aspose.slides/cell/row_span/) | يرجع عدد الصفوف التي تمتد عليها الخلية المدمجة.<br/>            يستخدم ذلك بالتزامن مع خاصية vMerge على خلايا أخرى لتحديد خلية البداية للدمج الأفقي.<br/>            للقراءة فقط **int**. |
| [`text_frame`](/slides/python-net/ar/aspose.slides/cell/text_frame/) | يرجع إطار النص للخلية.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ar/aspose.slides/cell/table/) | يرجع كائن Table الأب للخلية.<br/>            للقراءة فقط [`ITable`](/slides/python-net/ar/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ar/aspose.slides/cell/is_merged_cell/) | يرجع true إذا كانت الخلية مدمجة مع أي خلية معدلة، false خلاف ذلك.<br/>            للقراءة فقط **bool**. |
| [`cell_format`](/slides/python-net/ar/aspose.slides/cell/cell_format/) | يرجع كائن CellFormat الذي يحتوي على خصائص تنسيق لهذه الخلية.<br/>            للقراءة فقط [`ICellFormat`](/slides/python-net/ar/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ar/aspose.slides/cell/slide/) | يرجع الشريحة الأب للخلية.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/cell/presentation/) | يرجع العرض الأب للخلية.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ar/aspose.slides/cell/split_by_col_span/#int) | يقص الخلية إلى خليتين بحسب فهرس العمود. |
| [`split_by_row_span(self, index)`](/slides/python-net/ar/aspose.slides/cell/split_by_row_span/#int) | يقص الخلية إلى خليتين بحسب فهرس الصف. |
| [`split_by_height(self, height)`](/slides/python-net/ar/aspose.slides/cell/split_by_height/#float) | يقص الخلية بحسب الارتفاع. |
| [`split_by_width(self, width)`](/slides/python-net/ar/aspose.slides/cell/split_by_width/#float) | يقص الخلية بحسب العرض. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)