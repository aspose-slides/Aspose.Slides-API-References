---
title: TextFrameFormat class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/textframeformat/
---
## TextFrameFormat کلاس

حاوی ویژگی‌های formatTextFrameFormatting فریم متن است.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/fa/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)

نوع TextFrameFormat اعضای زیر را نمایان می‌کند:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/textframeformat/__init__/#) | یک نمونه جدید از کلاس [`TextFrameFormat`](/slides/python-net/fa/aspose.slides/textframeformat) را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/textframeformat/three_d_format/) | شی ThreeDFormat را برمی‌گرداند که نشان‌دهنده ویژگی‌های اثر ۳بعدی برای متن است.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/fa/aspose.slides/textframeformat/margin_left/) | مارجین چپ (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_right`](/slides/python-net/fa/aspose.slides/textframeformat/margin_right/) | مارجین راست (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_top`](/slides/python-net/fa/aspose.slides/textframeformat/margin_top/) | مارجین بالا (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`margin_bottom`](/slides/python-net/fa/aspose.slides/textframeformat/margin_bottom/) | مارجین پایین (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`wrap_text`](/slides/python-net/fa/aspose.slides/textframeformat/wrap_text/) | **True** اگر متن در حاشیه‌های TextFrame بسته‌بندی شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/fa/aspose.slides/textframeformat/anchoring_type/) | متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`TextAnchorType`](/slides/python-net/fa/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/fa/aspose.slides/textframeformat/center_text/) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه وسط‌چین شود.<br/>            خواندنی/نوشتنی [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/fa/aspose.slides/textframeformat/text_vertical_type/) | جهت‌گیری متن را تعیین می‌کند.<br/>            مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به دست می‌آید.<br/>            خواندنی/نوشتنی [`TextVerticalType`](/slides/python-net/fa/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/fa/aspose.slides/textframeformat/autofit_type/) | حالت خودتنظیم متن را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`TextAutofitType`](/slides/python-net/fa/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/fa/aspose.slides/textframeformat/column_count/) | تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند.<br/>            این مقدار باید عددی مثبت باشد. در غیر این صورت مقدار به صفر تنظیم می‌شود. <br/>            مقدار ۰ به معنی مقدار تعریف‌نشده است.<br/>            خواندنی/نوشتنی **int**. |
| [`column_spacing`](/slides/python-net/fa/aspose.slides/textframeformat/column_spacing/) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را برمی‌گرداند یا تنظیم می‌کند. این فقط زمانی اعمال می‌شود <br/>            که بیش از یک ستون موجود باشد.<br/>            این مقدار باید عددی مثبت باشد. در غیر این صورت مقدار به صفر تنظیم می‌شود. <br/>            خواندنی/نوشتنی **float**. |
| [`rotation_angle`](/slides/python-net/fa/aspose.slides/textframeformat/rotation_angle/) | چرخش سفارشی که بر متن داخل جعبه محاط کننده اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به‌صورت مستقل از شکل اعمال می‌گردد. یعنی شکل می‌تواند چرخش خود را داشته باشد و متن نیز چرخش جداگانه‌ای داشته باشد.<br/>            مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType به دست می‌آید.<br/>            خواندنی/نوشتنی **float**. |
| [`transform`](/slides/python-net/fa/aspose.slides/textframeformat/transform/) | شکل بسته‌بندی متن را برمی‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`TextShapeType`](/slides/python-net/fa/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/fa/aspose.slides/textframeformat/keep_text_flat/) | حفظ متن به صورت صاف حتی در صورت اعمال اثر چرخش ۳-بعدی را برمی‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **bool**. |
| [`slide`](/slides/python-net/fa/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/fa/aspose.slides/textframeformat/text_style/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fa/aspose.slides/textframeformat/get_effective/#) | داده‌های قالب‌بندی مؤثر فریم متن را با درنظر گرفتن ارث‌بری برمی‌گرداند. |

### همچنین ببینید
* کلاس [`PVIObject`](/slides/python-net/fa/aspose.slides/pviobject)
* کلاس [`TextFrameFormat`](/slides/python-net/fa/aspose.slides/textframeformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)