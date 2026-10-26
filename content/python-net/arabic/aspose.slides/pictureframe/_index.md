---
title: PictureFrame class
second_title: Aspose.Slides للغة Python عبر مرجع .NET API
description: 
type: docs
url: /ar/aspose.slides/pictureframe/
---
## PictureFrame فئة

يمثل إطارًا يحتوي على صورة داخله.

الوراثة:[`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يظهر نوع PictureFrame الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/pictureframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/pictureframe/placeholder/) | يرجع العنصر النائب للشكل. يرجع None إذا لم يكن لدى الشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/pictureframe/custom_data/) | يرجع البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/pictureframe/raw_frame/) | يرجع أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/pictureframe/frame/) | يرجع أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/pictureframe/line_format/) | يرجع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص الخط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/pictureframe/three_d_format/) | يرجع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/pictureframe/effect_format/) | يرجع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص التأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/pictureframe/fill_format/) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: قد يرجع None لبعض أنواع الأشكال التي لا تملك خصائص التعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/pictureframe/hyperlink_click/) | يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/pictureframe/hyperlink_mouse_over/) | يرجع أو يضبط الارتباط التشعبي المحدد لتمرير الفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/pictureframe/hyperlink_manager/) | يرجع مدير الارتباطات التشعبية.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/pictureframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/pictureframe/z_order_position/) | يرجع موضع الشكل في ترتيب z.<br/>            Shapes[0] يرجع الشكل في خلفية ترتيب z,<br/>            و Shapes[Shapes.Count - 1] يرجع الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/pictureframe/connection_site_count/) | يرجع عدد نقاط الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/pictureframe/rotation/) | يرجع أو يضبط عدد درجات دوران الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/pictureframe/x/) | يرجع أو يضبط الإحداثي x لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/pictureframe/y/) | يرجع أو يضبط الإحداثي y لزاوية الشكل العليا اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/pictureframe/width/) | يرجع أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/pictureframe/height/) | يرجع أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/pictureframe/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/pictureframe/unique_id/) | يرجع معرفًا داخليًا يخص العرض تقديميًا مخصصًا للاستخدام من قبل الإضافات أو شفرة أخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم التعامل معها<br/>            كمفتاح فريد مستمر.<br/>            قراءة فقط **int**.<br/>            أنظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/pictureframe/office_interop_shape_id/) | يرجع معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل و<br/>            يتيح لبرنامج PowerPoint أو شفرة التفاعل الإشارة إلى الشكل بثقة من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            أنظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/pictureframe/alternative_text/) | يرجع أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/pictureframe/alternative_text_title/) | يرجع أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/pictureframe/name/) | يرجع أو يضبط اسم الشكل.<br/>            يجب ألا تكون None. استخدم سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/pictureframe/is_decorative/) | يرجع أو يضبط خيار 'تمييز كديكور'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/pictureframe/shape_lock/) | يرجع أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/pictureframe/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/pictureframe/parent_group/) | يرجع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يرجع None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/pictureframe/slide/) | يرجع شريحة الأب للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/pictureframe/presentation/) | يرجع عرض التقديم الأب للشرائح.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/pictureframe/shape_style/) | يرجع كائن نمط الشكل.<br/>            قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/pictureframe/shape_type/) | يرجع أو يضبط نوع AutoShape لإطار الصورة.<br/>            جميع العناصر المسموح بها في مجموعة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)، <br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/pictureframe/adjustments/) | يرجع مجموعة من قيم تعديل الشكل.<br/>            قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ar/aspose.slides/pictureframe/picture_frame_lock/) | يرجع أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ar/aspose.slides/pictureframe/picture_format/) | يرجع كائن PictureFillFormat لإطار الصورة.<br/>            قراءة فقط [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ar/aspose.slides/pictureframe/relative_scale_height/) | يرجع أو يضبط مقياس الارتفاع (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪.<br/>            قراءة/كتابة **float**. |
| [`relative_scale_width`](/slides/python-net/ar/aspose.slides/pictureframe/relative_scale_width/) | يرجع أو يضبط مقياس العرض (نسبةً إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪.<br/>            قراءة/كتابة **float**. |
| [`is_cameo`](/slides/python-net/ar/aspose.slides/pictureframe/is_cameo/) | يحدد ما إذا كان PictureFrame كائن Cameo أم لا.<br/>            قراءة فقط **bool**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/pictureframe/get_image/#) | يرجع صورة مصغرة للشكل.<br/>            يتم استخدام نوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | يرجع صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/pictureframe/remove_placeholder/#) | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى عنصر محدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/pictureframe/get_base_placeholder/#) | يرجع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو شريحة النموذج التي يرث منها الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/pictureframe/get_visual_bounds/#) | يرجع حدود الشكل البصرية المحسوبة من محتواه المعروض. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/pictureframe/get_geometry_paths/#) | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى<br/>             العليا للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | يحدّث هندسة الشكل من مجموعة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى<br/>             العليا للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/pictureframe/create_shape_elements/#) | ينشئ ويرجع مجموعة من عناصر الشكل. |

### انظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)