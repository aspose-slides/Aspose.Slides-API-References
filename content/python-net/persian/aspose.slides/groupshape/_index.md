---
title: GroupShape class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/groupshape/
---
## GroupShape کلاس

نمایانگر یک گروه از اشکال در یک اسلاید است.

**Inheritance:**[`GroupShape`](/slides/python-net/fa/aspose.slides/groupshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

The GroupShape type exposes the following members:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/groupshape/is_text_holder/) | تشخیص می‌دهد آیا شکل TextHolder_PPT است.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/groupshape/placeholder/) | Placeholder شکل را بر می‌گرداند. اگر شکل placeholder نداشته باشد، None بر می‌گرداند.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/groupshape/custom_data/) | داده‌های سفارشی شکل را بر می‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/groupshape/raw_frame/) | خواص فریم اولیه (raw) شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/groupshape/frame/) | خواص فریم شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/groupshape/line_format/) | شیء LineFormat که شامل خصوصیات قالب‌بندی خط برای یک شکل است را بر می‌گرداند.<br/>            نکته: برای اشیاء GroupShape، None بر می‌گردد زیرا آن‌ها خاصیت خط ندارند.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/groupshape/three_d_format/) | شیء ThreeDFormat که خصوصیات اثر 3D برای یک شکل را دارد را بر می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات 3D ندارند، None برگرداند.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/groupshape/effect_format/) | شیء EffectFormat که شامل اثرات پیکسل اعمال شده به یک شکل است را بر می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات اثر ندارند، None برگرداند.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/groupshape/fill_format/) | شیء FillFormat که شامل خصوصیات قالب‌بندی پرکننده برای یک شکل است را بر می‌گرداند.<br/>            نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات پرکننده ندارند، None برگرداند.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/groupshape/hyperlink_click/) | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/groupshape/hyperlink_mouse_over/) | پیوند تعریف‌شده برای حرکت ماوس بر روی (mouse over) را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/groupshape/hyperlink_manager/) | مدیر پیوندها را بر می‌گرداند.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/groupshape/hidden/) | تشخیص می‌دهد آیا شکل مخفی است.<br/>            خواندنی/نوشتنی **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/groupshape/z_order_position/) | موقعیت یک شکل در ترتیب z را بر می‌گرداند.<br/>            Shapes[0] شکل در انتهای پس‌زمینهٔ ترتیب z را بر می‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را بر می‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/groupshape/connection_site_count/) | تعداد نقاط اتصال روی شکل را بر می‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/groupshape/rotation/) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را بر می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است.<br/>            خواندنی/نوشتنی **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/groupshape/x/) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/groupshape/y/) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/groupshape/width/) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/groupshape/height/) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/groupshape/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود.<br/>            خواندنی/نوشتنی [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/groupshape/unique_id/) | یک شناسهٔ داخلی scoped به ارائه (presentation) که برای استفاده توسط افزودنی‌ها یا کدهای دیگر هدف دارد را بر می‌گرداند.<br/>            از آنجا که این مقدار ممکن است توسط کاربر یا برنامه‌نویسی تغییر یابد، نباید به‌عنوان کلید یکتا پایدار در نظر گرفته شود.<br/>            فقط-خواندنی **int**.<br/>            همچنین به [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id) مراجعه کنید. |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/groupshape/office_interop_shape_id/) | یک شناسهٔ یکتا scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع مطمئن به شکل از هرجای سند را می‌دهد، بر می‌گرداند.<br/>            فقط-خواندنی **int**.<br/>            همچنین به [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id) مراجعه کنید. |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/groupshape/alternative_text/) | متن جایگزین مرتبط با شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/groupshape/alternative_text_title/) | عنوان متن جایگزین مرتبط با شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/groupshape/name/) | نام شکل را بر می‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز از مقدار رشته خالی استفاده کنید.<br/>            خواندنی/نوشتنی **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/groupshape/is_decorative/) | گزینه 'Mark as decorative' را بر می‌گرداند یا تنظیم می‌کند<br/>            خواندنی/نوشتنی **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/groupshape/shape_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط-خواندنی [`IGroupShapeLock`](/slides/python-net/fa/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/groupshape/is_grouped/) | تشخیص می‌دهد آیا شکل گروه‌بندی شده است.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/groupshape/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را بر می‌گرداند. در غیر این صورت None بر می‌گرداند.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/groupshape/slide/) | اسلاید والد یک شکل را بر می‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/groupshape/presentation/) | ارائه (presentation) والد یک اسلاید را بر می‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/fa/aspose.slides/groupshape/group_shape_lock/) | قفل‌های شکل را بر می‌گرداند.<br/>            فقط-خواندنی [`IGroupShapeLock`](/slides/python-net/fa/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/fa/aspose.slides/groupshape/shapes/) | مجموعهٔ اشکال داخل گروه را بر می‌گرداند.<br/>            فقط-خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/groupshape/get_image/#) | تصویر بندانگشتی شکل را بر می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape برای محدودهٔ تصویر بندانگشتی شکل به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | تصویر بندانگشتی شکل را بر می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/groupshape/write_as_svg/#iorawiobase) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/groupshape/remove_placeholder/#) | تعریف می‌کند که این شکل placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/groupshape/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/groupshape/get_base_placeholder/#) | یک شکل placeholder پایه را بر می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند).<br/>            اگر شکل فعلی ارث‌بری نشده باشد، None برگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/groupshape/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، بر می‌گرداند. |

### موارد مرتبط
* کلاس [`GroupShape`](/slides/python-net/fa/aspose.slides/groupshape)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)