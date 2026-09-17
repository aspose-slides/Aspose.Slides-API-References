---
title: ZoomObject class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomobject/
---
## ZoomObject الفئة

يمثل كائن Zoom في شريحة.

**الوراثة:**[`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع ZoomObject يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/zoomobject/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/zoomobject/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/zoomobject/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/zoomobject/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/zoomobject/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/zoomobject/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: يمكن أن يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/zoomobject/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: يمكن أن يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/zoomobject/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: يمكن أن يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/zoomobject/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: يمكن أن يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/zoomobject/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/zoomobject/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد للتحويم بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/zoomobject/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/zoomobject/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/zoomobject/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في الجزء الخلفي من ترتيب z,<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في الجزء الأمامي من ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/zoomobject/connection_site_count/) | يعيد عدد نقاط الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/zoomobject/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z.<br/>            قيمة إيجابية تشير إلى دوران مع اتجاه عقارب الساعة؛ قيمة سلبية تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/zoomobject/x/) | يحصل أو يضبط الإحداثي x للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/zoomobject/y/) | يحصل أو يضبط الإحداثي y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/zoomobject/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/zoomobject/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/zoomobject/black_white_mode/) | الخاصية تحدد كيف سيُعرض الشكل في وضعية عرض أبيض-أسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/zoomobject/unique_id/) | يعيد معرفًا داخليًا نطاق العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجياً، يجب عدم التعامل معها<br/>            كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/zoomobject/office_interop_shape_id/) | يعيد معرفًا فريدًا نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/zoomobject/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/zoomobject/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/zoomobject/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/zoomobject/is_decorative/) | يحصل أو يضبط خيار 'تمييز كزخرف'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/zoomobject/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/zoomobject/is_grouped/) | يحدد ما إذا كان الشكل مجمعًا.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/zoomobject/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يعيد None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/zoomobject/slide/) | يعيد الشريحة الأب للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/zoomobject/presentation/) | يعيد العرض الأب للشرحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/zoomobject/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ar/aspose.slides/zoomobject/image_type/) | يحصل أو يضبط نوع الصورة لكائن Zoom.<br/>            قراءة/كتابة [`ZoomImageType`](/slides/python-net/ar/aspose.slides/zoomimagetype).<br/>            القيمة الافتراضية: Preview |
| [`return_to_parent`](/slides/python-net/ar/aspose.slides/zoomobject/return_to_parent/) | يحصل أو يضبط سلوك التنقل في عرض الشرائح.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: false |
| [`show_background`](/slides/python-net/ar/aspose.slides/zoomobject/show_background/) | يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم الخلفية للشرحة الوجهة.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: true |
| [`zoom_image`](/slides/python-net/ar/aspose.slides/zoomobject/zoom_image/) | يحصل أو يضبط الصورة لكائن Zoom.<br/>            قراءة/كتابة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ar/aspose.slides/zoomobject/transition_duration/) | يحصل أو يضبط مدة الانتقال بين Zoom والشرحة.<br/>            قراءة/كتابة **float**.<br/>            القيمة الافتراضية: 1.0f |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/zoomobject/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية لحدود الصورة المصغرة. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/zoomobject/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/zoomobject/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (الشكل من التخطيط و/أو شريحة القالب الذي يُورث منه الشكل الحالي).<br/>            يُعاد None إذا لم يكن الشكل الحالي مُورثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/zoomobject/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُرَسَم. |

### انظر أيضًا
* الفئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الفئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)