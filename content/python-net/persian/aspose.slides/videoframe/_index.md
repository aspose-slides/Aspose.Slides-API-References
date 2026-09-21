---
title: VideoFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/videoframe/
---
## کلاس VideoFrame

یک کلیپ ویدئویی را بر روی یک اسلاید نشان می‌دهد.

**ارث‌برداری:**[`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع VideoFrame اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/videoframe/is_text_holder/) | مشخص می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/videoframe/placeholder/) | مقدار جای‌گیر برای یک شکل را برمی‌گرداند. اگر شکل جای‌گیر نداشته باشد، None برمی‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/videoframe/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/videoframe/raw_frame/) | ویژگی‌های خام فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/videoframe/frame/) | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/videoframe/line_format/) | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، None برگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/videoframe/three_d_format/) | شیء ThreeDFormat را برمی‌گرداند که ویژگی‌های افکت 3-بعدی برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی 3-بعدی ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/videoframe/effect_format/) | شیء EffectFormat را برمی‌گرداند که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی افکت ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/videoframe/fill_format/) | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_click/) | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_mouse_over/) | پیوندهای تعریف‌شده برای حرکت ماوس بر روی را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/videoframe/hidden/) | مشخص می‌کند که آیا شکل مخفی است.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/videoframe/z_order_position/) | موقعیت یک شکل در ترتیب-z را برمی‌گرداند.<br/>            Shapes[0] شکلی را که در انتهای ترتیب-z قرار دارد برمی‌گرداند,<br/>            و Shapes[Shapes.Count - 1] شکلی را که در جلوی ترتیب-z قرار دارد برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/videoframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/videoframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/videoframe/x/) | مختصات x رأس بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/videoframe/y/) | مختصات y رأس بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/videoframe/width/) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/videoframe/height/) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/videoframe/black_white_mode/) | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود..<br/>            قابل‌خواندن/نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/videoframe/unique_id/) | شناسه داخلی scoped به ارائه که برای استفاده توسط افزودنی‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره تخصیص یابد، نباید به عنوان کلید منحصر به‌فرد ثابت درنظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/videoframe/office_interop_shape_id/) | شناسه یکتا scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اطمینان به شکل را از هر نقطه‌ای در سند می‌دهد را برمی‌گرداند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/videoframe/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/videoframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/videoframe/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز از مقدار رشته خالی استفاده کنید.<br/>            قابل‌خواندن/نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/videoframe/is_decorative/) | دریافت یا تنظیم گزینه 'Mark as decorative'.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/videoframe/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/videoframe/is_grouped/) | مشخص می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/videoframe/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/videoframe/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/videoframe/presentation/) | ارائه والد یک اسلاید را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/videoframe/shape_style/) | شیء سبک شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/videoframe/shape_type/) | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            تمام موارد قابل‌استفاده در مجموعه [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) وجود دارد، <br/>            به‌جز انواع خطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            قابل‌خواندن/نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/videoframe/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fa/aspose.slides/videoframe/picture_frame_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fa/aspose.slides/videoframe/picture_format/) | شیء PictureFillFormat برای یک فریم تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fa/aspose.slides/videoframe/relative_scale_height/) | مقیاس ارتفاع (نسبت به اندازه تصویر اصلی) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`relative_scale_width`](/slides/python-net/fa/aspose.slides/videoframe/relative_scale_width/) | مقیاس عرض (نسبت به اندازه تصویر اصلی) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است.<br/>            قابل‌خواندن/نوشتن **float**. |
| [`is_cameo`](/slides/python-net/fa/aspose.slides/videoframe/is_cameo/) | مشخص می‌کند که آیا PictureFrame یک شیء Cameo است یا نه.<br/>            فقط‌خواندنی **bool**. |
| [`rewind_video`](/slides/python-net/fa/aspose.slides/videoframe/rewind_video/) | مشخص می‌کند که آیا ویدئو به‌صورت خودکار به شروع باز می‌گردد<br/>            به محض پایان پخش فیلم.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`play_loop_mode`](/slides/python-net/fa/aspose.slides/videoframe/play_loop_mode/) | مشخص می‌کند که آیا ویدئو حلقه‌ای است.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`hide_at_showing`](/slides/python-net/fa/aspose.slides/videoframe/hide_at_showing/) | مشخص می‌کند که آیا VideoFrame مخفی است.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`volume`](/slides/python-net/fa/aspose.slides/videoframe/volume/) | حجم صدا را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`AudioVolumeMode`](/slides/python-net/fa/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/fa/aspose.slides/videoframe/play_mode/) | حالت پخش ویدئو را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`VideoPlayModePreset`](/slides/python-net/fa/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/fa/aspose.slides/videoframe/full_screen_mode/) | مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود.<br/>            قابل‌خواندن/نوشتن **bool**. |
| [`link_path_long`](/slides/python-net/fa/aspose.slides/videoframe/link_path_long/) | نام یک فایل ویدئویی که به VideoFrame لینک دارد را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن **str**. |
| [`embedded_video`](/slides/python-net/fa/aspose.slides/videoframe/embedded_video/) | شیء ویدئوی توکار را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن/نوشتن [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/fa/aspose.slides/videoframe/trim_from_start/) | شروع برش [ms] |
| [`trim_from_end`](/slides/python-net/fa/aspose.slides/videoframe/trim_from_end/) | پایان برش [ms] |
| [`caption_tracks`](/slides/python-net/fa/aspose.slides/videoframe/caption_tracks/) | مجموعه زیرنویس‌های بسته مرتبط با فریم ویدئو را دریافت می‌کند.<br/>             این ویژگی فقط‌خواندنی است و یک [`ICaptionsCollection`](/slides/python-net/fa/aspose.slides/icaptionscollection) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_image/#) | تصویر کوچک شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک شکل به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/videoframe/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/videoframe/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/videoframe/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی به ارث برده نشده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوا رندر شده محاسبه می‌شود، دریافت می‌کند. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_geometry_paths/#) | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشه بالا-چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | هندسه شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روز می‌کند. مختصات باید نسبت به گوشه بالا-چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | هندسه شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روز می‌کند. مختصات باید نسبت به گوشه بالا-چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/videoframe/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |

### موارد مرتبط
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)