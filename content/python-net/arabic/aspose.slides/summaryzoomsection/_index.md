---
title: SummaryZoomSection class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomsection/
---
## فئة SummaryZoomSection

يمثل كائن Summary Zoom Section داخل إطار Summary Zoom.

**الوراثة:**[`SummaryZoomSection`](/slides/python-net/ar/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع SummaryZoomSection يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/summaryzoomsection/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/summaryzoomsection/placeholder/) | يعيد العنصر النائب (placeholder) للشكل. يُعيد None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/summaryzoomsection/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/summaryzoomsection/raw_frame/) | يعيد أو يحدد خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/summaryzoomsection/frame/) | يعيد أو يحدد خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/summaryzoomsection/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تحتوي على خصائص الخط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/summaryzoomsection/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/summaryzoomsection/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تحتوي على خصائص التأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/summaryzoomsection/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تحتوي على خصائص التعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/summaryzoomsection/hyperlink_click/) | يعيد أو يحدد الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | يعيد أو يحدد الارتباط التشعبي المحدد لتحريك الفأرة فوقه.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/summaryzoomsection/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/summaryzoomsection/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/summaryzoomsection/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/summaryzoomsection/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/summaryzoomsection/rotation/) | يعيد أو يحدد عدد الدرجات التي يُدوَر فيها الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/summaryzoomsection/x/) | يحصل أو يحدد الإحداثي السيني للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/summaryzoomsection/y/) | يحصل أو يحدد الإحداثي الصادي للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/summaryzoomsection/width/) | يحصل أو يحدد عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/summaryzoomsection/height/) | يحصل أو يحدد ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/summaryzoomsection/black_white_mode/) | المخاصية تحدد كيف سيُظهر الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/summaryzoomsection/unique_id/) | يعيد معرفًا داخليًا ضمن نطاق العرض مخصص للاستخدام من قبل الإضافات أو التعليمات البرمجية الأخرى.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/summaryzoomsection/office_interop_shape_id/) | يعيد معرفًا فريدًا ضمن نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويتيح لـ PowerPoint أو شفرة التفاعل الإشارة إلى الشكل بثقة من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/summaryzoomsection/alternative_text/) | يعيد أو يحدد النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/summaryzoomsection/alternative_text_title/) | يعيد أو يحدد عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/summaryzoomsection/name/) | يعيد أو يحدد اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/summaryzoomsection/is_decorative/) | يحصل أو يحدد خيار 'علامة كديكور'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/summaryzoomsection/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/summaryzoomsection/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/summaryzoomsection/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/summaryzoomsection/slide/) | يعيد الشريحة الأم للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/summaryzoomsection/presentation/) | يعيد العرض الأم للشريحة.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/summaryzoomsection/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ar/aspose.slides/summaryzoomsection/image_type/) | يحصل أو يحدد نوع الصورة لكائن Zoom.<br/>            قراءة/كتابة [`ZoomImageType`](/slides/python-net/ar/aspose.slides/zoomimagetype).<br/>            القيمة الافتراضية: Preview |
| [`return_to_parent`](/slides/python-net/ar/aspose.slides/summaryzoomsection/return_to_parent/) | يحصل أو يحدد سلوك التنقل في عرض الشرائح.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: false |
| [`show_background`](/slides/python-net/ar/aspose.slides/summaryzoomsection/show_background/) | يحصل أو يحدد القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: true |
| [`zoom_image`](/slides/python-net/ar/aspose.slides/summaryzoomsection/zoom_image/) | يحصل أو يحدد الصورة لكائن Zoom.<br/>            قراءة/كتابة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ar/aspose.slides/summaryzoomsection/transition_duration/) | يحصل أو يحدد مدة الانتقال بين Zoom والشريحة.<br/>            قراءة/كتابة **float**.<br/>            القيمة الافتراضية: 1.0f |
| [`target_section`](/slides/python-net/ar/aspose.slides/summaryzoomsection/target_section/) | يحصل أو يحدد كائن القسم الذي يرتبط به كائن Section Zoom.<br/>            قراءة/كتابة [`ISection`](/slides/python-net/ar/aspose.slides/isection). |
| [`title`](/slides/python-net/ar/aspose.slides/summaryzoomsection/title/) | يعيد عنوان النص لكائن Summary Zoom Section. |
| [`description`](/slides/python-net/ar/aspose.slides/summaryzoomsection/description/) | يعيد الوصف النصي لكائن Summary Zoom Section. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشكل افتراضيًا. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة القالب التي يُورث منها الشكل الحالي).<br/>            يُعاد None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/summaryzoomsection/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل محسوبة من محتواه المُعرض. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`SummaryZoomSection`](/slides/python-net/ar/aspose.slides/summaryzoomsection)
* فئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)