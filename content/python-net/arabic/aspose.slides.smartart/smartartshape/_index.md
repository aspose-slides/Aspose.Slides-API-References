---
title: SmartArtShape class
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.smartart/smartartshape/
---
## فئة SmartArtShape

يمثل SmartArt shape

**الوراثة:**[`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يظهر نوع SmartArtShape الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/placeholder/) | يرجع العنصر النائب للشكل. يرجع None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/custom_data/) | يرجع البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/raw_frame/) | يرجع أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/frame/) | يرجع أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/line_format/) | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/three_d_format/) | يرجع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/effect_format/) | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/fill_format/) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/hyperlink_click/) | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | يرجع أو يضبط الارتباط التشعبي المحدد للتمرير فوق الماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/hyperlink_manager/) | يرجع مدير الارتباطات التشعبية.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/z_order_position/) | يرجع موضع الشكل في ترتيب z.<br/>            Shapes[0] يرجع الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/connection_site_count/) | يرجع عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/rotation/) | يرجع أو يضبط عدد الدرجات التي يدور حولها الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/x/) | يحصل أو يضبط الإحداثي السيني للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/y/) | يحصل أو يضبط الإحداثي الصادي للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضع العرض الأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/unique_id/) | يرجع معرفًا داخليًا يخص العرض، مخصص للاستخدام من قبل الإضافات أو الكود الآخر.<br/>            لأن هذه القيمة يمكن أن يعيد تعيينها المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | يرجع معرفًا فريدًا يخص الشريحة يظل ثابتًا طوال عمر الشكل ويسمح لPowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/alternative_text/) | يرجع أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/alternative_text_title/) | يرجع أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/name/) | يرجع أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/is_decorative/) | يحصل أو يضبط خيار 'Mark as decorative'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/shape_lock/) | يرجع أقفال الشكل.<br/>            قراءة فقط [`IBaseShapeLock`](/slides/python-net/ar/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/parent_group/) | يرجع كائن GroupShape الأصل إذا كان الشكل مجموعة. وإلا يرجع None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/slide/) | يرجع الشريحة الأصلية للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/presentation/) | يرجع العرض الأصلي للشرائح.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/shape_style/) | يرجع كائن نمط الشكل.<br/>            قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/shape_type/) | يرجع أو يضبط نوع الإعداد المسبق للهندسة.<br/>            ملاحظة: عند تغيير القيمة سيتم إعادة جميع قيم التعديل إلى القيم الافتراضية.<br/>            قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/adjustments/) | يرجع مجموعة قيم تعديل الشكل.<br/>            قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/text_frame/) | يرجع نص شكل SmartArt.<br/>            قراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/get_image/#) | يرجع صورة مصغرة للشكل.<br/>            ShapeThumbnailBounds.Shape نوع حدود الصورة المصغرة للشكل يستخدم افتراضيًا. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | يرجع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو شريحة الماستر التي يُورث منها الشكل الحالي).<br/>            يرجع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المعروض. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | يحدث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>            يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | يحدث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>            يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides.smartart/smartartshape/create_shape_elements/#) | ينشئ ويعود بمصفوفة عناصر الشكل. |


### أنظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)