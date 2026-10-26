---
title: AutoShape class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/autoshape/
---
## کلاس AutoShape

یک AutoShape را نشان می‌دهد.

**وارثی:**[`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع AutoShape اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/autoshape/is_text_holder/) | مشخص می‌کند که شکل TextHolder_PPT است یا خیر.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/autoshape/placeholder/) | مقدار جای‌دار (placeholder) یک شکل را برمی‌گرداند. اگر شکل جای‌داری نداشته باشد None برمی‌گرداند.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/autoshape/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/autoshape/raw_frame/) | خواص خام فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/autoshape/frame/) | خواص فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/autoshape/line_format/) | شیئ LineFormat را برمی‌گرداند که شامل خصوصیات قالب‌بندی خط برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خصوصیات خط ندارند می‌تواند None برگرداند.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/autoshape/three_d_format/) | شیئ ThreeDFormat را برمی‌گرداند که شامل خصوصیات اثر ۳بعدی برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خصوصیات ۳بعدی ندارند می‌تواند None برگرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/autoshape/effect_format/) | شیئ EffectFormat را برمی‌گرداند که شامل اثرات پیکسلی اعمال‌شده به یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خصوصیات اثر ندارند می‌تواند None برگرداند.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/autoshape/fill_format/) | شیئ FillFormat را برمی‌گرداند که شامل خصوصیات قالب‌بندی پر کردن برای یک شکل است.<br/>            نکته: برای برخی انواع شکل‌ها که خصوصیات پر کردن ندارند می‌تواند None برگرداند.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/autoshape/hyperlink_click/) | پی‌وند (hyperlink) تعریف شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/autoshape/hyperlink_mouse_over/) | پی‌وند تعریف شده برای حرکت موس بر روی آن را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/autoshape/hyperlink_manager/) | مدیر پی‌وند را برمی‌گرداند.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/autoshape/hidden/) | مشخص می‌کند که شکل مخفی است یا نه.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/autoshape/z_order_position/) | موقعیت یک شکل در ترتیب z را برمی‌گرداند.<br/>            Shapes[0] شکلی را که در پشت ترتیب z است برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکلی را که در جلو ترتیب z است برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/autoshape/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/autoshape/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/autoshape/x/) | مختصات x گوشهٔ بالا-چپ شکل را برحسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/autoshape/y/) | مختصات y گوشهٔ بالا-چپ شکل را برحسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/autoshape/width/) | عرض شکل را برحسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/autoshape/height/) | ارتفاع شکل را برحسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/autoshape/black_white_mode/) | خاصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود..<br/>            قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/autoshape/unique_id/) | یک شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر مقصود است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به‌عنوان کلید یکتا پایدار در نظر گرفته شود.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/autoshape/office_interop_shape_id/) | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل‌اعتماد به شکل را از هرجای سند می‌دهد.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/autoshape/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/autoshape/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/autoshape/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/autoshape/is_decorative/) | 'Mark as decorative' گزینه را می‌گیرد یا تنظیم می‌کند<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/autoshape/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IAutoShapeLock`](/slides/python-net/fa/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/autoshape/is_grouped/) | مشخص می‌کند که شکل گروه‌بندی شده است یا نه.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/autoshape/parent_group/) | اگر شکل گروه‌بندی شده باشد شیئ GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/autoshape/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/autoshape/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/autoshape/shape_style/) | شیئ style شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/autoshape/shape_type/) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند.<br/>            نکته: با تغییر مقدار، تمام مقادیر تنظیم مجدداً به مقادیر پیش‌فرض بازمی‌گردند.<br/>            قابل‌خواندن/قابل‌نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/autoshape/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/fa/aspose.slides/autoshape/auto_shape_lock/) | قفل‌های autoshape را برمی‌گرداند.<br/>            فقط-خواندنی [`IAutoShapeLock`](/slides/python-net/fa/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/fa/aspose.slides/autoshape/text_frame/) | شیئ TextFrame برای AutoShape را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/fa/aspose.slides/autoshape/use_background_fill/) | مشخص می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به جای اینکه توسط style یا fill format مشخص شود.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`is_text_box`](/slides/python-net/fa/aspose.slides/autoshape/is_text_box/) | مشخص می‌کند آیا شکل یک جعبهٔ متن است یا نه. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/autoshape/get_image/#) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض برای مرزهای تصویر کوچک استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/autoshape/write_as_svg/#iorawiobase) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/autoshape/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/autoshape/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/autoshape/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی به ارث نرسیده باشد، None برمی‌گرداند. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/autoshape/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، برمی‌گیرد. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/autoshape/get_geometry_paths/#) | یک نسخهٔ کپی از مسیر (path) شکل هندسی را برمی‌گرداند. مختصات‌ها نسبی به گوشهٔ بالای چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | هندسهٔ شکل را از شیئ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبی به گوشهٔ بالای چپ شکل باشند.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | هندسهٔ شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات‌ها باید نسبی به گوشهٔ بالای چپ شکل باشند.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/autoshape/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| [`add_text_frame(self, text)`](/slides/python-net/fa/aspose.slides/autoshape/add_text_frame/#str) | یک TextFrame جدید به شکل اضافه می‌کند.<br/>            اگر شکل قبلاً TextFrame داشته باشد، به‌سادگی متن آن را تغییر می‌دهد. |

### موارد مرتبط
* کلاس [`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape)
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)