---
title: SectionZoomFrame class
second_title: Aspose.Slides للPython عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame فئة

Represents a Section Zoom object in a slide.

**الوراثة:**[`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/sectionzoomframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/sectionzoomframe/placeholder/) | يعيد العنصر النائب للشكل. يرجع None إذا لم يكن لل الشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/sectionzoomframe/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/sectionzoomframe/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/sectionzoomframe/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/sectionzoomframe/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/sectionzoomframe/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/sectionzoomframe/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/sectionzoomframe/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/sectionzoomframe/hyperlink_click/) | يعيد أو يضبط الرابط التشعبي المعرفة للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | يعيد أو يضبط الرابط التشعبي المعرفة للتحويم بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/sectionzoomframe/hyperlink_manager/) | يعيد مدير الروابط التشعبية.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/sectionzoomframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/sectionzoomframe/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل الموجود في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل الموجود في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/sectionzoomframe/connection_site_count/) | يعيد عدد نقاط الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/sectionzoomframe/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم تدوير الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه العقارب.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/sectionzoomframe/x/) | يعيد أو يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، بوحدات النقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/sectionzoomframe/y/) | يعيد أو يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، بوحدات النقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/sectionzoomframe/width/) | يعيد أو يضبط عرض الشكل، بوحدات النقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/sectionzoomframe/height/) | يعيد أو يضبط ارتفاع الشكل، بوحدات النقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/sectionzoomframe/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/sectionzoomframe/unique_id/) | يعيد معرفًا داخليًا يقتصر على العرض ويُقصد به للاستخدام من قبل الإضافات أو أي كود آخر.<br/>            لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/sectionzoomframe/office_interop_shape_id/) | يعيد معرفًا فريدًا يقتصر على الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/sectionzoomframe/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/sectionzoomframe/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/sectionzoomframe/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/sectionzoomframe/is_decorative/) | يعيد أو يضبط خيار 'وضع علامة كديكور'.<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/sectionzoomframe/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/sectionzoomframe/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/sectionzoomframe/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/sectionzoomframe/slide/) | يعيد الشريحة الأم للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/sectionzoomframe/presentation/) | يعيد العرض الأم للشريحة.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/sectionzoomframe/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ar/aspose.slides/sectionzoomframe/image_type/) | يعيد أو يضبط نوع الصورة لكائن التكبير.<br/>            قراءة/كتابة [`ZoomImageType`](/slides/python-net/ar/aspose.slides/zoomimagetype).<br/>            القيمة الافتراضية: Preview |
| [`return_to_parent`](/slides/python-net/ar/aspose.slides/sectionzoomframe/return_to_parent/) | يعيد أو يضبط سلوك التنقل في عرض الشرائح.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: false |
| [`show_background`](/slides/python-net/ar/aspose.slides/sectionzoomframe/show_background/) | يعيد أو يضبط قيمة تحدد ما إذا كان التكبير سيستخدم خلفية الشريحة المستهدفة.<br/>            قراءة/كتابة **bool**.<br/>            القيمة الافتراضية: true |
| [`zoom_image`](/slides/python-net/ar/aspose.slides/sectionzoomframe/zoom_image/) | يعيد أو يضبط الصورة لكائن التكبير.<br/>            قراءة/كتابة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ar/aspose.slides/sectionzoomframe/transition_duration/) | يعيد أو يضبط مدة الانتقال بين التكبير والشريحة.<br/>            قراءة/كتابة **float**.<br/>            القيمة الافتراضية: 1.0f |
| [`target_section`](/slides/python-net/ar/aspose.slides/sectionzoomframe/target_section/) | يعيد أو يضبط كائن القسم الذي يربط به كائن Section Zoom.<br/>            قراءة/كتابة [`ISection`](/slides/python-net/ar/aspose.slides/isection). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape كحدود للصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يوجد ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية التي يتم وراثة الشكل الحالي منها).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي وراثيًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/sectionzoomframe/get_visual_bounds/#) | يعيد الحدود البصرية للشكل المحسوبة من محتواه المعروض. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)