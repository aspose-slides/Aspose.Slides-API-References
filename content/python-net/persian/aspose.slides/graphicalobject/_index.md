---
title: GraphicalObject class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/graphicalobject/
---
## کلاس GraphicalObject

نشان‌دهندهٔ شیء گرافیکی انتزاعی است.

**ارث‌بری:**[`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع GraphicalObject اعضای زیر را باز می‌کند:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/graphicalobject/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/graphicalobject/placeholder/) | مکان‌دار یک شکل را باز می‌گرداند. اگر شکل مکان‌داری نداشته باشد، None باز می‌گردد.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/graphicalobject/custom_data/) | داده‌های سفارشی شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/graphicalobject/raw_frame/) | ویژگی‌های فریم خام شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/graphicalobject/frame/) | ویژگی‌های فریم شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/graphicalobject/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است، باز می‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/graphicalobject/three_d_format/) | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است، باز می‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/graphicalobject/effect_format/) | شیء EffectFormat را که شامل اثرهای پیکسلی اعمال‌شده به یک شکل است، باز می‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/graphicalobject/fill_format/) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است، باز می‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، None بازگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/graphicalobject/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده است را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/graphicalobject/hyperlink_mouse_over/) | پیوندی که برای عبور ماوس تعریف شده است را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/graphicalobject/hyperlink_manager/) | مدیر پیوندها را باز می‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/graphicalobject/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            خواندنی/نوشتنی **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/graphicalobject/z_order_position/) | موقعیت یک شکل در ترتیب-z را باز می‌گرداند.<br/>            Shapes[0] شکل را در انتهای ترتیب-z برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل را در ابتدای ترتیب-z برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/graphicalobject/connection_site_count/) | تعداد سایت‌های اتصال روی شکل را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/graphicalobject/rotation/) | تعداد درجاتی که شکل مشخص شده حول محور z چرخش دارد را باز می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است.<br/>            خواندنی/نوشتنی **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/graphicalobject/x/) | مختصات x گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/graphicalobject/y/) | مختصات y گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/graphicalobject/width/) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/graphicalobject/height/) | ارتفاع شکل را که بر همان پوینت اندازه‌گیری می‌شود، دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/graphicalobject/black_white_mode/) | ویژگی مشخص می‌کند که شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود.<br/>            خواندنی/نوشتنی [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/graphicalobject/unique_id/) | یک شناسه داخلی محدودهٔ ارائه را که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، باز می‌گرداند.<br/>            از آن‌جا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتا و پایدار در نظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/graphicalobject/office_interop_shape_id/) | یک شناسه یکتا محدود به اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای میان‌پروگرامی امکان ارجاع مطمئن به شکل را از هر نقطه‌ای در سند می‌دهد، باز می‌گرداند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/graphicalobject/alternative_text/) | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/graphicalobject/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/graphicalobject/name/) | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            خواندنی/نوشتنی **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/graphicalobject/is_decorative/) | دریافت یا تنظیم گزینهٔ «علامت‌گذاری به عنوان تزئینی»<br/>            خواندنی/نوشتنی **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/graphicalobject/shape_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/graphicalobject/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/graphicalobject/parent_group/) | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را باز می‌گرداند. در غیر این صورت None باز می‌گردد.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/graphicalobject/slide/) | اسلاید والد یک شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/graphicalobject/presentation/) | ارائهٔ والد یک اسلاید را باز می‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/graphicalobject/graphical_object_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/graphicalobject/get_image/#) | بند انگشتی (thumbnail) شکل را باز می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض برای مرزبندی بند انگشتی استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | بند انگشتی شکل را باز می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/graphicalobject/remove_placeholder/#) | مشخص می‌کند که این شکل مکان‌دار نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | اگر مکان‌داری وجود نداشته باشد، یک مکان‌دار جدید اضافه می‌کند و ویژگی‌های مکان‌دار را به مقداری مشخص تنظیم می‌سازد. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/graphicalobject/get_base_placeholder/#) | یک شکل مکان‌دار پایه را باز می‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی به ارث نرسیده باشد، None باز می‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/graphicalobject/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)