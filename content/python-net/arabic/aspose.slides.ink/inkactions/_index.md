---
title: InkActions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ink/inkactions/
---
## InkActions فئة

يمثل الجذر لإجراءات الحبر.

**الوراثة:**[`InkActions`](/slides/python-net/ar/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض النوع InkActions الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides.ink/inkactions/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides.ink/inkactions/placeholder/) | يرجع العنصر النائب للshape. يرجع None إذا لم يكن للshape عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides.ink/inkactions/custom_data/) | يرجع البيانات المخصصة للshape.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides.ink/inkactions/raw_frame/) | يرجع أو يضبط خصائص إطار shape الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides.ink/inkactions/frame/) | يرجع أو يضبط خصائص إطار shape.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides.ink/inkactions/line_format/) | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للshape.<br/>            ملاحظة: قد يرجع None لبعض أنواع الshape التي لا تحتوي على خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides.ink/inkactions/three_d_format/) | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للshape.<br/>            ملاحظة: قد يرجع None لبعض أنواع الshape التي لا تحتوي على خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides.ink/inkactions/effect_format/) | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على shape.<br/>            ملاحظة: قد يرجع None لبعض أنواع الshape التي لا تحتوي على خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides.ink/inkactions/fill_format/) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للshape.<br/>            ملاحظة: قد يرجع None لبعض أنواع الshape التي لا تحتوي على خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides.ink/inkactions/hyperlink_click/) | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | يرجع أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides.ink/inkactions/hyperlink_manager/) | يرجع مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides.ink/inkactions/hidden/) | يحدد ما إذا كان shape مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides.ink/inkactions/z_order_position/) | يرجع موضع shape في ترتيب z.<br/>            Shapes[0] يرجع الشكل في الخلف من ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يرجع الشكل في المقدمة من ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides.ink/inkactions/connection_site_count/) | يرجع عدد مواقع الاتصال على shape.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides.ink/inkactions/rotation/) | يرجع أو يضبط عدد الدرجات التي يدور فيها shape المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه العقارب.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides.ink/inkactions/x/) | يرجع أو يضبط الإحداثي x للزاوية العليا اليسرى للshape، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.ink/inkactions/y/) | يرجع أو يضبط الإحداثي y للزاوية العليا اليسرى للshape، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.ink/inkactions/width/) | يرجع أو يضبط عرض shape، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.ink/inkactions/height/) | يرجع أو يضبط ارتفاع shape، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides.ink/inkactions/black_white_mode/) | تحدد الخاصية كيفية عرض shape في وضع العرض أبيض-أسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides.ink/inkactions/unique_id/) | يرجع معرفًا داخليًا نطاقه العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو كود آخر.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها<br/>            مفتاحًا فريدًا دائمًا.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides.ink/inkactions/office_interop_shape_id/) | يرجع معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر shape ويتيح لPowerPoint أو كود التفاعل الإشارة إلى shape بثقة من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides.ink/inkactions/alternative_text/) | يرجع أو يضبط النص البديل المرتبط بالshape.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides.ink/inkactions/alternative_text_title/) | يرجع أو يضبط عنوان النص البديل المرتبط بالshape.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides.ink/inkactions/name/) | يرجع أو يضبط اسم الshape.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides.ink/inkactions/is_decorative/) | يرجع أو يضبط خيار 'وضع علامة كديكوري' <br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides.ink/inkactions/shape_lock/) | يرجع أقفال الshape.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides.ink/inkactions/is_grouped/) | يحدد ما إذا كان الshape مجموعًا.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides.ink/inkactions/parent_group/) | يرجع كائن GroupShape الأب إذا كان الshape مجموعًا. وإلا يرجع None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides.ink/inkactions/slide/) | يرجع الشريحة الأم للshape.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides.ink/inkactions/presentation/) | يرّجع العرض التقديمي الأم للشريحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides.ink/inkactions/graphical_object_lock/) | يرجع أقفال الshape.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides.ink/inkactions/get_image/#) | يرجع صورة مصغرة للshape.<br/>            يتم استخدام النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة للshape بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | يرجع صورة مصغرة للshape. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | يحفظ محتوى Shape كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى Shape كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides.ink/inkactions/remove_placeholder/#) | يحدد أن هذا الshape ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides.ink/inkactions/get_base_placeholder/#) | يرجع شكل عنصر نائب أساسي (shape من التخطيط و/أو شريحة القالب الذي يرث منه الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides.ink/inkactions/get_visual_bounds/#) | يرجع الحدود البصرية للshape المحسوبة من محتواه المعروض. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`InkActions`](/slides/python-net/ar/aspose.slides.ink/inkactions)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* مكتبة [`Aspose.Slides`](/slides/python-net)