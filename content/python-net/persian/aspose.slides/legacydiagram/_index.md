---
title: LegacyDiagram class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/legacydiagram/
---
## LegacyDiagram کلاس

یک شیء نمودار قدیمی را نمایش می‌دهد.

**ارث‌بری:**[`LegacyDiagram`](/slides/python-net/fa/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع LegacyDiagram اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/legacydiagram/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/legacydiagram/placeholder/) | نگهدارنده برای یک شکل را برمی‌گرداند. اگر شکل هیچ نگهدارنده‌ای نداشته باشد، None را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/legacydiagram/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/legacydiagram/raw_frame/) | دریافت یا تنظیم ویژگی‌های فریم خام شکل.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/legacydiagram/frame/) | دریافت یا تنظیم ویژگی‌های فریم شکل.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/legacydiagram/line_format/) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند.<br/>            توجه: می‌تواند برای برخی نوع‌های شکل که ویژگی‌های خط ندارند، None را برگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/legacydiagram/three_d_format/) | شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند.<br/>            توجه: می‌تواند برای برخی نوع‌های شکل که ویژگی‌های سه‌بعدی ندارند، None را برگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/legacydiagram/effect_format/) | شیء EffectFormat که شامل اثرات پیکسلی اعمال شده بر یک شکل است را برمی‌گرداند.<br/>            توجه: می‌تواند برای برخی نوع‌های شکل که ویژگی‌های اثر ندارند، None را برگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/legacydiagram/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند.<br/>            توجه: می‌تواند برای برخی نوع‌های شکل که ویژگی‌های پر کردن ندارند، None را برگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/legacydiagram/hyperlink_click/) | دریافت یا تنظیم پیوند (hyperlink) تعریف شده برای کلیک ماوس.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/legacydiagram/hyperlink_mouse_over/) | دریافت یا تنظیم پیوند تعریف شده برای حرکت ماوس روی شی.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/legacydiagram/hyperlink_manager/) | مدیر پیوند را برمی‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/legacydiagram/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/legacydiagram/z_order_position/) | موقعیت یک شکل در ترتیب Z را برمی‌گرداند.<br/>            Shapes[0] شکل در پشت ترتیب Z را برمی‌گرداند,<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب Z را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/legacydiagram/connection_site_count/) | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/legacydiagram/rotation/) | دریافت یا تنظیم تعداد درجه‌هایی که شکل مشخص شده حول محور Z می‌چرخد.<br/>            مقدار مثبت نشان‌دهنده چرخش در جهت ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش در جهت ساعت‌پسگرد.<br/>            قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/legacydiagram/x/) | دریافت یا تنظیم مختصات X گوشه بالا-چپ شکل، بر حسب پوینت.<br/>            قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/legacydiagram/y/) | دریافت یا تنظیم مختصات Y گوشه بالا-چپ شکل، بر حسب پوینت.<br/>            قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/legacydiagram/width/) | دریافت یا تنظیم عرض شکل، بر حسب پوینت.<br/>            قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/legacydiagram/height/) | دریافت یا تنظیم ارتفاع شکل، بر حسب پوینت.<br/>            قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/legacydiagram/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود..<br/>            قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/legacydiagram/unique_id/) | شناسه داخلی با حوزه ارائه (presentation) را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی بازنویسی شود، نباید به عنوان کلید منحصر به‌فرد پایدار در نظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/legacydiagram/office_interop_shape_id/) | شناسه منحصر به‌فرد با حوزه اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و<br/>            به PowerPoint یا کدهای تعامل (interop) امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/legacydiagram/alternative_text/) | دریافت یا تنظیم متن جایگزین مرتبط با یک شکل.<br/>            قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/legacydiagram/alternative_text_title/) | دریافت یا تنظیم عنوان متن جایگزین مرتبط با یک شکل.<br/>            قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/legacydiagram/name/) | دریافت یا تنظیم نام یک شکل.<br/>            باید None نباشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/legacydiagram/is_decorative/) | دریافت یا تنظیم گزینه 'Mark as decorative'<br/>            قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/legacydiagram/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/legacydiagram/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/legacydiagram/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None را برمی‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/legacydiagram/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/legacydiagram/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/legacydiagram/graphical_object_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/get_image/#) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به صورت پیش‌فرض برای مرزهای تصویر کوچک استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | اگر placeholder موجود نباشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخصی تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی به ارث نبرده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندرده شده محاسبه می‌شود، دریافت می‌کند. |
| [`convert_to_smart_art(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/convert_to_smart_art/#) | نمودار قدیمی را به شیء SmartArt قابل ویرایش تبدیل می‌کند. <br/>            شیء SmartArt ایجاد شده به شکل گروه والد در همان موقعیت افزوده می‌شود. |
| [`convert_to_group_shape(self)`](/slides/python-net/fa/aspose.slides/legacydiagram/convert_to_group_shape/#) | نمودار قدیمی را به شکل گروه قابل ویرایش تبدیل می‌کند. <br/>            شیء GroupShape ایجاد شده به شکل گروه والد در همان موقعیت افزوده می‌شود. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`LegacyDiagram`](/slides/python-net/fa/aspose.slides/legacydiagram)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)