---
title: GraphicalObject class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/graphicalobject/
---
## GraphicalObject فئة

يمثل كائنًا رسوميًا تجريديًا.

**Inheritance:**[`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض نوع GraphicalObject الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/graphicalobject/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/graphicalobject/placeholder/) | يرجع العنصر النائب للشكل. يرجع None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/graphicalobject/custom_data/) | يرجع البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/graphicalobject/raw_frame/) | يرجع أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/graphicalobject/frame/) | يرجع أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/graphicalobject/line_format/) | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تحتوي على خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/graphicalobject/three_d_format/) | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/graphicalobject/effect_format/) | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البيكسل المطبقة على شكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/graphicalobject/fill_format/) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/graphicalobject/hyperlink_click/) | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/graphicalobject/hyperlink_mouse_over/) | يرجع أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/graphicalobject/hyperlink_manager/) | يرجع مدير الارتباطات التشعبية.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/graphicalobject/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/graphicalobject/z_order_position/) | يرجع موضع الشكل في ترتيب Z.<br/>            Shapes[0] يرجع الشكل في الخلف من ترتيب Z،<br/>            و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب Z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/graphicalobject/connection_site_count/) | يرجع عدد مواقع الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/graphicalobject/rotation/) | يرجع أو يضبط عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/graphicalobject/x/) | يرجع أو يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/graphicalobject/y/) | يرجع أو يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/graphicalobject/width/) | يرجع أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/graphicalobject/height/) | يرجع أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/graphicalobject/black_white_mode/) | تحدد الخاصية كيف سيتم عرض الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/graphicalobject/unique_id/) | يرجع معرفًا داخليًا نطاقه العرض مخصص للاستخدام من قبل الإضافات أو تعليمات برمجية أخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها<br/>            مفتاحًا فريدًا دائمًا.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/graphicalobject/office_interop_shape_id/) | يرجع معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل و<br/>            يتيح لـ PowerPoint أو شفرة التفاعل الإشارة إلى الشكل بثقة من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/graphicalobject/alternative_text/) | يرجع أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/graphicalobject/alternative_text_title/) | يرجع أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/graphicalobject/name/) | يرجع أو يضبط اسم الشكل.<br/>            يجب أن لا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/graphicalobject/is_decorative/) | يرجع أو يضبط خيار 'وضع علامة كزخرف'.<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/graphicalobject/shape_lock/) | يرجع أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/graphicalobject/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/graphicalobject/parent_group/) | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/graphicalobject/slide/) | يرجع الشريحة الأب للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/graphicalobject/presentation/) | يرجع العرض الأب للشرائح.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/graphicalobject/graphical_object_lock/) | يرجع أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/graphicalobject/get_image/#) | يرجع صورة مصغرة للشكل.<br/>            يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | يرجع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/graphicalobject/remove_placeholder/#) | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/graphicalobject/get_base_placeholder/#) | يرجع شكلًا نائبًا أساسيًا (شكل من التخطيط و/أو الشريحة الرئيسية الذي يتم وراثة الشكل الحالي منه).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/graphicalobject/get_visual_bounds/#) | يرجع حدود الشكل البصرية المحسوبة من محتواها المُعرض. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)