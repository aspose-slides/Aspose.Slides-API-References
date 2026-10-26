---
title: AutoShape class
second_title: مرجع API لـ Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/autoshape/
---
## فئة AutoShape

يمثل AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع AutoShape يكشف عن الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/autoshape/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/autoshape/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/autoshape/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/autoshape/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قابل للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/autoshape/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قابل للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/autoshape/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/autoshape/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/autoshape/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/autoshape/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/autoshape/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قابل للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/autoshape/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد لتمرير الفأرة فوقه.<br/>            قابل للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/autoshape/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/autoshape/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قابل للقراءة والكتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/autoshape/z_order_position/) | يعيد موضع الشكل في ترتيب الـ z.<br/>            Shapes[0] يرجع الشكل في عنق الزاوية الخلفية للترتيب،<br/>            و Shapes[Shapes.Count - 1] يرجع الشكل في أمامية الترتيب.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/autoshape/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/autoshape/rotation/) | يعيد أو يضبط عدد درجات دوران الشكل حول محور الـ z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قابل للقراءة والكتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/autoshape/x/) | يحصل أو يضبط الإحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/autoshape/y/) | يحصل أو يضبط الإحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/autoshape/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/autoshape/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/autoshape/black_white_mode/) | الخاصية تحدد كيف سيُعرض الشكل في وضعية العرض بالأبيض والأسود.<br/>            قابل للقراءة والكتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/autoshape/unique_id/) | يعيد معرفًا داخليًا يخص العرض، مخصص للاستخدام من قبل الإضافات أو الشيفرات الأخرى.<br/>            بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم التعامل معها كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/autoshape/office_interop_shape_id/) | يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/autoshape/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قابل للقراءة والكتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/autoshape/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قابل للقراءة والكتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/autoshape/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قابل للقراءة والكتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/autoshape/is_decorative/) | يحصل أو يضبط خيار "علامة كديكور".<br/>            قابل للقراءة والكتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/autoshape/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IAutoShapeLock`](/slides/python-net/ar/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/autoshape/is_grouped/) | يحدد ما إذا كان الشكل مجموعًا.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/autoshape/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعًا. وإلا يرجع None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/autoshape/slide/) | يعيد الشريحة الأب للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/autoshape/presentation/) | يعيد العرض التقديمي الأب للشريحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/autoshape/shape_style/) | يعيد كائن نمط الشكل.<br/>            للقراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/autoshape/shape_type/) | يعيد أو يضبط نوع الإعداد المسبق للهندسة.<br/>            ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديلات إلى القيم الافتراضية.<br/>            قابل للقراءة والكتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/autoshape/adjustments/) | يعيد مجموعة قيم تعديل الشكل.<br/>            للقراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/ar/aspose.slides/autoshape/auto_shape_lock/) | يعيد أقفال الشكل التلقائي.<br/>            للقراءة فقط [`IAutoShapeLock`](/slides/python-net/ar/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ar/aspose.slides/autoshape/text_frame/) | يعيد كائن TextFrame للـ AutoShape.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ar/aspose.slides/autoshape/use_background_fill/) | يحدد ما إذا كان يجب ملء هذا الشكل التلقائي بخلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق التعبئة.<br/>            قابل للقراءة والكتابة **bool**. |
| [`is_text_box`](/slides/python-net/ar/aspose.slides/autoshape/is_text_box/) | يحدد ما إذا كان الشكل صندوق نص. |

## الطرق

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/autoshape/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type يُستخدم بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/autoshape/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/autoshape/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/autoshape/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/autoshape/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من تخطيط أو شريحة رئيسية يتم وراثته من قبل الشكل الحالي).<br/>            يرجع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/autoshape/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/autoshape/get_geometry_paths/#) | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العليا اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | يحدث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). الإحداثيات يجب أن تكون نسبية للزاوية العليا اليسرى للشكل.<br/>            يغير نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | يحدث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). الإحداثيات يجب أن تكون نسبية للزاوية العليا اليسرى للشكل.<br/>            يغير نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/autoshape/create_shape_elements/#) | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| [`add_text_frame(self, text)`](/slides/python-net/ar/aspose.slides/autoshape/add_text_frame/#str) | يضيف TextFrame جديدًا إلى الشكل.<br/>            إذا كان الشكل يحتوي بالفعل على TextFrame فسيتم ببساطة تغيير نصه. |


### انظر أيضاً
* الفئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* الفئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)