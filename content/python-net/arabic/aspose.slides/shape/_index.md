---
title: Shape class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shape/
---
## Shape الفئة

يمثل الشكل على شريحة.

يعرض نوع Shape الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/shape/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/shape/placeholder/) | يعيد العنصر النائب لشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/shape/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/shape/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/shape/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/shape/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص الخط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/shape/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص 3d.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/shape/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على شكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص التأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/shape/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تمتلك خصائص التعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/shape/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/shape/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/shape/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/shape/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/shape/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في الخلف من ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في المقدمة من ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/shape/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/shape/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z.<br/>            القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/shape/x/) | يحصل أو يضبط الإحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/shape/y/) | يحصل أو يضبط الإحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/shape/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/shape/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/shape/black_white_mode/) | خاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id/) | يعيد معرفًا داخليًا، نطاقه العرض التقديمي، يُقصد به الاستخدام من قبل الإضافات أو كود آخر.<br/>            نظرًا لأن هذه القيمة يمكن أن تُعاد تعيينها بواسطة المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id/) | يعيد معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالمرجعية إلى الشكل من أي مكان في المستند بثقة.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/shape/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/shape/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/shape/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/shape/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كزخرف'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/shape/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IBaseShapeLock`](/slides/python-net/ar/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/shape/is_grouped/) | يحدد ما إذا كان الشكل مجموعًا.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/shape/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعًا. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/shape/slide/) | يعيد شريحة الأب للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/shape/presentation/) | يعيد العرض التقديمي الأب للشريحة.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/shape/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يتم استخدام نوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/shape/write_as_svg/#iorawiobase) | يحفظ محتوى Shape كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى Shape كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/shape/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/shape/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن هناك ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/shape/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة الأساس التي يرث منها الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/shape/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل محسوبة من المحتوى المرسوم. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)