---
title: GeometryShape class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/geometryshape/
---
## GeometryShape کلاس

نقش کلاس والد برای تمام اشکال هندسی را دارد.

**وراثت:**[`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع GeometryShape اعضای زیر را ارائه می‌دهد:

## خواص

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/geometryshape/is_text_holder/) | مشخص می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/geometryshape/placeholder/) | مقدار متغیر نگهدارنده برای یک شکل را برمی‌گرداند. اگر شکل هیچ نگهدارنده‌ای نداشته باشد، مقدار None را برمی‌گرداند.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/geometryshape/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/geometryshape/raw_frame/) | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/geometryshape/frame/) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/geometryshape/line_format/) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، مقدار None را برگرداند.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/geometryshape/three_d_format/) | شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند، مقدار None را برگرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/geometryshape/effect_format/) | شیء EffectFormat که شامل اثرات پیکسل اعمال شده به یک شکل است را برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند، مقدار None را برگرداند.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/geometryshape/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر شدن برای یک شکل است را برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر شدن ندارند، مقدار None را برگرداند.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/geometryshape/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/geometryshape/hyperlink_mouse_over/) | پیوندی که برای عبور ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/geometryshape/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/geometryshape/hidden/) | مشخص می‌کند که آیا شکل مخفی است.<br/>            قابل‌خواندن-قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/geometryshape/z_order_position/) | موقعیت یک شکل را در ترتیب z برمی‌ گرداند.<br/>            Shapes[0] شکلی را که در انتهای ترتیب z قرار دارد برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکلی را که در جلوی ترتیب z است برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/geometryshape/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/geometryshape/rotation/) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل‌خواندن-قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/geometryshape/x/) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/geometryshape/y/) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/geometryshape/width/) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/geometryshape/height/) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/geometryshape/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-وسفید رندر می‌شود..<br/>            قابل‌خواندن-قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/geometryshape/unique_id/) | شناسهٔ داخلی scoped به ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند.<br/>            از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص یابد، نباید به‌عنوان کلید یکتا و مداوم در نظر گرفته شود.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/geometryshape/office_interop_shape_id/) | شناسهٔ یکتای scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع مطمئن به شکل از هرجای سند را می‌دهد، را برمی‌گرداند.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/geometryshape/alternative_text/) | متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/geometryshape/alternative_text_title/) | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن-قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/geometryshape/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز می‌توانید از رشتهٔ خالی استفاده کنید.<br/>            قابل‌خواندن-قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/geometryshape/is_decorative/) | گزینهٔ «Mark as decorative» را دریافت یا تنظیم می‌کند<br/>            قابل‌خواندن-قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/geometryshape/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseShapeLock`](/slides/python-net/fa/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/geometryshape/is_grouped/) | مشخص می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/geometryshape/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت مقدار None را برمی‌گرداند.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/geometryshape/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/geometryshape/presentation/) | ارائهٔ والد یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/geometryshape/shape_style/) | شیء سبک شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type/) | نوع پیش‌تنظیم هندسه را برمی‌گرداند یا تنظیم می‌کند.<br/>            نکته: با تغییر مقدار، تمام مقادیر تنظیمات به مقادیر پیش‌فرض خود بازنشانی می‌شوند.<br/>            قابل‌خواندن-قابل‌نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/geometryshape/adjustments/) | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/geometryshape/get_image/#) | تصویر کوچک شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک شکل به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/geometryshape/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | در صورت عدم وجود، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/geometryshape/get_base_placeholder/#) | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند) را برمی‌گرداند.<br/>            اگر شکل فعلی ارث‌بری نشده باشد، مقدار None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/geometryshape/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/geometryshape/get_geometry_paths/#) | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | هندسهٔ شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌کند. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | هندسهٔ شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌کند. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/geometryshape/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |

### مراجع
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)