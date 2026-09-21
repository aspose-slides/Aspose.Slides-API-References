---
title: Ink class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ink/ink/
---
## کلاس Ink

یک شیء جوهر را روی یک اسلاید نشان می‌دهد.

**وراثت:**[`Ink`](/slides/python-net/fa/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع Ink اعضای زیر را فراهم می‌کند:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides.ink/ink/is_text_holder/) | مشخص می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط‌قابل‌خواندن **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides.ink/ink/placeholder/) | مقدار جای‌گیر (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل جای‌گیر نداشته باشد، None را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides.ink/ink/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides.ink/ink/raw_frame/) | مشخصات فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides.ink/ink/frame/) | مشخصات فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides.ink/ink/line_format/) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند، می‌تواند None برگرداند.<br/>            فقط‌قابل‌خواندن [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides.ink/ink/three_d_format/) | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک شکل را دارد را برمی‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی 3D ندارند، می‌تواند None برگرداند.<br/>            فقط‌قابل‌خواندن [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides.ink/ink/effect_format/) | شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند، می‌تواند None برگرداند.<br/>            فقط‌قابل‌خواندن [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides.ink/ink/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکردن برای یک شکل است را برمی‌گرداند.<br/>            نکته: برای برخی انواع شکل‌ها که ویژگی پرکردن ندارند، می‌تواند None برگرداند.<br/>            فقط‌قابل‌خواندن [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides.ink/ink/hyperlink_click/) | پیوندی که برای کلیک موس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides.ink/ink/hyperlink_mouse_over/) | پیوندی که برای عبور موس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides.ink/ink/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides.ink/ink/hidden/) | مشخص می‌کند که آیا شکل مخفی است.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides.ink/ink/z_order_position/) | موقعیت یک شکل در ترتیب محور Z را برمی‌گرداند.<br/>            Shapes[0] شکلی را برمی‌گرداند که در پشت ترتیب Z قرار دارد،<br/>            و Shapes[Shapes.Count - 1] شکلی را برمی‌گرداند که در جلوی ترتیب Z است.<br/>            فقط‌قابل‌خواندن **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides.ink/ink/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides.ink/ink/rotation/) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور Z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides.ink/ink/x/) | مختصات X گوشهٔ بالایی-چپ شکل را به واحد نقطه (point) می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.ink/ink/y/) | مختصات Y گوشهٔ بالایی-چپ شکل را به واحد نقطه می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.ink/ink/width/) | عرض شکل را به واحد نقطه می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.ink/ink/height/) | ارتفاع شکل را به واحد نقطه می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides.ink/ink/black_white_mode/) | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه‌سفید رندر می‌شود..<br/>            خواندنی/قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides.ink/ink/unique_id/) | یک شناسه داخلی scoped به ارائه (presentation) را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی مجدداً اختصاص یابد، نباید به عنوان یک کلید یکتا و دائمی در نظر گرفته شود.<br/>            فقط‌قابل‌خواندن **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides.ink/ink/office_interop_shape_id/) | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و<br/>            به PowerPoint یا کدهای interop امکان ارجاع قابل‌اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد.<br/>            فقط‌قابل‌خواندن **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides.ink/ink/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides.ink/ink/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides.ink/ink/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            باید None نباشد. در صورت نیاز می‌توان مقدار رشتهٔ خالی استفاده کرد.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides.ink/ink/is_decorative/) | گزینهٔ 'Mark as decorative' را می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides.ink/ink/shape_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides.ink/ink/is_grouped/) | مشخص می‌کند که آیا شکل گروه‌بندی شده است.<br/>            فقط‌قابل‌خواندن **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides.ink/ink/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides.ink/ink/slide/) | اسلاید والد یک شکل را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides.ink/ink/presentation/) | ارائه (presentation) والد یک اسلاید را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides.ink/ink/graphical_object_lock/) | قفل‌های شکل را برمی‌گرداند.<br/>            فقط‌قابل‌خواندن [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/fa/aspose.slides.ink/ink/traces/) | تمام ردهای موجود در عنصر IInk [`IInkTrace`](/slides/python-net/fa/aspose.slides.ink/iinktrace) را می‌گیرد.<br/>            فقط‌قابل‌خواندن. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides.ink/ink/get_image/#) | تصویر کوچک (thumbnail) شکل را برمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک شکل به‌طور پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | تصویر کوچک شکل را برمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides.ink/ink/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides.ink/ink/get_base_placeholder/#) | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند) را برمی‌گرداند.<br/>            اگر شکل فعلی ارث‌بری نشده باشد، None برمی‌گردد. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides.ink/ink/get_visual_bounds/#) | مرزهای بصری شکل را که از محتوای رندرش محاسبه شده‌اند دریافت می‌کند. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/fa/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | یک تصویر را به مجموعهٔ تصاویر سفارشی استفاده‌شده برای شبیه‌سازی اثرات بصری برای قلم‌موهای جوهر ثبت می‌کند.<br/>            این تصاویر هنگام رندر جوهر با مقادیر خاص [`InkEffectType`](/slides/python-net/fa/aspose.slides.ink/inkeffecttype) استفاده می‌شوند،<br/>            مانند Galaxy، Rainbow و غیره. با ارائهٔ تصاویر خودتان، می‌توانید کنترل کنید که هر اثر جوهر چگونه ظاهر شود. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/fa/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | یک تصویر را از مجموعهٔ تصاویر سفارشی استفاده‌شده برای شبیه‌سازی اثرات بصری برای قلم‌موهای جوهر حذف می‌کند<br/>            تصاویر قبلاً ثبت‌شده از طریق **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Ink`](/slides/python-net/fa/aspose.slides.ink/ink)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)