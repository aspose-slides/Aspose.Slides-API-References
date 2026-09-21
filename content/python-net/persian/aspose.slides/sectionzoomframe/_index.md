---
title: SectionZoomFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/sectionzoomframe/
---
## کلاس SectionZoomFrame

نمایانگر یک شیء Section Zoom در یک اسلاید است.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع SectionZoomFrame اعضای زیر را فراهم می‌کند:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/sectionzoomframe/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/sectionzoomframe/placeholder/) | مکان‌دار (placeholder) را برای یک شکل برمی‌گرداند. اگر شکل مکان‌دار نداشته باشد، None برمی‌گرداند.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/sectionzoomframe/custom_data/) | داده سفارشی شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/sectionzoomframe/raw_frame/) | ویژگی‌های قاب شکل خام را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/sectionzoomframe/frame/) | ویژگی‌های قاب شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/sectionzoomframe/line_format/) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند، None برگرداند.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/sectionzoomframe/three_d_format/) | شیء ThreeDFormat را که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است، برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های 3d ندارند، None برگرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/sectionzoomframe/effect_format/) | شیء EffectFormat را که شامل افکت‌های پیکسل اعمال شده بر یک شکل است، برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های افکت ندارند، None برگرداند.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/sectionzoomframe/fill_format/) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پرکردن برای یک شکل است، برمی‌گرداند.<br/>            توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پرکردن ندارند، None برگرداند.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/sectionzoomframe/hyperlink_click/) | پیوند (hyperlink) تعریف‌شده برای کلیک موشواره را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | پیوند تعریف‌شده برای حرکت موشواره بر روی شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/sectionzoomframe/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/sectionzoomframe/hidden/) | تعیین می‌کند که آیا شکل مخفی است.<br/>            قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/sectionzoomframe/z_order_position/) | موقعیت یک شکل در z-order را برمی‌گرداند.<br/>            Shapes[0] شکل را در پشت z-order برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل را در جلوی z-order برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/sectionzoomframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/sectionzoomframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/sectionzoomframe/x/) | مختصات X گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/sectionzoomframe/y/) | مختصات Y گوشه بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/sectionzoomframe/width/) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/sectionzoomframe/height/) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/sectionzoomframe/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-و-سفید رندر می‌شود.<br/>            قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/sectionzoomframe/unique_id/) | شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند.<br/>            از آنجایی که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود.<br/>            فقط-خواندنی **int**.<br/>            همچنین به [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id) مراجعه کنید. |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/sectionzoomframe/office_interop_shape_id/) | شناسه یکتا scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را به‌طور قابل‌اعتماد از هرجای سند ارجاع دهند، برمی‌گرداند.<br/>            فقط-خواندنی **int**.<br/>            همچنین به [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id) مراجعه کنید. |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/sectionzoomframe/alternative_text/) | متن جایگزین (alternative text) مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/sectionzoomframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/sectionzoomframe/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز مقدار رشته خالی را استفاده کنید.<br/>            قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/sectionzoomframe/is_decorative/) | گزینه «علامت‌گذاری به‌عنوان تزئینی» را دریافت یا تنظیم می‌کند<br/>            قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/sectionzoomframe/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/sectionzoomframe/is_grouped/) | تعیین می‌کند که آیا شکل در یک گروه قرار دارد.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/sectionzoomframe/parent_group/) | شیء Parent GroupShape را اگر شکل در یک گروه باشد برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/sectionzoomframe/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/sectionzoomframe/presentation/) | ارائه والد یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/sectionzoomframe/graphical_object_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fa/aspose.slides/sectionzoomframe/image_type/) | نوع تصویر یک شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`ZoomImageType`](/slides/python-net/fa/aspose.slides/zoomimagetype).<br/>            مقدار پیش‌فرض: Preview |
| [`return_to_parent`](/slides/python-net/fa/aspose.slides/sectionzoomframe/return_to_parent/) | رفتار ناوبری در نمایش اسلاید را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **bool**.<br/>            مقدار پیش‌فرض: false |
| [`show_background`](/slides/python-net/fa/aspose.slides/sectionzoomframe/show_background/) | مقدار که تعیین می‌کند Zoom آیا از پس‌زمینه اسلاید مقصد استفاده کند یا نه را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **bool**.<br/>            مقدار پیش‌فرض: true |
| [`zoom_image`](/slides/python-net/fa/aspose.slides/sectionzoomframe/zoom_image/) | تصویر برای شیء Zoom را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fa/aspose.slides/sectionzoomframe/transition_duration/) | مدت زمان انتقال بین Zoom و اسلاید را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن **float**.<br/>            مقدار پیش‌فرض: 1.0f |
| [`target_section`](/slides/python-net/fa/aspose.slides/sectionzoomframe/target_section/) | شیء بخش (section) که شیء Section Zoom به آن پیوند می‌شود را دریافت یا تنظیم می‌کند.<br/>            قابل‌نوشتن [`ISection`](/slides/python-net/fa/aspose.slides/isection). |

## متدها

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/get_image/#) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/remove_placeholder/#) | تعریف می‌کند که این شکل مکان‌دار (placeholder) نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | اگر مکان‌دار وجود نداشته باشد، یک مکان‌دار جدید اضافه می‌کند و ویژگی‌های مکان‌دار را به مورد مشخص‌شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/get_base_placeholder/#) | یک شکل مکان‌دار پایه (شکل از لایه‌بندی و/یا اسلاید اصلی که شکل جاری از آن ارث می‌برد) را برمی‌گرداند.<br/>            اگر شکل جاری ارث‌برده نشده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/sectionzoomframe/get_visual_bounds/#) | حدود بصری شکل را که از محتوی رندر شده‌اش محاسبه می‌شود، برمی‌گرداند. |

### مشاهده نیز
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)