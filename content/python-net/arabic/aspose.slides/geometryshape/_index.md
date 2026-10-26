---
title: GeometryShape class
second_title: مرجع API ل Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/geometryshape/
---
## GeometryShape الفئة

Represents the parent class for all geometric shapes.

**Inheritance:**[`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

The GeometryShape type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/geometryshape/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/geometryshape/placeholder/) | إرجاع العنصر النائب للشكل. إرجاع None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/geometryshape/custom_data/) | إرجاع البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/geometryshape/raw_frame/) | إرجاع أو تعيين خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/geometryshape/frame/) | إرجاع أو تعيين خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/geometryshape/line_format/) | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص الخط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/geometryshape/three_d_format/) | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/geometryshape/effect_format/) | إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص التأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/geometryshape/fill_format/) | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص التعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/geometryshape/hyperlink_click/) | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/geometryshape/hyperlink_mouse_over/) | إرجاع أو تعيين الارتباط التشعبي المحدد للتمرير فوق الماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/geometryshape/hyperlink_manager/) | إرجاع مدير الارتباط التشعبي.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/geometryshape/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/geometryshape/z_order_position/) | إرجاع موضع الشكل في ترتيب z.<br/>            Shapes[0] تُعيد الشكل الموجود في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] تُعيد الشكل الموجود في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/geometryshape/connection_site_count/) | إرجاع عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/geometryshape/rotation/) | إرجاع أو تعيين عدد الدرجات التي يُدور فيها الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/geometryshape/x/) | إرجاع أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/geometryshape/y/) | إرجاع أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/geometryshape/width/) | إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/geometryshape/height/) | إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/geometryshape/black_white_mode/) | الخاصية تُحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/geometryshape/unique_id/) | إرجاع معرف داخلي مرتبط بالعرض مخصص للاستخدام من قبل الإضافات أو كود آخر.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            راجع أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/geometryshape/office_interop_shape_id/) | إرجاع معرف فريد مرتبط بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            راجع أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/geometryshape/alternative_text/) | إرجاع أو تعيين النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/geometryshape/alternative_text_title/) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/geometryshape/name/) | إرجاع أو تعيين اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/geometryshape/is_decorative/) | إرجاع أو تعيين خيار 'وضع علامة كديكوري'.<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/geometryshape/shape_lock/) | إرجاع أقفال الشكل.<br/>            قراءة فقط [`IBaseShapeLock`](/slides/python-net/ar/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/geometryshape/is_grouped/) | يحدد ما إذا كان الشكل مُجَمَّعًا.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/geometryshape/parent_group/) | إرجاع كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا إرجاع None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/geometryshape/slide/) | إرجاع شريحة الأب للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/geometryshape/presentation/) | إرجاع العرض الأب للشرائح.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/geometryshape/shape_style/) | إرجاع كائن نمط الشكل.<br/>            قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type/) | إرجاع أو تعيين نوع إعداد الشكل الهندسي المسبق.<br/>            ملاحظة: عند تغيير القيمة سيتم إعادة تعيين جميع قيم الضبط إلى القيم الافتراضية.<br/>            قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/geometryshape/adjustments/) | إرجاع مجموعة قيم الضبط للشكل.<br/>            قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/geometryshape/get_image/#) | إرجاع صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape لإرجاع حدود الصورة المصغرة بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | إرجاع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | حفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | حفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/geometryshape/remove_placeholder/#) | تعريف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | إضافة عنصر نائب جديد إذا لم يكن موجودًا وتعيين خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/geometryshape/get_base_placeholder/#) | إرجاع شكل عنصر نائب أساسي (شكل من التخطيط أو الشريحة الرئيسية التي يُرث منها الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي مُرَثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/geometryshape/get_visual_bounds/#) | إرجاع الحدود البصرية للشكل محسوبة من محتواه المُعرض. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/geometryshape/get_geometry_paths/#) | إرجاع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | تحديث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>            تغيير نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | تحديث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>            تغيير نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/geometryshape/create_shape_elements/#) | إنشاء وإرجاع مصفوفة من عناصر الشكل. |

### انظر أيضًا
* class [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)