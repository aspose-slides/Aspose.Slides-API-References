---
title: ZoomObject class
second_title: مرجع API .NET برای Aspose.Slides در Python
description: 
type: docs
url: /fa/aspose.slides/zoomobject/
---
## کلاس ZoomObject

یک شی Zoom را در یک اسلاید نشان می‌دهد.

**ارث‌بری:**[`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع ZoomObject اعضای زیر را افشا می‌کند:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/zoomobject/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/zoomobject/placeholder/) | مکان‌دار یک شکل را برمی‌گرداند. اگر شکل مکان‌دار نداشته باشد، None برمی‌گرداند.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/zoomobject/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/zoomobject/raw_frame/) | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/zoomobject/frame/) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/zoomobject/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند، None برگرداند.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/zoomobject/three_d_format/) | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است، برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی سه‌بعدی ندارند، None برگرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/zoomobject/effect_format/) | شیء EffectFormat را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است، برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی افکت ندارند، None برگرداند.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/zoomobject/fill_format/) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است، برمی‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی پر ندارند، None برگرداند.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/zoomobject/hyperlink_click/) | پیوندهای تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/zoomobject/hyperlink_mouse_over/) | پیوند تعریف‌شده برای گذر موس را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/zoomobject/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/zoomobject/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            خواندن/نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/zoomobject/z_order_position/) | موقعیت یک شکل را در ترتیب Z برمی‌گرداند.<br/>            Shapes[0] شکل در انتهای ترتیب Z را برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوتر از ترتیب Z را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/zoomobject/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/zoomobject/rotation/) | تعداد درجه‌های چرخش شکل مشخص شده حول محور Z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است.<br/>            خواندن/نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/zoomobject/x/) | مختصات X گوشه بالایی-چپ شکل را بر حسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/zoomobject/y/) | مختصات Y گوشه بالایی-چپ شکل را بر حسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/zoomobject/width/) | عرض شکل را بر حسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/zoomobject/height/) | ارتفاع شکل را بر حسب پوینت برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/zoomobject/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود..<br/>            خواندن/نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/zoomobject/unique_id/) | یک شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی تغییر یابد، نباید به‌عنوان یک کلید یکتا دائمی در نظر گرفته شود.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/zoomobject/office_interop_shape_id/) | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و<br/>            به PowerPoint یا کدهای interop اجازه می‌دهد به‌صورت قابل اعتماد شکل را از هرجای سند ارجاع دهند.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/zoomobject/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/zoomobject/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/zoomobject/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید.<br/>            خواندن/نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/zoomobject/is_decorative/) | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند<br/>            خواندن/نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/zoomobject/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/zoomobject/is_grouped/) | تعیین می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/zoomobject/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر اینصورت None برمی‌گرداند.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/zoomobject/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/zoomobject/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/zoomobject/graphical_object_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fa/aspose.slides/zoomobject/image_type/) | نوع تصویر شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`ZoomImageType`](/slides/python-net/fa/aspose.slides/zoomimagetype).<br/>            مقدار پیش‌فرض: Preview |
| [`return_to_parent`](/slides/python-net/fa/aspose.slides/zoomobject/return_to_parent/) | رفتار ناوبری در نمایش اسلاید را دریافت یا تنظیم می‌کند.<br/>            خواندن/نوشتن **bool**.<br/>            مقدار پیش‌فرض: false |
| [`show_background`](/slides/python-net/fa/aspose.slides/zoomobject/show_background/) | مقداری را دریافت یا تنظیم می‌کند که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده کند یا نه.<br/>            خواندن/نوشتن **bool**.<br/>            مقدار پیش‌فرض: true |
| [`zoom_image`](/slides/python-net/fa/aspose.slides/zoomobject/zoom_image/) | تصویر برای شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            خواندن/نوشتن [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fa/aspose.slides/zoomobject/transition_duration/) | مدت زمان انتقال بین Zoom و اسلاید را دریافت یا تنظیم می‌کند.<br/>            خواندن/نوشتن **float**.<br/>            مقدار پیش‌فرض: 1.0f |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/zoomobject/get_image/#) | تصویر بند انگشتی شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/zoomobject/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/zoomobject/get_base_placeholder/#) | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده شده است).<br/>            اگر شکل جاری ارث‌بری نداشته باشد، None برمی‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/zoomobject/get_visual_bounds/#) | محدوده بصری شکل را بر اساس محتویات رندر شده آن به‌دست می‌آورد. |

### مراجع دیگر
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)