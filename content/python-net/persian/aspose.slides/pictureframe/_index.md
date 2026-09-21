---
title: PictureFrame class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/pictureframe/
---
## کلاس PictureFrame

یک فریم حاوی یک تصویر را نشان می‌دهد.

**ارث‌بری:**[`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع PictureFrame اعضای زیر را افشا می‌کند:

## خصوصیات

| ویژگی | توضیحات |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/pictureframe/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/pictureframe/placeholder/) | مقدار جای‌نگهدارنده برای یک شکل را باز می‌گرداند. اگر شکل جای‌نگهدارنده‌ای نداشته باشد، None را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/pictureframe/custom_data/) | داده‌های سفارشی شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/pictureframe/raw_frame/) | ویژگی‌های خام چارچوب شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/pictureframe/frame/) | ویژگی‌های چارچوب شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/pictureframe/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است باز می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع اشکالی که ویژگی خط ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/pictureframe/three_d_format/) | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل را دارد باز می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع اشکالی که ویژگی 3D ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/pictureframe/effect_format/) | شیء EffectFormat که شامل اثرهای پیکسلی اعمال‌شده به یک شکل است باز می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع اشکالی که ویژگی اثر ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/pictureframe/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرشدگی برای یک شکل است باز می‌گرداند.<br/>            نکته: ممکن است برای برخی اشکالی که ویژگی پرشدگی ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/pictureframe/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده را باز می‌گرداند یا تنظیم می‌کند.<br/>            خوانדنی/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/pictureframe/hyperlink_mouse_over/) | پیوندی که برای عبور ماوس تعریف شده را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/pictureframe/hyperlink_manager/) | مدیر پیوندها را باز می‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/pictureframe/hidden/) | تعیین می‌کند که آیا شکل پنهان است.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/pictureframe/z_order_position/) | موقعیت یک شکل در ترتیب z را باز می‌گرداند.<br/>            Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/pictureframe/connection_site_count/) | تعداد نقاط اتصال بر روی شکل را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/pictureframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را باز می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/pictureframe/x/) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/pictureframe/y/) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/pictureframe/width/) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/pictureframe/height/) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/pictureframe/black_white_mode/) | ویژگی نحوهٔ رندر شدن شکل در حالت نمایش سیاه-سفید را مشخص می‌کند..<br/>            خواندنی/قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/pictureframe/unique_id/) | شناسهٔ داخلی scoped به ارائه که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده را باز می‌گرداند.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتا ثابت در نظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/pictureframe/office_interop_shape_id/) | شناسهٔ یکتا scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد تا شکل را به‌طور قابل‌اعتمادی از هرجای سند ارجاع دهد را باز می‌گرداند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/pictureframe/alternative_text/) | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/pictureframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/pictureframe/name/) | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/pictureframe/is_decorative/) | گزینهٔ 'علامت‌گذاری به عنوان تزئینی' را دریافت یا تنظیم می‌کند<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/pictureframe/shape_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/pictureframe/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/pictureframe/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را باز می‌گرداند. در غیر این صورت None را برمی‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/pictureframe/slide/) | اسلاید والد یک شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/pictureframe/presentation/) | ارائهٔ والد یک اسلاید را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides/pictureframe/shape_style/) | شیء سبک شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides/pictureframe/shape_type/) | نوع AutoShape برای یک PictureFrame را باز می‌گرداند یا تنظیم می‌کند.<br/>            تمام موارد قابل‌استفاده در مجموعهٔ [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) مجاز هستند، <br/>            مگر تمام انواع خطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            خواندنی/قابل‌نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides/pictureframe/adjustments/) | مجموعه‌ای از مقادیر تنظیم شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fa/aspose.slides/pictureframe/picture_frame_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFrameLock`](/slides/python-net/fa/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fa/aspose.slides/pictureframe/picture_format/) | شیء PictureFillFormat برای یک چارچوب تصویر را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fa/aspose.slides/pictureframe/relative_scale_height/) | مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) چارچوب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`relative_scale_width`](/slides/python-net/fa/aspose.slides/pictureframe/relative_scale_width/) | مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) چارچوب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 معادل 100٪ است.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`is_cameo`](/slides/python-net/fa/aspose.slides/pictureframe/is_cameo/) | تعیین می‌کند که آیا PictureFrame شیء Cameo است یا نه.<br/>            فقط‌خواندنی **bool**. |

## متدها

| متد | توضیحات |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/pictureframe/get_image/#) | تصویر کوچک‌نمایی شکل را باز می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض برای مرزهای تصویر کوچک‌نمایی استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک‌نمایی شکل را باز می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/pictureframe/remove_placeholder/#) | مشخص می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص‌شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/pictureframe/get_base_placeholder/#) | یک شکل placeholder پایه را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند).<br/>            اگر شکل فعلی ارث‌بری نشده باشد، None باز می‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/pictureframe/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، به‌دست می‌آورد. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides/pictureframe/get_geometry_paths/#) | کپی مسیر شکل هندسی را باز می‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | هندسه شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | هندسه شکل را از آرایه‌ای از [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند.<br/>             نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد. |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides/pictureframe/create_shape_elements/#) | آرایه‌ای از عناصر شکل را ایجاد و باز می‌گرداند. |

### همچنین ببینید
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)