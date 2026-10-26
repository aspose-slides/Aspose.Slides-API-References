---
title: ITextFrameFormat class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/itextframeformat/
---
## کلاس ITextFrameFormat

متناظر حاوی ویژگی‌های قالب‌بندی TextFrame است.

نوع ITextFrameFormat اعضای زیر را افشا می‌کند:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`text_style`](/slides/python-net/fa/aspose.slides/itextframeformat/text_style/) | استایل متن را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/fa/aspose.slides/itextframeformat/margin_left/) | حاشیه چپ (نقطه) را در TextFrame باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`margin_right`](/slides/python-net/fa/aspose.slides/itextframeformat/margin_right/) | حاشیه راست (نقطه) را در TextFrame باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`margin_top`](/slides/python-net/fa/aspose.slides/itextframeformat/margin_top/) | حاشیه بالا (نقطه) را در TextFrame باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`margin_bottom`](/slides/python-net/fa/aspose.slides/itextframeformat/margin_bottom/) | حاشیه پایین (نقطه) را در TextFrame باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`wrap_text`](/slides/python-net/fa/aspose.slides/itextframeformat/wrap_text/) | **True**  اگر متن در حاشیه‌های TextFrame بسته شود.<br/>            قابل خواندن و نوشتن [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/fa/aspose.slides/itextframeformat/anchoring_type/) | متن لنگر عمودی را در TextFrame باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`TextAnchorType`](/slides/python-net/fa/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/fa/aspose.slides/itextframeformat/center_text/) | اگر NullableBool.True باشد متن باید به صورت افقی در جعبه مرکز شود.<br/>            قابل خواندن و نوشتن [`NullableBool`](/slides/python-net/fa/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/fa/aspose.slides/itextframeformat/text_vertical_type/) | جهت‌گیری متن را تعیین می‌کند.<br/>            مقدار حاصل از چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle جمع‌آوری می‌شود.<br/>            قابل خواندن و نوشتن [`TextVerticalType`](/slides/python-net/fa/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/fa/aspose.slides/itextframeformat/autofit_type/) | حالت خودتنظیم متن را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`TextAutofitType`](/slides/python-net/fa/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/fa/aspose.slides/itextframeformat/column_count/) | تعداد ستون‌ها در ناحیه متن را باز می‌گرداند یا تنظیم می‌کند.<br/>            این مقدار باید عددی مثبت باشد. در غیر این صورت مقدار به صفر تنظیم می‌شود. <br/>            مقدار 0 به معنی مقدار تعریف‌نشده است.<br/>            قابل خواندن و نوشتن **int**. |
| [`column_spacing`](/slides/python-net/fa/aspose.slides/itextframeformat/column_spacing/) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را باز می‌گرداند یا تنظیم می‌کند. این تنها زمانی اعمال می‌شود <br/>            که بیش از یک ستون موجود باشد.<br/>            این مقدار باید عددی مثبت باشد. در غیر این صورت مقدار به صفر تنظیم می‌شود. <br/>            قابل خواندن و نوشتن **float**. |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/itextframeformat/three_d_format/) | شی ThreeDFormat را که ویژگی‌های اثر 3بعدی برای متن را نشان می‌دهد، باز می‌گرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/fa/aspose.slides/itextframeformat/keep_text_flat/) | نگه داشتن متن خارج از صحنه 3D را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **bool**. |
| [`rotation_angle`](/slides/python-net/fa/aspose.slides/itextframeformat/rotation_angle/) | چرخش سفارشی که بر روی متن داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به طور مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخش داشته باشد در کنار اینکه متن خودش نیز چرخش دارد.<br/>            مقدار حاصل از چرخش بصری متن که از این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType جمع‌آوری می‌شود.<br/>            قابل خواندن و نوشتن **float**. |
| [`transform`](/slides/python-net/fa/aspose.slides/itextframeformat/transform/) | قالب‌بندی پیچیده متن را دریافت یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`TextShapeType`](/slides/python-net/fa/aspose.slides/textshapetype). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fa/aspose.slides/itextframeformat/get_effective/#) | داده‌های قالب‌بندی مؤثر فریم متن را با اعمال وراثت دریافت می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)