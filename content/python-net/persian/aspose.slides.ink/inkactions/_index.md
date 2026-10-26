---
title: InkActions class
second_title: Aspose.Slides برای پایتون از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides.ink/inkactions/
---
## InkActions کلاس

نمایانگر ریشهٔ عملیات جوهر است.

**ارث‌بری:**[`InkActions`](/slides/python-net/fa/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع InkActions اعضای زیر را در دسترس قرار می‌دهد:

## خواص

| خصوصیت | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides.ink/inkactions/is_text_holder/) | تعیین می‌کند آیا شکل TextHolder_PPT است.<br/> فقط خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides.ink/inkactions/placeholder/) | محل‌نگهداری یک شکل را باز می‌گرداند. اگر شکل هیچ مکان‌نگهداری نداشته باشد None باز می‌گرداند.<br/> فقط خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides.ink/inkactions/custom_data/) | داده‌های سفارشی شکل را باز می‌گرداند.<br/> فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides.ink/inkactions/raw_frame/) | خواص قاب خام شکل را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides.ink/inkactions/frame/) | خواص قاب شکل را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides.ink/inkactions/line_format/) | شیء LineFormat را که شامل خواص قالب‌بندی خط برای یک شکل است باز می‌گرداند.<br/> توجه: ممکن است برای برخی انواع شکل‌ها که خواص خط ندارند None بازگرداند.<br/> فقط خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides.ink/inkactions/three_d_format/) | شیء ThreeDFormat را که شامل خواص اثر سه‌بعدی برای یک شکل است باز می‌گرداند.<br/> توجه: ممکن است برای برخی انواع شکل‌ها که خواص سه‌بعدی ندارند None بازگرداند.<br/> فقط خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides.ink/inkactions/effect_format/) | شیء EffectFormat را که شامل اثرات پیکسل اعمال‌شده به یک شکل است باز می‌گرداند.<br/> توجه: ممکن است برای برخی انواع شکل‌ها که خواص اثر ندارند None بازگرداند.<br/> فقط خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides.ink/inkactions/fill_format/) | شیء FillFormat را که شامل خواص قالب‌بندی پر کردن برای یک شکل است باز می‌گرداند.<br/> توجه: ممکن است برای برخی انواع شکل‌ها که خواص پر کردن ندارند None بازگرداند.<br/> فقط خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides.ink/inkactions/hyperlink_click/) | پیوند هیپرمتنی تعریف‌شده برای کلیک موس را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | پیوند هیپرمتنی تعریف‌شده برای عبور موس را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides.ink/inkactions/hyperlink_manager/) | مدیر پیوندهای هیپرمتنی را باز می‌گرداند.<br/> فقط خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides.ink/inkactions/hidden/) | تعیین می‌کند آیا شکل مخفی است.<br/> قابل خواندن و نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides.ink/inkactions/z_order_position/) | موقعیت یک شکل را در ترتیب z باز می‌گرداند.<br/> Shapes[0] شکل در پشت ترتیب z را باز می‌گرداند،<br/> و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را باز می‌گرداند.<br/> فقط خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides.ink/inkactions/connection_site_count/) | تعداد نقاط اتصال روی شکل را باز می‌گرداند.<br/> فقط خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides.ink/inkactions/rotation/) | تعداد درجاتی که شکل مشخص اطراف محور z چرخانده می‌شود را باز می‌گرداند یا تنظیم می‌کند.<br/> مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است.<br/> قابل خواندن و نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides.ink/inkactions/x/) | مختصات x گوشهٔ بالا-چپ شکل را که به پوینت اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.ink/inkactions/y/) | مختصات y گوشهٔ بالا-چپ شکل را که به پوینت اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.ink/inkactions/width/) | عرض شکل را که به پوینت اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.ink/inkactions/height/) | ارتفاع شکل را که به پوینت اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides.ink/inkactions/black_white_mode/) | خاصیتی که مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود.<br/> قابل خواندن و نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides.ink/inkactions/unique_id/) | یک شناسه داخلی scoped برای ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده، باز می‌گرداند.<br/> چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص یابد، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود.<br/> فقط خواندنی **int**.<br/> همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides.ink/inkactions/office_interop_shape_id/) | یک شناسه یکتا scoped برای اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هر نقطه‌ای در سند به‌طور قابل اعتماد ارجاع دهد، باز می‌گرداند.<br/> فقط خواندنی **int**.<br/> همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides.ink/inkactions/alternative_text/) | متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides.ink/inkactions/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/> قابل خواندن و نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides.ink/inkactions/name/) | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/> باید None نباشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید.<br/> قابل خواندن و نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides.ink/inkactions/is_decorative/) | گزینه 'Mark as decorative' را دریافت یا تنظیم می‌کند<br/> قابل خواندن و نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides.ink/inkactions/shape_lock/) | قفل‌های شکل را باز می‌گرداند.<br/> فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides.ink/inkactions/is_grouped/) | تعیین می‌کند آیا شکل گروه‌بندی شده است.<br/> فقط خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides.ink/inkactions/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را باز می‌گرداند. در غیر این صورت None باز می‌گرداند.<br/> فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides.ink/inkactions/slide/) | اسلاید والد یک شکل را باز می‌گرداند.<br/> فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides.ink/inkactions/presentation/) | ارائه والد یک اسلاید را باز می‌گرداند.<br/> فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides.ink/inkactions/graphical_object_lock/) | قفل‌های شکل را باز می‌گرداند.<br/> فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides.ink/inkactions/get_image/#) | بندانگشتی شکل را باز می‌گرداند.<br/> نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض برای محدودهٔ بندانگشتی شکل استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | بندانگشتی شکل را باز می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتویات Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides.ink/inkactions/remove_placeholder/#) | تعریف می‌کند که این شکل یک placeholder نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خواص placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides.ink/inkactions/get_base_placeholder/#) | یک شکل placeholder پایه را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند).<br/> اگر شکل فعلی ارث‌بری نشده باشد، None باز می‌گرداند. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides.ink/inkactions/get_visual_bounds/#) | حدود بصری شکل را که از محتوای رندر شده آن محاسبه شده است، دریافت می‌کند. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`InkActions`](/slides/python-net/fa/aspose.slides.ink/inkactions)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)