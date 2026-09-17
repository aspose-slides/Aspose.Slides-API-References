---
title: Chart class
second_title: Aspose.Slides للـ Python عبر .NET API المرجعية
description: 
type: docs
url: /ar/aspose.slides.charts/chart/
---
## فئة Chart

يمثل رسمًا بيانيًا على شريحة.

**الوراثة:**[`Chart`](/slides/python-net/ar/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

تعرض فئة Chart الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides.charts/chart/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides.charts/chart/placeholder/) | إرجاع العنصر النائب للشكل. إرجاع None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides.charts/chart/custom_data/) | إرجاع البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides.charts/chart/raw_frame/) | إرجاع أو تعيين خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides.charts/chart/frame/) | إرجاع أو تعيين خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides.charts/chart/line_format/) | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تمتلك خصائص خط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides.charts/chart/three_d_format/) | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides.charts/chart/effect_format/) | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على الشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides.charts/chart/fill_format/) | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تمتلك خصائص تعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides.charts/chart/hyperlink_click/) | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides.charts/chart/hyperlink_mouse_over/) | إرجاع أو تعيين الارتباط التشعبي المحدد للتمرير فوق الماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides.charts/chart/hyperlink_manager/) | إرجاع مدير الارتباط التشعبي.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides.charts/chart/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides.charts/chart/z_order_position/) | إرجاع موضع الشكل في ترتيب z.<br/>            Shapes[0] إرجاع الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] إرجاع الشكل في واجهة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides.charts/chart/connection_site_count/) | إرجاع عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides.charts/chart/rotation/) | إرجاع أو تعيين عدد درجات دوران الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides.charts/chart/x/) | إرجاع أو تعيين الإحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.charts/chart/y/) | إرجاع أو تعيين الإحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.charts/chart/width/) | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.charts/chart/height/) | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides.charts/chart/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضعية الأسود والأبيض.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides.charts/chart/unique_id/) | إرجاع معرف داخلي يخص العرض التقديمي مخصص للاستخدام بواسطة الإضافات أو تعليمات برمجة أخرى.<br/>            لأن هذا القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي معاملتها كمفتاح فريد دائم.<br/>            قراءة فقط **int**.<br/>            أنظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides.charts/chart/office_interop_shape_id/) | إرجاع معرف فريد يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            أنظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides.charts/chart/alternative_text/) | إرجاع أو تعيين النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides.charts/chart/alternative_text_title/) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides.charts/chart/name/) | إرجاع أو تعيين اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides.charts/chart/is_decorative/) | إرجاع أو تعيين خيار 'علامة كزخرف'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides.charts/chart/shape_lock/) | إرجاع أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides.charts/chart/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides.charts/chart/parent_group/) | إرجاع كائن GroupShape الأصل إذا كان الشكل مجموعة. وإلا إرجاع None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides.charts/chart/slide/) | إرجاع الشريحة الأصلية للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides.charts/chart/presentation/) | إرجاع العرض التقديمي الأصل للشرائح.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides.charts/chart/graphical_object_lock/) | إرجاع أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/ar/aspose.slides.charts/chart/plot_visible_cells_only/) | يحدد ما إذا كانت الخلايا المرئية فقط هي التي تُرسم. False لت رسم كل من الخلايا المرئية والمخفية.<br/>            قراءة/كتابة **bool**. |
| [`display_blanks_as`](/slides/python-net/ar/aspose.slides.charts/chart/display_blanks_as/) | إرجاع أو تعيين طريقة رسم الخلايا الفارغة في المخطط.<br/>            قراءة/كتابة [`DisplayBlanksAsType`](/slides/python-net/ar/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/ar/aspose.slides.charts/chart/chart_data/) | إرجاع معلومات حول البيانات المرتبطة أو المضمّنة مع المخطط.<br/>            قراءة فقط [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/ar/aspose.slides.charts/chart/has_title/) | يحدد ما إذا كان للمخطط عنوان مرئي.<br/>            قراءة/كتابة **bool**. |
| [`chart_title`](/slides/python-net/ar/aspose.slides.charts/chart/chart_title/) | إرجاع أو تعيين عنوان المخطط.<br/>            قراءة فقط [`IChartTitle`](/slides/python-net/ar/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/ar/aspose.slides.charts/chart/has_data_table/) | يحدد ما إذا كان للمخطط جدول بيانات.<br/>            قراءة/كتابة **bool**. |
| [`has_legend`](/slides/python-net/ar/aspose.slides.charts/chart/has_legend/) | يحدد ما إذا كان للمخطط مفتاح توضيحي.<br/>            قراءة/كتابة **bool**. |
| [`legend`](/slides/python-net/ar/aspose.slides.charts/chart/legend/) | إرجاع أو تعيين مفتاح توضيحي للمخطط.<br/>            قراءة فقط [`ILegend`](/slides/python-net/ar/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/ar/aspose.slides.charts/chart/chart_data_table/) | إرجاع جدول بيانات للمخطط.<br/>            قراءة فقط [`IDataTable`](/slides/python-net/ar/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/ar/aspose.slides.charts/chart/style/) | إرجاع أو تعيين نمط المخطط.<br/>            قراءة/كتابة [`StyleType`](/slides/python-net/ar/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/ar/aspose.slides.charts/chart/type/) | إرجاع أو تعيين نوع المخطط.<br/>            قراءة/كتابة [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/ar/aspose.slides.charts/chart/plot_area/) | يمثل منطقة الرسم للمخطط.<br/>            قراءة فقط [`IChartPlotArea`](/slides/python-net/ar/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/ar/aspose.slides.charts/chart/rotation_3d/) | إرجاع دوران ثلاثي الأبعاد للمخطط.<br/>            قراءة فقط [`IRotation3D`](/slides/python-net/ar/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/ar/aspose.slides.charts/chart/back_wall/) | إرجاع كائن يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد.<br/>            قراءة فقط [`IChartWall`](/slides/python-net/ar/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/ar/aspose.slides.charts/chart/side_wall/) | إرجاع كائن يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد.<br/>            قراءة فقط [`IChartWall`](/slides/python-net/ar/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/ar/aspose.slides.charts/chart/floor/) | إرجاع كائن يتيح تغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد.<br/>            قراءة فقط [`IChartWall`](/slides/python-net/ar/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/ar/aspose.slides.charts/chart/text_format/) | إرجاع تنسيق نص المخطط.<br/>            الخاصية غير مطبقة للأنواع التالية: [`ChartType.TREEMAP`](/slides/python-net/ar/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/ar/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/ar/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/ar/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/ar/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/ar/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            قراءة فقط [`IChartTextFormat`](/slides/python-net/ar/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides.charts/chart/theme_manager/) | إرجاع مدير السمة.<br/>            قراءة فقط [`IOverrideThemeManager`](/slides/python-net/ar/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/ar/aspose.slides.charts/chart/user_shapes/) | تحديد الأشكال المرسومة فوق المخطط.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/ar/aspose.slides.charts/chart/axes/) | توفير وصول إلى محاور المخطط.<br/>            قراءة فقط [`IAxesManager`](/slides/python-net/ar/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/ar/aspose.slides.charts/chart/show_data_labels_over_maximum/) | تحديد ما إذا كانت ملصقات البيانات فوق الحد الأقصى للمخطط يجب عرضها.<br/>            قراءة/كتابة **bool**. |
| [`has_rounded_corners`](/slides/python-net/ar/aspose.slides.charts/chart/has_rounded_corners/) | تحديد ما إذا كان لمنطقة المخطط أن تكون ذات زوايا مستديرة.<br/>            قراءة/كتابة **bool**. |
| [`chart`](/slides/python-net/ar/aspose.slides.charts/chart/chart/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides.charts/chart/get_image/#) | إرجاع صورة مصغرة للشكل.<br/>            يتم استخدام النوع ShapeThumbnailBounds.Shape كنوع حدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | إرجاع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | حفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | حفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides.charts/chart/remove_placeholder/#) | تعريف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | إضافة عنصر نائب جديد إذا لم يكن موجودًا وتعيين خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides.charts/chart/get_base_placeholder/#) | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides.charts/chart/get_visual_bounds/#) | إرجاع الحدود المرئية للشكل المحسوبة من محتواه المرسوم. |
| [`validate_chart_layout(self)`](/slides/python-net/ar/aspose.slides.charts/chart/validate_chart_layout/#) | حساب القيم الفعلية لعناصر المخطط. تشمل القيم الفعلية موضع العناصر التي تنفذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides.charts/chart/create_theme_effective/#) | إرجاع سمة فعّالة لهذا المخطط. |

### انظر أيضًا
* فئة [`Chart`](/slides/python-net/ar/aspose.slides.charts/chart)
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)