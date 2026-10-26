---
title: Connector class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/connector/
---
## کلاس Connector

نمایانگر یک اتصال است.

**وراثت:**[`Connector`](/slides/python-net/fa/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع Connector اعضای زیر را در دسترس قرار می‌دهد:

## خصوصیات

| خصوصیت | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/connector/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر.<br/>            فقط خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/connector/placeholder/) | مکان‌نگهدار شکل را برمی‌گرداند. اگر شکل مکان‌نگهداری نداشته باشد، None را برمی‌گرداند.<br/>            فقط خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/connector/custom_data/) | دیتای سفارشی شکل را برمی‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/connector/raw_frame/) | خواص فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/connector/frame/) | خواص فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/connector/line_format/) | شیء LineFormat که شامل خواص قالب‌بندی خط برای یک شکل است را برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که خواص خط ندارند، None برگرداند.<br/>            فقط خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/connector/three_d_format/) | شیء ThreeDFormat که شامل خواص اثر سه‌بعدی برای یک شکل است را برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که خواص سه‌بعدی ندارند، None برگرداند.<br/>            فقط خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/connector/effect_format/) | شیء EffectFormat که شامل افکت‌های پیکسلی اعمال‌شده بر یک شکل است را برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که خواص افکت ندارند، None برگرداند.<br/>            فقط خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/connector/fill_format/) | شیء FillFormat که شامل خواص قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که خواص پر کردن ندارند، None برگرداند.<br/>            فقط خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/connector/hyperlink_click/) | لینک ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/connector/hyperlink_mouse_over/) | لینک ابرمتنی تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/connector/hyperlink_manager/) | مدیر لینک‌های ابرمتنی را برمی‌گرداند.<br/>            فقط خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/connector/hidden/) | تعیین می‌کند که آیا شکل مخفی است یا خیر.<br/>            قابل خواندن/نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/connector/z_order_position/) | موقعیت یک شکل را در ترتیب z برمی‌گرداند.<br/>            Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/connector/connection_site_count/) | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/connector/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. یک مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل خواندن/نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/connector/x/) | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/connector/y/) | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/connector/width/) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/connector/height/) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/connector/black_white_mode/) | خصوصیت نحوه نمایش شکل در حالت سیاه‌ و سفید را مشخص می‌کند.<br/>            قابل خواندن/نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/connector/unique_id/) | یک شناسه داخلی با حوزهٔ ارائه (presentation) را که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است، برمی‌گرداند.<br/>            از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص داده شود، نباید به عنوان کلید منحصر به‌فرد پایدار در نظر گرفته شود.<br/>            فقط خواندنی **int**.<br/>            همچنین نگاه کنید به [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/connector/office_interop_shape_id/) | یک شناسه منحصر به‌فرد با حوزهٔ اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌صورت قابل اطمینان شکل را از هرجا در سند ارجاع دهند، برمی‌گرداند.<br/>            فقط خواندنی **int**.<br/>            همچنین نگاه کنید به [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/connector/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/connector/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/connector/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل خواندن/نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/connector/is_decorative/) | گزینهٔ 'علامت‌گذاری به‌عنوان تزئینی' را می‌گیرد یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/connector/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IConnectorLock`](/slides/python-net/fa/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/connector/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی‌شده است یا خیر.<br/>            فقط خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/connector/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند؛ در غیر اینصورت None برمی‌گرداند.<br/>            فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/connector/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/connector/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/connector/shape_style/) | شیء سبک (style) شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/connector/shape_type/) | نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/connector/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/fa/aspose.slides/connector/connector_lock/) | قفل‌های connector را برمی‌گرداند.<br/>            فقط خواندنی [`IConnectorLock`](/slides/python-net/fa/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/fa/aspose.slides/connector/start_shape_connected_to/) | شکلی را که انتهای آغازین connector به آن متصل می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/fa/aspose.slides/connector/end_shape_connected_to/) | شکلی را که انتهای انتهایی connector به آن متصل می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/fa/aspose.slides/connector/start_shape_connection_site_index/) | اندیس نقطه اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/fa/aspose.slides/connector/end_shape_connection_site_index/) | اندیس نقطه اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/connector/get_image/#) | تصویر بند انگشتی شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌عنوان پیش‌فرض برای مرزهای تصویر بند انگشتی استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/connector/write_as_svg/#iorawiobase) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/connector/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/connector/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خواص placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/connector/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند).<br/>            اگر شکل جاری ارث‌بری نشده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/connector/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، می‌گیرد. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/connector/get_geometry_paths/#) | یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالایی-چپ شکل است. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/connector/set_geometry_path/#igeometrypath) | شکل هندسی را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی-چپ شکل باشد.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | شکل هندسی را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی-چپ شکل باشد.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/connector/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [`reroute(self)`](/slides/python-net/fa/aspose.slides/connector/reroute/#) | connector را به‌گونه‌ای مسیر می‌دهد که کوتاه‌ترین مسیر ممکن بین شکل‌هایی که به آن‌ها متصل است را بگیرد. |

### مراجع
* کلاس [`Connector`](/slides/python-net/fa/aspose.slides/connector)
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)