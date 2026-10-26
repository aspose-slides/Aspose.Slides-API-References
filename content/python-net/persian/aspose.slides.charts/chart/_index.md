---
title: Chart class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chart/
---
## کلاس Chart

نمایش یک نمودار گرافیکی بر روی یک اسلاید.

**Inheritance:**[`Chart`](/slides/python-net/fa/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع Chart اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides.charts/chart/is_text_holder/) | تعیین می‌کند که آیا شکل TextHolder_PPT است.<br/>            فقط خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides.charts/chart/placeholder/) | باز می‌گرداند جای‌گیرنده برای یک شکل. اگر شکل جای‌گیرنده نداشته باشد None باز می‌گرداند.<br/>            فقط خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides.charts/chart/custom_data/) | داده‌های سفارشی شکل را باز می‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides.charts/chart/raw_frame/) | ویژگی‌های چارچوب شکل خام را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides.charts/chart/frame/) | ویژگی‌های چارچوب شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides.charts/chart/line_format/) | شیء LineFormat را باز می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع اشکالی که ویژگی خط ندارند None بازگرداند.<br/>            فقط خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides.charts/chart/three_d_format/) | شیء ThreeDFormat را باز می‌گرداند که ویژگی‌های اثر سه‌بعدی برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع اشکالی که ویژگی سه‌بعدی ندارند None بازگرداند.<br/>            فقط خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides.charts/chart/effect_format/) | شیء EffectFormat را باز می‌گرداند که شامل اثرهای پیکسل اعمال‌شده به یک شکل است.<br/>            توجه: ممکن است برای برخی انواع اشکالی که ویژگی اثر ندارند None بازگرداند.<br/>            فقط خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides.charts/chart/fill_format/) | شیء FillFormat را باز می‌گرداند که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است.<br/>            توجه: ممکن است برای برخی انواع اشکالی که ویژگی پر کردن ندارند None بازگرداند.<br/>            فقط خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides.charts/chart/hyperlink_click/) | پیوندهای تعریف‌شده برای کلیک ماوس را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides.charts/chart/hyperlink_mouse_over/) | پیوندهای تعریف‌شده برای عبور ماوس را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides.charts/chart/hyperlink_manager/) | مدیر پیوندها را باز می‌گرداند.<br/>            فقط خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides.charts/chart/hidden/) | تعیین می‌کند آیا شکل مخفی است.<br/>            قابل خواندن و نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides.charts/chart/z_order_position/) | موقعیت یک شکل را در ترتیب z باز می‌گرداند.<br/>            Shapes[0] شکل در انتهای ترتیب z را بر می‌گرداند،<br/>            و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را بر می‌گرداند.<br/>            فقط خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides.charts/chart/connection_site_count/) | تعداد نقاط اتصال روی شکل را باز می‌گرداند.<br/>            فقط خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides.charts/chart/rotation/) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را باز می‌گرداند یا تنظیم می‌کند.<br/>            مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است.<br/>            قابل خواندن و نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides.charts/chart/x/) | مختصات x گوشه بالا-چپ شکل را می‌گیرد یا تنظیم می‌کند، بر حسب نقاط.<br/>            قابل خواندن و نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.charts/chart/y/) | مختصات y گوشه بالا-چپ شکل را می‌گیرد یا تنظیم می‌کند، بر حسب نقاط.<br/>            قابل خواندن و نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.charts/chart/width/) | عرض شکل را می‌گیرد یا تنظیم می‌کند، بر حسب نقاط.<br/>            قابل خواندن و نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.charts/chart/height/) | ارتفاع شکل را می‌گیرد یا تنظیم می‌کند، بر حسب نقاط.<br/>            قابل خواندن و نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides.charts/chart/black_white_mode/) | ویژگی نحوه رندر شکل در حالت نمایش سیاه-سفید را مشخص می‌کند.<br/>            قابل خواندن و نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides.charts/chart/unique_id/) | شناسه داخلی scoped به ارائه را باز می‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است.<br/>            چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به عنوان کلید یکتا و ثابت در نظر گرفته شود.<br/>            فقط خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides.charts/chart/office_interop_shape_id/) | شناسه یکتا scoped به اسلاید را باز می‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای در سند می‌دهد.<br/>            فقط خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides.charts/chart/alternative_text/) | متن جایگزین مرتبط با شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides.charts/chart/alternative_text_title/) | عنوان متن جایگزین مرتبط با شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides.charts/chart/name/) | نام یک شکل را باز می‌گرداند یا تنظیم می‌کند.<br/>            نباید None باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید.<br/>            قابل خواندن و نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides.charts/chart/is_decorative/) | گزینه 'علامت‌گذاری به عنوان تزئینی' را می‌گیرد یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides.charts/chart/shape_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides.charts/chart/is_grouped/) | تعیین می‌کند آیا شکل گروه‌بندی شده است.<br/>            فقط خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides.charts/chart/parent_group/) | اگر شکل گروه‌بندی شده باشد شیء GroupShape والد را باز می‌گرداند. در غیر این صورت None باز می‌گرداند.<br/>            فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/chart/slide/) | اسلاید والد یک شکل را باز می‌گرداند.<br/>            فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/chart/presentation/) | ارائه (presentation) والد یک اسلاید را باز می‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides.charts/chart/graphical_object_lock/) | قفل‌های شکل را باز می‌گرداند.<br/>            فقط خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/fa/aspose.slides.charts/chart/plot_visible_cells_only/) | تعیین می‌کند آیا فقط سلول‌های قابل مشاهده ترسیم شوند. برای ترسیم هر دو سلول قابل مشاهده و مخفی False تنظیم کنید.<br/>            قابل خواندن و نوشتن **bool**. |
| [`display_blanks_as`](/slides/python-net/fa/aspose.slides.charts/chart/display_blanks_as/) | راهی برای ترسیم سلول‌های خالی در یک نمودار را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`DisplayBlanksAsType`](/slides/python-net/fa/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/fa/aspose.slides.charts/chart/chart_data/) | اطلاعاتی درباره داده‌های مرتبط یا جاسازی‌شده مربوط به یک نمودار را باز می‌گرداند.<br/>            فقط خواندنی [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/fa/aspose.slides.charts/chart/has_title/) | تعیین می‌کند آیا یک نمودار عنوان قابل مشاهده دارد.<br/>            قابل خواندن و نوشتن **bool**. |
| [`chart_title`](/slides/python-net/fa/aspose.slides.charts/chart/chart_title/) | عنوان یک نمودار را باز می‌گرداند یا تنظیم می‌کند.<br/>            فقط خواندنی [`IChartTitle`](/slides/python-net/fa/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/fa/aspose.slides.charts/chart/has_data_table/) | تعیین می‌کند آیا یک نمودار جدول داده دارد.<br/>            قابل خواندن و نوشتن **bool**. |
| [`has_legend`](/slides/python-net/fa/aspose.slides.charts/chart/has_legend/) | تعیین می‌کند آیا یک نمودار افسانه (legend) دارد.<br/>            قابل خواندن و نوشتن **bool**. |
| [`legend`](/slides/python-net/fa/aspose.slides.charts/chart/legend/) | یک افسانه برای نمودار را باز می‌گرداند یا تنظیم می‌کند.<br/>            فقط خواندنی [`ILegend`](/slides/python-net/fa/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/fa/aspose.slides.charts/chart/chart_data_table/) | جدول داده‌ای از یک نمودار را باز می‌گرداند.<br/>            فقط خواندنی [`IDataTable`](/slides/python-net/fa/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/fa/aspose.slides.charts/chart/style/) | سبک نمودار را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`StyleType`](/slides/python-net/fa/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/fa/aspose.slides.charts/chart/type/) | نوع نمودار را باز می‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن و نوشتن [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/fa/aspose.slides.charts/chart/plot_area/) | ناحیه رسم یک نمودار را نشان می‌دهد.<br/>            فقط خواندنی [`IChartPlotArea`](/slides/python-net/fa/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/fa/aspose.slides.charts/chart/rotation_3d/) | چرخش سه‌بعدی یک نمودار را باز می‌گرداند.<br/>            فقط خواندنی [`IRotation3D`](/slides/python-net/fa/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/fa/aspose.slides.charts/chart/back_wall/) | شیئی را باز می‌گرداند که امکان تغییر قالب دیوار پشت یک نمودار سه‌بعدی را می‌دهد.<br/>            فقط خواندنی [`IChartWall`](/slides/python-net/fa/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/fa/aspose.slides.charts/chart/side_wall/) | شیئی را باز می‌گرداند که امکان تغییر قالب دیوار کناری یک نمودار سه‌بعدی را می‌دهد.<br/>            فقط خواندنی [`IChartWall`](/slides/python-net/fa/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/fa/aspose.slides.charts/chart/floor/) | شیئی را باز می‌گرداند که امکان تغییر قالب کف یک نمودار سه‌بعدی را می‌دهد.<br/>            فقط خواندنی [`IChartWall`](/slides/python-net/fa/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/chart/text_format/) | قالب متن نمودار را باز می‌گرداند.<br/>            این ویژگی برای انواع زیر کاربرد ندارد: [`ChartType.TREEMAP`](/slides/python-net/fa/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/fa/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/fa/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/fa/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/fa/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/fa/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            فقط خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/fa/aspose.slides.charts/chart/theme_manager/) | مدیر تم را باز می‌گرداند.<br/>            فقط خواندنی [`IOverrideThemeManager`](/slides/python-net/fa/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/fa/aspose.slides.charts/chart/user_shapes/) | اشکال رسم‌شده روی بالای نمودار را مشخص می‌کند.<br/>            فقط خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/fa/aspose.slides.charts/chart/axes/) | دسترسی به محورهای نمودار را فراهم می‌کند.<br/>            فقط خواندنی [`IAxesManager`](/slides/python-net/fa/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/fa/aspose.slides.charts/chart/show_data_labels_over_maximum/) | مشخص می‌کند برچسب‌های داده‌ای بالاتر از حداکثر نمودار نمایش داده شوند.<br/>            قابل خواندن و نوشتن **bool**. |
| [`has_rounded_corners`](/slides/python-net/fa/aspose.slides.charts/chart/has_rounded_corners/) | مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد.<br/>            قابل خواندن و نوشتن **bool**. |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/chart/chart/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides.charts/chart/get_image/#) | تصویر بندانگشتی شکل را باز می‌گرداند.<br/>            نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض برای حدود تصویر بندانگشتی استفاده می‌شود. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | تصویر بندانگشتی شکل را باز می‌گرداند. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides.charts/chart/remove_placeholder/#) | تعریف می‌کند که این شکل یک جای‌گیرنده نیست. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | اگر جای‌گیرنده‌ای وجود نداشته باشد، یک جای‌گیرنده جدید اضافه می‌کند و ویژگی‌های جای‌گیرنده را به مقدار مشخصی تنظیم می‌کند. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides.charts/chart/get_base_placeholder/#) | یک شکل پایه جای‌گیرنده را باز می‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است).<br/>            اگر شکل جاری به ارث نرسیده باشد None بازگردانده می‌شود. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides.charts/chart/get_visual_bounds/#) | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود به‌دست می‌آورد. |
| [`validate_chart_layout(self)`](/slides/python-net/fa/aspose.slides.charts/chart/validate_chart_layout/#) | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides.charts/chart/create_theme_effective/#) | تم مؤثری برای این نمودار باز می‌گرداند. |

### موارد مرتبط
* کلاس [`Chart`](/slides/python-net/fa/aspose.slides.charts/chart)
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)