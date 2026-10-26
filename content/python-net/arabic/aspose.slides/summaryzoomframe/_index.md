---
title: SummaryZoomFrame class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame فئة

يمثّل كائن ملخص التكبير (Summary Zoom) في شريحة.

**الوراثة:**[`SummaryZoomFrame`](/slides/python-net/ar/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع SummaryZoomFrame يعرّض الأعضاء التالية:

## الخصائص

| خاصية | وصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/summaryzoomframe/is_text_holder/) | يحدّد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/summaryzoomframe/placeholder/) | يرجّع العنصر النائب للشكل. يرجّع None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/summaryzoomframe/custom_data/) | يرجّع البيانات المخصّصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/summaryzoomframe/raw_frame/) | يرجّع أو يضبط خصائص إطار الشكل الخام.<br/>            للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/summaryzoomframe/frame/) | يرجّع أو يضبط خصائص إطار الشكل.<br/>            للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/summaryzoomframe/line_format/) | يرجّع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يرجّع None لبعض أنواع الأشكال التي لا تمتلك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/summaryzoomframe/three_d_format/) | يرجّع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يرجّع None لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/summaryzoomframe/effect_format/) | يرجّع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل.<br/>            ملاحظة: قد يرجّع None لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/summaryzoomframe/fill_format/) | يرجّع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يرجّع None لبعض أنواع الأشكال التي لا تمتلك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/summaryzoomframe/hyperlink_click/) | يرجّع أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | يرجّع أو يضبط الارتباط التشعبي المحدد للمرور فوقه بالماوس.<br/>            للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/summaryzoomframe/hyperlink_manager/) | يرجّع مدير الارتباطات التشعبية.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/summaryzoomframe/hidden/) | يحدّد ما إذا كان الشكل مخفيًا.<br/>            للقراءة والكتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/summaryzoomframe/z_order_position/) | يرجّع موضع الشكل في ترتيب z.<br/>            Shapes[0] تُرجع الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] تُرجع الشكل في مقدمة ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/summaryzoomframe/connection_site_count/) | يرجّع عدد مواقع الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/summaryzoomframe/rotation/) | يرجّع أو يضبط عدد درجات تدوير الشكل المحدد حول محور z.<br/>            القيمة الموجبة تعني دوران باتجاه عقارب الساعة؛ القيمة السالبة تعني دوران عكس اتجاه العقارب.<br/>            للقراءة والكتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/summaryzoomframe/x/) | يحصل أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسة بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/summaryzoomframe/y/) | يحصل أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسة بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/summaryzoomframe/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/summaryzoomframe/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/summaryzoomframe/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضع اللونين الأسود والأبيض.<br/>            للقراءة والكتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/summaryzoomframe/unique_id/) | يرجّع معرفًا داخليًا للنطاق العرضي مخصصًا للاستخدام من قبل الإضافات أو الشيفرة الأخرى.<br/>            لأن هذه القيمة يمكن أن يعيد المستخدم تعيينها برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/summaryzoomframe/office_interop_shape_id/) | يرجّع معرفًا فريدًا للنطاق العرضي للشرائح يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شيفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/summaryzoomframe/alternative_text/) | يرجّع أو يضبط النص البديل المرتبط بالشكل.<br/>            للقراءة والكتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/summaryzoomframe/alternative_text_title/) | يرجّع أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            للقراءة والكتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/summaryzoomframe/name/) | يرجّع أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة السلسلة الفارغة إذا لزم الأمر.<br/>            للقراءة والكتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/summaryzoomframe/is_decorative/) | يحصل أو يضبط خيار “ضع علامة كديكور”.<br/>            للقراءة والكتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/summaryzoomframe/shape_lock/) | يرجّع أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/summaryzoomframe/is_grouped/) | يحدّد ما إذا كان الشكل ضمن مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/summaryzoomframe/parent_group/) | يرجّع كائن GroupShape الأب إذا كان الشكل ضمن مجموعة. وإلا يرجّع None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/summaryzoomframe/slide/) | يرجّع الشريحة الأب للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/summaryzoomframe/presentation/) | يرجّع العرض التقديمي الأب للشرائح.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/summaryzoomframe/graphical_object_lock/) | يرجّع أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/ar/aspose.slides/summaryzoomframe/layout/) | يحصل على تخطيط أقسام ملخص التكبير داخل الإطار.<br/>            القيمة الافتراضية هي GridLayout. |
| [`summary_zoom_collection`](/slides/python-net/ar/aspose.slides/summaryzoomframe/summary_zoom_collection/) | يحصل على [`ISummaryZoomSectionCollection`](/slides/python-net/ar/aspose.slides/isummaryzoomsectioncollection) لكائن SummaryZoomFrame. |

## الطرق

| طريقة | وصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/get_image/#) | يرجّع صورة مصغرة للشكل.<br/>            يُستخدم نوع ShapeThumbnailBounds.Shape كقيمة افتراضية لحدود الصورة المصغرة. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | يرجّع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى ما هو محدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/get_base_placeholder/#) | يرجّع شكلًا عنصرًا نائبًا أساسيًا (من تخطيط أو شريحة رئيسية يرث منها الشكل الحالي).<br/>            يرجّع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/summaryzoomframe/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`SummaryZoomFrame`](/slides/python-net/ar/aspose.slides/summaryzoomframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)