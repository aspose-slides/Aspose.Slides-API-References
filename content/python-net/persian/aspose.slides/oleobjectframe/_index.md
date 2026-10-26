---
title: OleObjectFrame class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/oleobjectframe/
---
## OleObjectFrame کلاس

نمایانگر یک شیء OLE در یک اسلاید است.

**ارث‌بری:**[`OleObjectFrame`](/slides/python-net/fa/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع OleObjectFrame اعضای زیر را در دسترس قرار می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/oleobjectframe/is_text_holder/) | تشخیص می‌دهد که آیا شکل TextHolder_PPT است.<br/>            فقط‌خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/oleobjectframe/placeholder/) | نگهدارنده‌ی یک شکل را برمی‌گرداند. اگر شکل نگهدارنده نداشته باشد، None باز می‌گرداند.<br/>            فقط‌خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/oleobjectframe/custom_data/) | داده‌های سفارشی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/oleobjectframe/raw_frame/) | ویژگی‌های فریم خام شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/oleobjectframe/frame/) | ویژگی‌های فریم شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/oleobjectframe/line_format/) | شیء LineFormat که حاوی ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند.<br/>            توجه: برای برخی از انواع شکل‌ها که ویژگی خط ندارند می‌تواند None بازگرداند.<br/>            فقط‌خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/oleobjectframe/three_d_format/) | شیء ThreeDFormat که شامل ویژگی‌های اثر 3D برای یک شکل است را برمی‌گرداند.<br/>            توجه: برای برخی از انواع شکل‌ها که ویژگی 3D ندارند می‌تواند None بازگرداند.<br/>            فقط‌خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/oleobjectframe/effect_format/) | شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند.<br/>            توجه: برای برخی از انواع شکل‌ها که ویژگی اثر ندارند می‌تواند None بازگرداند.<br/>            فقط‌خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/oleobjectframe/fill_format/) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکردن برای یک شکل است را برمی‌گرداند.<br/>            توجه: برای برخی از انواع شکل‌ها که ویژگی پرکردن ندارند می‌تواند None بازگرداند.<br/>            فقط‌خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/oleobjectframe/hyperlink_click/) | پیوندی که برای کلیک ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | پیوندی که برای عبور ماوس تعریف شده است را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/oleobjectframe/hyperlink_manager/) | مدیر پیوندها را برمی‌گرداند.<br/>            فقط‌خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/oleobjectframe/hidden/) | تشخیص می‌دهد که آیا شکل مخفی است.<br/>            قابل‌خواندن‌و‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/oleobjectframe/z_order_position/) | موقعیت یک شکل را در ترتیب Z برمی‌گرداند.<br/>            Shapes[0] شکل را در عقب ترتیب Z برمی‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب Z برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/oleobjectframe/connection_site_count/) | تعداد نقاط اتصال روی شکل را برمی‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/oleobjectframe/rotation/) | تعداد درجه‌های چرخش شکل مشخص شده حول محور Z را برمی‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است.<br/>            قابل‌خواندن‌و‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/oleobjectframe/x/) | مختصات x گوشه بالا سمت چپ شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/oleobjectframe/y/) | مختصات y گوشه بالا سمت چپ شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/oleobjectframe/width/) | عرض شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/oleobjectframe/height/) | ارتفاع شکل را بر حسب نقاط می‌گیرد یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/oleobjectframe/black_white_mode/) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌وسفید رندر می‌شود.<br/>            قابل‌خواندن‌و‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/oleobjectframe/unique_id/) | یک شناسه داخلی در محدودهٔ ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتا و دائمی در نظر گرفته شود.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/oleobjectframe/office_interop_shape_id/) | یک شناسه یکتا در محدودهٔ اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به‌پاورپوینت یا کدهای interop اجازه می‌دهد تا به‌صورت قابل اعتماد از هر جای سند به شکل ارجاع دهد.<br/>            فقط‌خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/oleobjectframe/alternative_text/) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/oleobjectframe/alternative_text_title/) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/oleobjectframe/name/) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/oleobjectframe/is_decorative/) | گزینهٔ 'علامت‌گذاری به‌عنوان تزئینی' را می‌گیرد یا تنظیم می‌کند<br/>            قابل‌خواندن‌و‌نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/oleobjectframe/shape_lock/) | قفل‌های شکل را بازمی‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/oleobjectframe/is_grouped/) | تشخیص می‌دهد که آیا شکل گروه‌بندی شده است.<br/>            فقط‌خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/oleobjectframe/parent_group/) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت None باز می‌گردد.<br/>            فقط‌خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/oleobjectframe/slide/) | اسلاید والد یک شکل را بازمی‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/oleobjectframe/presentation/) | ارائه‌گر والد یک اسلاید را بازمی‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/oleobjectframe/graphical_object_lock/) | قفل‌های شکل را بازمی‌گرداند.<br/>            فقط‌خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/fa/aspose.slides/oleobjectframe/substitute_picture_format/) | شیء خصوصیات پرکردن تصویر OleObject را بازمی‌گرداند.<br/>            فقط‌خواندنی [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/fa/aspose.slides/oleobjectframe/substitute_picture_title/) | عنوان آیکون OleObject را بازمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`object_name`](/slides/python-net/fa/aspose.slides/oleobjectframe/object_name/) | نام یک شیء را بازمی‌گرداند یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`object_prog_id`](/slides/python-net/fa/aspose.slides/oleobjectframe/object_prog_id/) | ProgID یک شیء را بازمی‌گرداند.<br/>            فقط‌خواندنی **str**. |
| [`link_file_name`](/slides/python-net/fa/aspose.slides/oleobjectframe/link_file_name/) | مسیر کامل یک فایل پیوندی را بازمی‌گرداند. نام کوتاه فایل استفاده می‌شود.<br/>            فقط‌خواندنی **str**. |
| [`link_path_long`](/slides/python-net/fa/aspose.slides/oleobjectframe/link_path_long/) | مسیر کامل یک فایل پیوندی را بازمی‌گرداند. نام طولانی فایل استفاده می‌شود.<br/>            قابل‌خواندن‌و‌نوشتن **str**. |
| [`link_path_relative`](/slides/python-net/fa/aspose.slides/oleobjectframe/link_path_relative/) | مسیر نسبی یک فایل پیوندی را در صورت وجود بازمی‌گرداند، در غیر این صورت رشتهٔ خالی بازمی‌گرداند.<br/>            فقط‌خواندنی **str**. |
| [`embedded_file_label`](/slides/python-net/fa/aspose.slides/oleobjectframe/embedded_file_label/) | نام فایل شیء OLE جاسازی‌شده را بازمی‌گرداند |
| [`embedded_file_name`](/slides/python-net/fa/aspose.slides/oleobjectframe/embedded_file_name/) | مسیر شیء OLE جاسازی‌شده را بازمی‌گرداند |
| [`embedded_data`](/slides/python-net/fa/aspose.slides/oleobjectframe/embedded_data/) | اطلاعات مربوط به داده‌های جاسازی‌شدهٔ OLE را می‌گیرد یا تنظیم می‌کند.<br/>            قابل‌خواندن‌و‌نوشتن [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/fa/aspose.slides/oleobjectframe/is_object_icon/) | تشخیص می‌دهد که آیا یک شیء به‌صورت آیکون قابل مشاهده است.<br/>            قابل‌خواندن‌و‌نوشتن **bool**. |
| [`is_object_link`](/slides/python-net/fa/aspose.slides/oleobjectframe/is_object_link/) | تشخیص می‌دهد که آیا یک شیء به فایل خارجی پیوند دارد.<br/>            فقط‌خواندنی **bool**. |
| [`update_automatic`](/slides/python-net/fa/aspose.slides/oleobjectframe/update_automatic/) | تشخیص می‌دهد که آیا شیء پیوندی جاسازی‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روزرسانی می‌شود.<br/>            قابل‌خواندن‌و‌نوشتن **bool**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/oleobjectframe/get_image/#) | تصویر بندانگشتی شکل را بازمی‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | تصویر بندانگشتی شکل را بازمی‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/oleobjectframe/remove_placeholder/#) | تعریف می‌کند که این شکل یک نگهدارنده نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | در صورت عدم وجود، یک نگهدارندهٔ جدید اضافه می‌کند و ویژگی‌های نگهدارنده را به یک مورد مشخص تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/oleobjectframe/get_base_placeholder/#) | یک شکل نگهدارندهٔ پایه را بازمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد).<br/>            اگر شکل جاری ارث‌بری نباشد، None بازگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/oleobjectframe/get_visual_bounds/#) | حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، می‌گیرد. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/fa/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | اطلاعات مربوط به داده‌های جاسازی‌شدهٔ OLE را تنظیم می‌کند.<br/>            <br/>            این متد ویژگی‌های شیء را برای بازتاب داده‌های جدید تغییر می‌دهد و <br/>            پرچم IsObjectLink را به false تنظیم می‌کند، که نشان‌دهندهٔ اینکه شیء OLE جاسازی شده است. |

### همچنین ببینید
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`OleObjectFrame`](/slides/python-net/fa/aspose.slides/oleobjectframe)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)