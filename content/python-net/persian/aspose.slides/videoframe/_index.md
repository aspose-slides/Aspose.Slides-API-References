---
title: VideoFrame class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/videoframe/
---
## VideoFrame کلاس

یک کلیپ ویدئویی را بر روی اسلاید نشان می‌دهد.

**ارث‌بری:**[`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع VideoFrame اعضای زیر را در دسترس قرار می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/videoframe/is_text_holder/) | مشخص می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/videoframe/placeholder/) | placeholder برای یک شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد None برمی‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/videoframe/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/videoframe/raw_frame/) | خصوصیات فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/videoframe/frame/) | خصوصیات فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/videoframe/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند.<br/>            توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/videoframe/three_d_format/) | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است برمی‌گرداند.<br/>            توجه: برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/videoframe/effect_format/) | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده بر یک شکل است برمی‌گرداند.<br/>            توجه: برای برخی انواع شکل‌ها که ویژگی افکت ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/videoframe/fill_format/) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند.<br/>            توجه: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_click/) | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_mouse_over/) | پیوند (hyperlink) تعریف‌شده برای عبور ماوس را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/videoframe/hyperlink_manager/) | مدیر پیوند (hyperlink) را برمی‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/videoframe/hidden/) | مشخص می‌کند که آیا شکل پنهان است.<br/>            قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/videoframe/z_order_position/) | موقعیت یک شکل در ترتیب z را برمی‌گرداند.<br/>            Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/videoframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/videoframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است.<br/>            قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/videoframe/x/) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/videoframe/y/) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/videoframe/width/) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/videoframe/height/) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/videoframe/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-و-سفید رندر می‌شود..<br/>            قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/videoframe/unique_id/) | یک شناسه داخلی محدودهٔ ارائه (presentation) را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است برمی‌گرداند.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً تخصیص داده شود، نباید به‌عنوان یک کلید منحصربه‌فرد دائم رفتار شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/videoframe/office_interop_shape_id/) | یک شناسه منحصر به‌فرد محدودهٔ اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل‌اعتماد به شکل از هرجای سند را می‌دهد برمی‌گرداند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/videoframe/alternative_text/) | متن جایگزین مربوط به یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/videoframe/alternative_text_title/) | عنوان متن جایگزین مربوط به یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/videoframe/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/videoframe/is_decorative/) | گزینه 'علامت‌گذاری به‌عنوان تزئینی' را دریافت یا تنظیم می‌کند<br/>            قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/videoframe/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/videoframe/is_grouped/) | مشخص می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/videoframe/parent_group/) | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/videoframe/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/videoframe/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/videoframe/shape_style/) | شیء سبک (style) شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/videoframe/shape_type/) | نوع AutoShape برای یک PictureFrame را برمی‌گرداند یا تنظیم می‌کند.<br/>            همهٔ آیتم‌های قابل‌استفادهٔ مجموعهٔ [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) مجاز هستند، <br/>            به‌جز انواع خطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            قابل‌نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/videoframe/adjustments/) | یک مجموعه از مقادیر تنظیم شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fa/aspose.slides/videoframe/picture_frame_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fa/aspose.slides/videoframe/picture_format/) | شیء PictureFillFormat برای یک فریم تصویر را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fa/aspose.slides/videoframe/relative_scale_height/) | مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            قابل‌نوشتن **float**. |
| [`relative_scale_width`](/slides/python-net/fa/aspose.slides/videoframe/relative_scale_width/) | مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) فریم تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            قابل‌نوشتن **float**. |
| [`is_cameo`](/slides/python-net/fa/aspose.slides/videoframe/is_cameo/) | مشخص می‌کند که آیا PictureFrame یک شیء Cameo است یا خیر.<br/>            فقط‌خواندنی **bool**. |
| [`rewind_video`](/slides/python-net/fa/aspose.slides/videoframe/rewind_video/) | مشخص می‌کند که آیا ویدئو به‌صورت خودکار به شروع بازمی‌گردد<br/>            به‌محض اتمام پخش فیلم.<br/>            قابل‌نوشتن **bool**. |
| [`play_loop_mode`](/slides/python-net/fa/aspose.slides/videoframe/play_loop_mode/) | مشخص می‌کند که آیا ویدئو حلقه‌ای است.<br/>            قابل‌نوشتن **bool**. |
| [`hide_at_showing`](/slides/python-net/fa/aspose.slides/videoframe/hide_at_showing/) | مشخص می‌کند که آیا VideoFrame پنهان است.<br/>            قابل‌نوشتن **bool**. |
| [`volume`](/slides/python-net/fa/aspose.slides/videoframe/volume/) | حجم صدا را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`AudioVolumeMode`](/slides/python-net/fa/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/fa/aspose.slides/videoframe/volume_value/) | حجم دقیق ویدئو را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار به‌صورت درصدی از 0 تا 100 بیان می‌شود. از این ویژگی برای خواندن یا تنظیم مقادیر حجمی که دقیق‌تر از سطوح پیش‌تعریف‌شدهٔ موجود از طریق ویژگی [`VideoFrame.volume`](/slides/python-net/fa/aspose.slides/videoframe/volume) هستند، استفاده کنید.<br/>            قابل‌نوشتن **float**. |
| [`play_mode`](/slides/python-net/fa/aspose.slides/videoframe/play_mode/) | حالت پخش ویدئو را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`VideoPlayModePreset`](/slides/python-net/fa/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/fa/aspose.slides/videoframe/full_screen_mode/) | مشخص می‌کند که آیا ویدئو در حالت تمام‌صفحه نمایش داده می‌شود.<br/>            قابل‌نوشتن **bool**. |
| [`link_path_long`](/slides/python-net/fa/aspose.slides/videoframe/link_path_long/) | نام یک فایل ویدئویی که به VideoFrame لینک شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`embedded_video`](/slides/python-net/fa/aspose.slides/videoframe/embedded_video/) | شیء ویدئوی جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IVideo`](/slides/python-net/fa/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/fa/aspose.slides/videoframe/trim_from_start/) | زمان برش آغاز [ms] |
| [`trim_from_end`](/slides/python-net/fa/aspose.slides/videoframe/trim_from_end/) | زمان برش پایان [ms] |
| [`caption_tracks`](/slides/python-net/fa/aspose.slides/videoframe/caption_tracks/) | مجموعهٔ زیرنویس‌های بسته مرتبط با فریم ویدئو را برمی‌گرداند.<br/>            این ویژگی فقط‌خواندنی است و یک [`ICaptionsCollection`](/slides/python-net/fa/aspose.slides/icaptionscollection) شامل تمام مسیرهای زیرنویس را برمی‌گرداند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_image/#) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌عنوان پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/videoframe/write_as_svg/#iorawiobase) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/videoframe/remove_placeholder/#) | تعریف می‌کند که این شکل placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/videoframe/add_placeholder/#iplaceholder) | اگر placeholder موجود نیست، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخصی تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از لایه یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی وارث نباشد None برمی‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_visual_bounds/#) | مرزهای بصری شکل را که از محتویات رندرش محاسبه شده است، برمی‌گرداند. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/videoframe/get_geometry_paths/#) | یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | ژئومتری شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | ژئومتری شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند.<br/>            نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/videoframe/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |

### موارد مرتبط
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)