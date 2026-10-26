---
title: Shape class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shape/
---
## کلاس Shape

نمایانگر یک شکل در اسلاید است.

نوع Shape اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/shape/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/shape/placeholder/) | مکان‌گیر برای یک شکل را برمی‌گرداند. اگر شکل مکان‌گیر نداشته باشد None برمی‌گرداند.<br/>            فقط خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/shape/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/shape/raw_frame/) | خواص خام قاب شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/shape/frame/) | خواص قاب شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/shape/line_format/) | شیء LineFormat را برمی‌گرداند که شامل خواص قالب‌بندی خط برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خواص خط ندارند، ممکن است None برگرداند.<br/>            فقط خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/shape/three_d_format/) | شیء ThreeDFormat را برمی‌گرداند که شامل خواص اثر سه‌بعدی برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خواص سه‌بعدی ندارند، ممکن است None برگرداند.<br/>            فقط خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/shape/effect_format/) | شیء EffectFormat را برمی‌گرداند که شامل اثرات پیکسل اعمال‌شده به یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خواص اثر ندارند، ممکن است None برگرداند.<br/>            فقط خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/shape/fill_format/) | شیء FillFormat را برمی‌گرداند که شامل خواص قالب‌بندی پر کردن برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خواص پر کردن ندارند، ممکن است None برگرداند.<br/>            فقط خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/shape/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/shape/hyperlink_mouse_over/) | پیوندی که برای حرکت ماوس (hover) تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/shape/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/shape/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            قابل خواندن و نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/shape/z_order_position/) | موقعیت یک شکل در ترتیب z را برمی‌گرداند.<br/>            Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/shape/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/shape/rotation/) | تعداد درجاتی که شکل مشخص شده حول محور z می‌چرخد را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل خواندن و نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/shape/x/) | مختصات x گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/shape/y/) | مختصات y گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/shape/width/) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/shape/height/) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/shape/black_white_mode/) | ویژگی مشخص می‌کند که چگونه یک شکل در حالت نمایش سیاه-سفید رندر می‌شود..<br/>            قابل خواندن و نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id/) | شناسه داخلی و محدود به ارائه (presentation) را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا سایر کدها در نظر گرفته شده است.<br/>            از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص داده شود، نباید به عنوان کلید یکتای ثابت درنظر گرفته شود.<br/>            فقط خواندنی **int**.<br/>            همچنین مراجعه کنید به [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id/) | شناسه یکتای محدود به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و<br/>            به PowerPoint یا کدهای بین‌عملیاتی اجازه می‌دهد به‌صورت قابل اعتماد شکل را از هر نقطه‌ای از سند ارجاع دهد.<br/>            فقط خواندنی **int**.<br/>            همچنین مراجعه کنید به [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/shape/alternative_text/) | متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/shape/alternative_text_title/) | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/shape/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز مقدار رشتهٔ خالی را استفاده کنید.<br/>            قابل خواندن و نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/shape/is_decorative/) | گزینه «علامت‌گذاری به عنوان تزئینی» را برمی‌گرداند یا تنظیم می‌کند<br/>            قابل خواندن و نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/shape/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IBaseShapeLock`](/slides/python-net/fa/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/shape/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/shape/parent_group/) | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/shape/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/shape/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |

## متدها

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/shape/get_image/#) | نماد کوچکی (thumbnail) از شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌عنوان مقدار پیش‌فرض برای محدودهٔ نمادهای کوچک استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | نماد کوچکی (thumbnail) از شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/shape/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/shape/remove_placeholder/#) | تعریف می‌کند که این شکل مکان‌گیر نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/shape/add_placeholder/#iplaceholder) | اگر مکان‌گیر وجود نداشته باشد، مکان‌گیر جدیدی اضافه می‌کند و خواص مکان‌گیر را به مورد مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/shape/get_base_placeholder/#) | یک شکل مکان‌گیر پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند).<br/>            اگر شکل فعلی ارث‌بری نشده باشد، None برمی‌گرداند. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/shape/get_visual_bounds/#) | محدودهٔ بصری شکل را که از محتوای رندرش محاسبه می‌شود، برمی‌گرداند. |

### مراجع
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)