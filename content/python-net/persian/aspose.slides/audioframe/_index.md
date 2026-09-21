---
title: AudioFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/audioframe/
---
## AudioFrame کلاس

نمایش یک کلیپ صوتی بر روی یک اسلاید.

**Inheritance:**[`AudioFrame`](/slides/python-net/fa/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع AudioFrame اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/audioframe/is_text_holder/) | تشخیص می‌دهد که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/audioframe/placeholder/) | مقدار مکان‌گیر شکل را بر می‌گرداند. اگر شکل مکان‌گیر نداشته باشد None بر می‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/audioframe/custom_data/) | داده‌های سفارشی شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/audioframe/raw_frame/) | ویژگی‌های فریم خام شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/audioframe/frame/) | ویژگی‌های فریم شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/audioframe/line_format/) | شیء LineFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، None برگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/audioframe/three_d_format/) | شیء ThreeDFormat را بر می‌گرداند که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/audioframe/effect_format/) | شیء EffectFormat را بر می‌گرداند که شامل اثرات پیکسل اعمال‌شده به یک شکل است.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/audioframe/fill_format/) | شیء FillFormat را بر می‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، None برگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/audioframe/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده است را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/audioframe/hyperlink_mouse_over/) | پیوندی که برای عبور ماوس تعریف شده است را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/audioframe/hyperlink_manager/) | مدیر پیوندها را بر می‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/audioframe/hidden/) | تشخیص می‌دهد که آیا شکل مخفی است.<br/>            خواندنی/نوشتنی **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/audioframe/z_order_position/) | موقعیت یک شکل را در ترتیب z باز می‌گرداند.<br/>            Shapes[0] شکلی را که در انتهای ترتیب z قرار دارد برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکلی که در جلوی ترتیب z قرار دارد را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/audioframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را بر می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/audioframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بر می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            خواندنی/نوشتنی **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/audioframe/x/) | مختصات x گوشه بالایی-چپ شکل را که به نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/audioframe/y/) | مختصات y گوشه بالایی-چپ شکل را که به نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/audioframe/width/) | عرض شکل را که به نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/audioframe/height/) | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/audioframe/black_white_mode/) | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود.<br/>            خواندنی/نوشتنی [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/audioframe/unique_id/) | یک شناسه داخلی scoped به ارائه را که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است بر می‌گرداند.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان یک کلید یکتا پایدار در نظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/audioframe/office_interop_shape_id/) | یک شناسه یکتا scoped به اسلاید را که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل‌اعتماد به شکل از هر جایی در سند را می‌دهد، بر می‌گرداند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/audioframe/alternative_text/) | متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/audioframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/audioframe/name/) | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز از مقدار رشته خالی استفاده کنید.<br/>            خواندنی/نوشتنی **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/audioframe/is_decorative/) | دریافت یا تنظیم گزینه 'علامت‌گذاری به‌عنوان تزئینی'<br/>            خواندنی/نوشتنی **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/audioframe/shape_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/audioframe/is_grouped/) | تشخیص می‌دهد که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/audioframe/parent_group/) | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را بر می‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/audioframe/slide/) | اسلاید والد یک شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/audioframe/presentation/) | ارائه والد اسلاید را بر می‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/audioframe/shape_style/) | شیء سبک شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/audioframe/shape_type/) | نوع AutoShape برای یک PictureFrame را بر می‌گرداند یا تنظیم می‌کند.<br/>            تمام آیتم‌های قابل‌استفاده مجموعه [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) موجود هستند، <br/>            به استثنای انواع خطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            خواندنی/نوشتنی [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/audioframe/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fa/aspose.slides/audioframe/picture_frame_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fa/aspose.slides/audioframe/picture_format/) | شیء PictureFillFormat برای یک قاب تصویر (picture frame) را بر می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fa/aspose.slides/audioframe/relative_scale_height/) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را بر می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            خواندنی/نوشتنی **float**. |
| [`relative_scale_width`](/slides/python-net/fa/aspose.slides/audioframe/relative_scale_width/) | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را بر می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            خواندنی/نوشتنی **float**. |
| [`is_cameo`](/slides/python-net/fa/aspose.slides/audioframe/is_cameo/) | تشخیص می‌دهد که آیا PictureFrame شیء Cameo است یا نه.<br/>            فقط‌خواندنی **bool**. |
| [`audio_cd_start_track`](/slides/python-net/fa/aspose.slides/audioframe/audio_cd_start_track/) | شاخص مسیر شروع را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/fa/aspose.slides/audioframe/audio_cd_start_track_time/) | زمان شروع مسیر را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`audio_cd_end_track`](/slides/python-net/fa/aspose.slides/audioframe/audio_cd_end_track/) | شاخص مسیر انتهایی را بر می‌گرداند یا تنظیم می‌کند<br/>            خواندنی/نوشتنی **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/fa/aspose.slides/audioframe/audio_cd_end_track_time/) | زمان مسیر انتهایی را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **int**. |
| [`volume`](/slides/python-net/fa/aspose.slides/audioframe/volume/) | حجم صدا را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`AudioVolumeMode`](/slides/python-net/fa/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/fa/aspose.slides/audioframe/play_mode/) | حالت پخش صدا را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`AudioPlayModePreset`](/slides/python-net/fa/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/fa/aspose.slides/audioframe/hide_at_showing/) | تشخیص می‌دهد که آیا AudioFrame مخفی است.<br/>            خواندنی/نوشتنی **bool**. |
| [`play_loop_mode`](/slides/python-net/fa/aspose.slides/audioframe/play_loop_mode/) | تشخیص می‌دهد که آیا صدا حلقه‌ای است.<br/>            خواندنی/نوشتنی **bool**. |
| [`play_across_slides`](/slides/python-net/fa/aspose.slides/audioframe/play_across_slides/) | تشخیص می‌دهد که آیا صدا در تمام اسلایدها پخش می‌شود.<br/>            خواندنی/نوشتنی **bool**. |
| [`rewind_audio`](/slides/python-net/fa/aspose.slides/audioframe/rewind_audio/) | تشخیص می‌دهد که آیا صدا پس از پخش به‌طور خودکار به ابتدا باز می‌گردد.<br/>            خواندنی/نوشتنی **bool**. |
| [`embedded`](/slides/python-net/fa/aspose.slides/audioframe/embedded/) | تشخیص می‌دهد که آیا صدا به ارائه جاسازی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`link_path_long`](/slides/python-net/fa/aspose.slides/audioframe/link_path_long/) | نام فایل صوتی که به AudioFrame لینک شده است را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`embedded_audio`](/slides/python-net/fa/aspose.slides/audioframe/embedded_audio/) | شیء صوتی جاسازی‌شده را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/fa/aspose.slides/audioframe/fade_in_duration/) | مدت زمان محو شدن اولیه (fade-in) رسانه را بر حسب میلی‌ثانیه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`fade_out_duration`](/slides/python-net/fa/aspose.slides/audioframe/fade_out_duration/) | مدت زمان محو شدن پایان (fade-out) رسانه را بر حسب میلی‌ثانیه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`volume_value`](/slides/python-net/fa/aspose.slides/audioframe/volume_value/) | حجم صدا را به درصد بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`trim_from_start`](/slides/python-net/fa/aspose.slides/audioframe/trim_from_start/) | مدت زمانی که در هنگام پخش از ابتدای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`trim_from_end`](/slides/python-net/fa/aspose.slides/audioframe/trim_from_end/) | مدت زمانی که در هنگام پخش از انتهای رسانه حذف می‌شود را بر حسب میلی‌ثانیه مشخص می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`caption_tracks`](/slides/python-net/fa/aspose.slides/audioframe/caption_tracks/) | مجموعه زیرنویس‌های بسته مرتبط با فریم صدا را بر می‌گرداند.<br/>            این ویژگی فقط‌خواندنی است و یک [`ICaptionsCollection`](/slides/python-net/fa/aspose.slides/icaptionscollection) شامل تمام مسیرهای زیرنویس برمی‌گرداند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/audioframe/get_image/#) | تصویر کوچک (thumbnail) شکل را بر می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌عنوان پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را بر می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/audioframe/write_as_svg/#iorawiobase) | محتوأ Shape را به صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوأ Shape را به صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/audioframe/remove_placeholder/#) | تعریف می‌کند که این شکل مکان‌گیر نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/audioframe/add_placeholder/#iplaceholder) | اگر مکان‌گیر موجود نباشد، یک مکان‌گیر جدید اضافه می‌کند و ویژگی‌های مکان‌گیر را به مقدار مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/audioframe/get_base_placeholder/#) | یک شکل مکان‌گیر پایه را بر می‌گرداند (شکلی که از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث می‌برد).<br/>            اگر شکل جاری ارث‌برده نباشد، None برمی‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/audioframe/get_visual_bounds/#) | حدود بصری شکل را که از محتویات رندر شده محاسبه می‌شود، بر می‌گرداند. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/audioframe/get_geometry_paths/#) | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشه‌بالایی چپ شکل است. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | هندسه شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه‌بالایی چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشه‌بالایی چپ شکل باشد.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/audioframe/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |

### همچنین ببینید
* کلاس [`AudioFrame`](/slides/python-net/fa/aspose.slides/audioframe)
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)