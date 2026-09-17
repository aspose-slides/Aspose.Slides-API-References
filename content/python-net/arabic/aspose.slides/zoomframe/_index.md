---
title: ZoomFrame class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/zoomframe/
---
## ZoomFrame فئة

يمثل كائن Slide Zoom في شريحة.

**الوراثة:**[`ZoomFrame`](/slides/python-net/ar/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض نوع ZoomFrame الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/zoomframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/zoomframe/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/zoomframe/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/zoomframe/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/zoomframe/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/zoomframe/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/zoomframe/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/zoomframe/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/zoomframe/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/zoomframe/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/zoomframe/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد لتحريك الفأرة فوقه.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/zoomframe/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/zoomframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/zoomframe/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل الموجود في مؤخرة ترتيب z،<br/>            وShapes[Shapes.Count - 1] يعيد الشكل الموجود في مقدمة ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/zoomframe/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/zoomframe/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول<br/>            محور z. قيمة موجبة تشير إلى دوران باتجاه عقارب الساعة؛ قيمة سالبة<br/>            تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/zoomframe/x/) | يحصل أو يضبط إحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/zoomframe/y/) | يحصل أو يضبط إحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/zoomframe/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/zoomframe/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/zoomframe/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/zoomframe/unique_id/) | يعيد معرفًا داخليًا محدود النطاق بالعرض مخصصًا للاستخدام من قبل الإضافات أو شفرة أخرى.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم التعامل معها<br/>            كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/zoomframe/office_interop_shape_id/) | يعيد معرفًا فريدًا محدود النطاق بالشريحة يبقى ثابتًا طوال عمر الشكل وي<br/>            يسمح لبرنامج PowerPoint أو شفرة التفاعل بالرجوع إلى الشكل بشكل موثوق من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/zoomframe/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/zoomframe/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/zoomframe/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/zoomframe/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كديكوري'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/zoomframe/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/zoomframe/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/zoomframe/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/zoomframe/slide/) | يعيد الشريحة الأصلية للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/zoomframe/presentation/) | يعيد العرض الأصلي للشريحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/zoomframe/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ar/aspose.slides/zoomframe/image_type/) | يحصل أو يضبط نوع الصورة لكائن Zoom.<br/>            قراءة/كتابة [`ZoomImageType`](/slides/python-net/ar/aspose.slides/zoomimagetype).<br/>            القيمة الافتراضية: Preview |
| [`return_to_parent`](/slides/python-net/ar/aspose.slides/zoomframe/return_to_parent/) | يحصل أو يضبط سلوك التنقل في عرض الشرائح.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: false |
| [`show_background`](/slides/python-net/ar/aspose.slides/zoomframe/show_background/) | يحصل أو يضبط قيمة تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: true |
| [`zoom_image`](/slides/python-net/ar/aspose.slides/zoomframe/zoom_image/) | يحصل أو يضبط صورة لكائن Zoom.<br/>            قراءة/كتابة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ar/aspose.slides/zoomframe/transition_duration/) | يحصل أو يضبط مدة الانتقال بين Zoom والشريحة.<br/>            قراءة/كتابة **float**.<br/>            القيمة الافتراضية: 1.0f |
| [`target_slide`](/slides/python-net/ar/aspose.slides/zoomframe/target_slide/) | يحصل أو يضبط كائن الشريحة الذي يربطه كائن Slide Zoom.<br/>            قراءة/كتابة [`ISlide`](/slides/python-net/ar/aspose.slides/islide). |

## الطرق

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/zoomframe/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/zoomframe/remove_placeholder/#) | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى ما تم تحديده. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/zoomframe/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة الماستر التي يرث منها الشكل الحالي).<br/>            يعاد None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/zoomframe/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُعرض. |

### انظر أيضا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`ZoomFrame`](/slides/python-net/ar/aspose.slides/zoomframe)
* فئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)