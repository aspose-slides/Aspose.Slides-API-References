---
title: Connector class
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/connector/
---
## Connector فئة

يمثل موصلًا.

**الوراثة:**[`Connector`](/slides/python-net/ar/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع Connector يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/connector/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/connector/placeholder/) | يعيد العنصر النائب للشكل. يُرجِع None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/connector/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/connector/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قابل للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/connector/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قابل للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/connector/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يُرجِع None لأنواع معينة من الأشكال التي لا تمتلك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/connector/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يُرجِع None لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/connector/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/>            ملاحظة: قد يُرجِع None لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/connector/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: قد يُرجِع None لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/connector/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المُعرّف للنقر بالماوس.<br/>            قابل للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/connector/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المُعرّف لتمرير الماوس فوقه.<br/>            قابل للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/connector/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/connector/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قابل للقراءة والكتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/connector/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] تُرجِع الشكل في مؤخرة ترتيب z،<br/>            و Shapes[Shapes.Count - 1] تُرجِع الشكل في مقدمة ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/connector/connection_site_count/) | يعيد عدد نقاط الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/connector/rotation/) | يعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z.<br/>            القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية<br/>            تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قابل للقراءة والكتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/connector/x/) | يحصل أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/connector/y/) | يحصل أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/connector/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/connector/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قابل للقراءة والكتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/connector/black_white_mode/) | تحدد الخاصية كيف سيُعرض الشكل في وضعية العرض بالأبيض والأسود..<br/>            قابل للقراءة والكتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/connector/unique_id/) | يعيد معرفًا داخليًا مقتصرًا على العرض يُقصد به للاستخدام من قبل الإضافات أو أي كود آخر.<br/>            نظرًا لأنه يمكن إعادة تعيين هذه القيمة من قبل المستخدم أو برمجيًا، لا ينبغي معالجتها<br/>            كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/connector/office_interop_shape_id/) | يعيد معرفًا فريدًا مقتصرًا على الشريحة يبقى ثابتًا طوال عمر الشكل وي<br/>            يسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثبات من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/connector/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بشكل.<br/>            قابل للقراءة والكتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/connector/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بشكل.<br/>            قابل للقراءة والكتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/connector/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة السلسلة الفارغة إذا لزم الأمر.<br/>            قابل للقراءة والكتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/connector/is_decorative/) | يحصل أو يضبط خيار 'Mark as decorative'<br/>            قابل للقراءة والكتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/connector/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IConnectorLock`](/slides/python-net/ar/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/connector/is_grouped/) | يحدد ما إذا كان الشكل مجمعًا.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/connector/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يُرجِع None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/connector/slide/) | يعيد الشريحة الأصلية للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/connector/presentation/) | يعيد العرض التقديمي الأصلي للشفرة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/connector/shape_style/) | يعيد كائن نمط الشكل.<br/>            للقراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/connector/shape_type/) | يعيد أو يضبط نوع AutoShape.<br/>            قابل للقراءة والكتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/connector/adjustments/) | يعيد مجموعة من قيم تعديل الشكل.<br/>            للقراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/ar/aspose.slides/connector/connector_lock/) | يعيد أقفال الموصل.<br/>            للقراءة فقط [`IConnectorLock`](/slides/python-net/ar/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ar/aspose.slides/connector/start_shape_connected_to/) | يعيد أو يضبط الشكل الذي يُرفق به بداية الموصل.<br/>            قابل للقراءة والكتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ar/aspose.slides/connector/end_shape_connected_to/) | يعيد أو يضبط الشكل الذي يُرفق به نهاية الموصل.<br/>            قابل للقراءة والكتابة [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ar/aspose.slides/connector/start_shape_connection_site_index/) | يعيد أو يضبط فهرس موقع الاتصال للشكل البداية.<br/>            قابل للقراءة والكتابة **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ar/aspose.slides/connector/end_shape_connection_site_index/) | يعيد أو يضبط فهرس موقع الاتصال للشكل النهاية.<br/>            قابل للقراءة والكتابة **int**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/connector/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود الصورة المصغرة للشك‍ل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/connector/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/connector/remove_placeholder/#) | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/connector/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/connector/get_base_placeholder/#) | يعيد شكلًا أساسيًا كعنصر نائب (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).<br/>            يُرجِع None إذا لم يكن الشكل الحالي مُرثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/connector/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل محسوبة من محتواه المُعرض. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/connector/get_geometry_paths/#) | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/connector/set_geometry_path/#igeometrypath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | يحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/connector/create_shape_elements/#) | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| [`reroute(self)`](/slides/python-net/ar/aspose.slides/connector/reroute/#) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |

### انظر أيضًا
* فئة [`Connector`](/slides/python-net/ar/aspose.slides/connector)
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)