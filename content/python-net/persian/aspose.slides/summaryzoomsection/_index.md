---
title: SummaryZoomSection class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/summaryzoomsection/
---
## کلاس SummaryZoomSection

یک شیء Summary Zoom Section را در یک فریم Summary Zoom نمایش می‌دهد.

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/fa/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع SummaryZoomSection اعضای زیر را نمایش می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/summaryzoomsection/is_text_holder/) | مشخص می‌کند آیا شکل TextHolder_PPT است یا خیر.<br/>            فقط خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/summaryzoomsection/placeholder/) | جای‌گیرنده‌ای برای یک شکل را برمی‌گرداند. اگر شکل جای‌گیرنده‌ای نداشته باشد، None برمی‌گرداند.<br/>            فقط خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/summaryzoomsection/custom_data/) | دادهٔ سفارشی شکل را برمی‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/summaryzoomsection/raw_frame/) | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/summaryzoomsection/frame/) | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/summaryzoomsection/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند.<br/>            نکته: ممکن است برای برخی از انواع شکل‌ها که ویژگی خط ندارند، None برگرداند.<br/>            فقط خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/summaryzoomsection/three_d_format/) | شیء ThreeDFormat را که شامل ویژگی‌های اثر ۳بعدی برای یک شکل است برمی‌گرداند.<br/>            نکته: ممکن است برای برخی از انواع شکل‌ها که ویژگی ۳بعدی ندارند، None برگرداند.<br/>            فقط خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/summaryzoomsection/effect_format/) | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است برمی‌گرداند.<br/>            نکته: ممکن است برای برخی از انواع شکل‌ها که ویژگی افکت ندارند، None برگرداند.<br/>            فقط خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/summaryzoomsection/fill_format/) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند.<br/>            نکته: ممکن است برای برخی از انواع شکل‌ها که ویژگی پر کردن ندارند، None برگرداند.<br/>            فقط خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/summaryzoomsection/hyperlink_click/) | لینک‌هیپری که برای کلیک ماوس تعریف شده را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | لینک‌هیپری که برای عبور ماوس تعریف شده را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/summaryzoomsection/hyperlink_manager/) | مدیر لینک‌هیپری را برمی‌گرداند.<br/>            فقط خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/summaryzoomsection/hidden/) | مشخص می‌کند آیا شکل مخفی است یا خیر.<br/>            خواندنی/قابل نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/summaryzoomsection/z_order_position/) | موقعیت یک شکل در ترتیب z را برمی‌گرداند.<br/>            Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی پیشانی ترتیب z را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/summaryzoomsection/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/summaryzoomsection/rotation/) | تعداد درجاتی که شکل مشخص حول محور z چرخانده می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است.<br/>            خواندنی/قابل نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/summaryzoomsection/x/) | مختصات X گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/summaryzoomsection/y/) | مختصات Y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/summaryzoomsection/width/) | عرض شکل که بر حسب نقطه اندازه‌گیری می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/summaryzoomsection/height/) | ارتفاع شکل که بر حسب نقطه اندازه‌گیری می‌شود را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/summaryzoomsection/black_white_mode/) | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود..<br/>            خواندنی/قابل نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/summaryzoomsection/unique_id/) | شناسه داخلی با حوزهٔ ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به‌عنوان کلید یکتا پایدار در نظر گرفته شود.<br/>            فقط خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/summaryzoomsection/office_interop_shape_id/) | شناسهٔ یکتای محدودهٔ اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هر نقطه‌ای در سند می‌دهد.<br/>            فقط خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/summaryzoomsection/alternative_text/) | متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/summaryzoomsection/alternative_text_title/) | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/summaryzoomsection/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید.<br/>            خواندنی/قابل نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/summaryzoomsection/is_decorative/) | گزینهٔ 'Mark as decorative' را دریافت یا تنظیم می‌کند<br/>            خواندنی/قابل نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/summaryzoomsection/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/summaryzoomsection/is_grouped/) | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر.<br/>            فقط خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/summaryzoomsection/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/summaryzoomsection/slide/) | اسلاید والد شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/summaryzoomsection/presentation/) | ارائه (presentation) والد اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/summaryzoomsection/graphical_object_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fa/aspose.slides/summaryzoomsection/image_type/) | نوع تصویر شیء زوم را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`ZoomImageType`](/slides/python-net/fa/aspose.slides/zoomimagetype).<br/>            مقدار پیش‌فرض: Preview |
| [`return_to_parent`](/slides/python-net/fa/aspose.slides/summaryzoomsection/return_to_parent/) | رفتار ناوبری در نمایش اسلاید را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **bool**.<br/>            مقدار پیش‌فرض: false |
| [`show_background`](/slides/python-net/fa/aspose.slides/summaryzoomsection/show_background/) | مقداری که مشخص می‌کند آیا زوم از پس‌زمینهٔ اسلاید مقصد استفاده می‌کند را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **bool**.<br/>            مقدار پیش‌فرض: true |
| [`zoom_image`](/slides/python-net/fa/aspose.slides/summaryzoomsection/zoom_image/) | تصویر برای شیء زوم را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fa/aspose.slides/summaryzoomsection/transition_duration/) | مدت زمان انتقال بین زوم و اسلاید را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن **float**.<br/>            مقدار پیش‌فرض: 1.0f |
| [`target_section`](/slides/python-net/fa/aspose.slides/summaryzoomsection/target_section/) | شیء بخش که شیء Section Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل نوشتن [`ISection`](/slides/python-net/fa/aspose.slides/isection). |
| [`title`](/slides/python-net/fa/aspose.slides/summaryzoomsection/title/) | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [`description`](/slides/python-net/fa/aspose.slides/summaryzoomsection/description/) | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/get_image/#) | بند کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌عنوان پیش‌فرض برای محدودهٔ بند کوچک استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | بند کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/remove_placeholder/#) | تعریف می‌کند که این شکل جای‌گیرنده نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | اگر جای‌گیرنده‌ای وجود نداشته باشد، یک جای‌گیرنده جدید اضافه می‌کند و ویژگی‌های جای‌گیرنده را به مقدار مشخص تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/get_base_placeholder/#) | یک شکل جای‌گیرندهٔ پایه را برمی‌گرداند (شکل از لایه یا اسلاید اصلی که شکل جاری از آن به ارث می‌برد).<br/>            اگر شکل جاری به ارث نرفته باشد، None برمی‌گرداند. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/summaryzoomsection/get_visual_bounds/#) | حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه شده است دریافت می‌کند. |

### مراجع
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`SummaryZoomSection`](/slides/python-net/fa/aspose.slides/summaryzoomsection)
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)