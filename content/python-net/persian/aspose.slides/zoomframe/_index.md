---
title: ZoomFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/zoomframe/
---
## کلاس ZoomFrame

نمایش یک شیء Slide Zoom در یک اسلاید.

**ارث‌بری:**[`ZoomFrame`](/slides/python-net/fa/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع ZoomFrame اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/zoomframe/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/zoomframe/placeholder/) | جای‌نگهدار یک شکل را بر می‌گرداند. اگر شکل جای‌نگهدار نداشته باشد None بر می‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/zoomframe/custom_data/) | داده‌های سفارشی شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/zoomframe/raw_frame/) | ویژگی‌های فریم خام شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/zoomframe/frame/) | ویژگی‌های فریم شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/zoomframe/line_format/) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را بر می‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/zoomframe/three_d_format/) | شیء ThreeDFormat که شامل ویژگی‌های اثر 3d برای یک شکل است را بر می‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3d ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/zoomframe/effect_format/) | شیء EffectFormat که شامل اثرات پیکسل اعمال‌شده به یک شکل است را بر می‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/zoomframe/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را بر می‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند می‌تواند None برگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/zoomframe/hyperlink_click/) | پیوند تعریف‌شده برای کلیک موشواره را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/zoomframe/hyperlink_mouse_over/) | پیوند تعریف‌شده برای حرکت موشواره بر روی آن را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/zoomframe/hyperlink_manager/) | مدیر پیوندها را بر می‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/zoomframe/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/zoomframe/z_order_position/) | موقعیت یک شکل در ترتیب z را بر می‌گرداند.<br/>            Shapes[0] شکل در پشت ترتیب z را بر می‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلو ترتیب z را بر می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/zoomframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را بر می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/zoomframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بر می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/zoomframe/x/) | مختصات x گوشهٔ بالا-چپ شکل را بر می‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری شده.<br/>            قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/zoomframe/y/) | مختصات y گوشهٔ بالا-چپ شکل را بر می‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری شده.<br/>            قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/zoomframe/width/) | عرض شکل را بر می‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری شده.<br/>            قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/zoomframe/height/) | ارتفاع شکل را بر می‌گرداند یا تنظیم می‌کند، به نقطه اندازه‌گیری شده.<br/>            قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/zoomframe/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود..<br/>            قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/zoomframe/unique_id/) | شناسه داخلی محدودهٔ ارائه را بر می‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به عنوان کلید یکتا پایدار رفتار شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/zoomframe/office_interop_shape_id/) | شناسه یکتا محدود به اسلاید را بر می‌گرداند که در طول عمر شکل ثابت می‌ماند و<br/>            به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هرجای سند به‌طور قابل‌اعتماد ارجاع دهند.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/zoomframe/alternative_text/) | متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/zoomframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/zoomframe/name/) | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/zoomframe/is_decorative/) | گزینهٔ 'Mark as decorative' را دریافت یا تنظیم می‌کند<br/>            قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/zoomframe/shape_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/zoomframe/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/zoomframe/parent_group/) | اگر شکل گروه‌بندی باشد، شیء GroupShape والد را بر می‌گرداند. در غیر این صورت None بر می‌گرداند.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/zoomframe/slide/) | اسلاید والد یک شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/zoomframe/presentation/) | ارائهٔ والد یک اسلاید را بر می‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/zoomframe/graphical_object_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fa/aspose.slides/zoomframe/image_type/) | نوع تصویر یک شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`ZoomImageType`](/slides/python-net/fa/aspose.slides/zoomimagetype).<br/>            مقدار پیش‌فرض: Preview |
| [`return_to_parent`](/slides/python-net/fa/aspose.slides/zoomframe/return_to_parent/) | رفتار ناوبری در نمایش اسلایدها را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **bool**.<br/>            مقدار پیش‌فرض: false |
| [`show_background`](/slides/python-net/fa/aspose.slides/zoomframe/show_background/) | مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده کند را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **bool**.<br/>            مقدار پیش‌فرض: true |
| [`zoom_image`](/slides/python-net/fa/aspose.slides/zoomframe/zoom_image/) | تصویر برای شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fa/aspose.slides/zoomframe/transition_duration/) | مدت زمان انتقال بین Zoom و اسلاید را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**.<br/>            مقدار پیش‌فرض: 1.0f |
| [`target_slide`](/slides/python-net/fa/aspose.slides/zoomframe/target_slide/) | شیء اسلایدی که شیء Slide Zoom به آن لینک می‌شود را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`ISlide`](/slides/python-net/fa/aspose.slides/islide). |

## متدها

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/zoomframe/get_image/#) | تصویر کوچک شکل را بر می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape برای محدوده تصویر کوچک شکل به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را بر می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/zoomframe/remove_placeholder/#) | تعریف می‌کند که این شکل جای‌نگهدار نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | اگر عدم وجود داشته باشد، جای‌نگهدار جدیدی اضافه می‌کند و ویژگی‌های جای‌نگهدار را به یکی مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/zoomframe/get_base_placeholder/#) | یک شکل جای‌نگهدار پایه را بر می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است).<br/>            اگر شکل فعلی به ارث نبرده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/zoomframe/get_visual_bounds/#) | محدوده‌های بصری شکل را که از محتوای رندر شده‌اش محاسبه شده‌اند، دریافت می‌کند. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`ZoomFrame`](/slides/python-net/fa/aspose.slides/zoomframe)
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)