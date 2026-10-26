---
title: VideoFrame class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/videoframe/
---
## فئة VideoFrame

يمثل مقطع فيديو على شريحة.

**Inheritance:**[`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض نوع VideoFrame الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/videoframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/videoframe/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للshape عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/videoframe/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/videoframe/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/videoframe/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/videoframe/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص الخط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/videoframe/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/videoframe/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص التأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/videoframe/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق الملء لشكل.<br/>            ملاحظة: قد يعيد None لأنواع معينة من الأشكال التي لا تملك خصائص الملء.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد عند تمرير الفأرة فوقه.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_manager/) | يعيد مدير الارتباطات التشعبية.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/videoframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/videoframe/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في خلف ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/videoframe/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/videoframe/rotation/) | يعيد أو يضبط عدد الدرجات التي يُدوَّر بها الشكل المحدد حول محور z.<br/>            القيمة الإيجابية تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/videoframe/x/) | يحصل أو يضبط إحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/videoframe/y/) | يحصل أو يضبط إحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/videoframe/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/videoframe/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/videoframe/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/videoframe/unique_id/) | يعيد معرفًا داخليًا ذو نطاق عرض تقديمي مخصص للاستخدام من قبل الإضافات أو كود آخر.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/videoframe/office_interop_shape_id/) | يعيد معرفًا فريدًا ذو نطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويتيح لبرنامج PowerPoint أو كود التفاعل الإشارة إلى الشكل من أي مكان في المستند بشكل موثوق.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/videoframe/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/videoframe/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/videoframe/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب أن لا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/videoframe/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كزخرف'.<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/videoframe/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/videoframe/is_grouped/) | يحدد ما إذا كان الشكل مُجَمَّعًا.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/videoframe/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مُجَمَّعًا. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/videoframe/slide/) | يعيد الشريحة الأم للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/videoframe/presentation/) | يعيد عرض الشرائح الأم للشريحة.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/videoframe/shape_style/) | يعيد كائن نمط الشكل.<br/>            قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/videoframe/shape_type/) | يعيد أو يضبط نوع AutoShape لإطار الصورة.<br/>            جميع العناصر المسموح بها في المجموعة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)، <br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/videoframe/adjustments/) | يعيد مجموعة من قيم تعديل الشكل.<br/>            قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ar/aspose.slides/videoframe/picture_frame_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ar/aspose.slides/videoframe/picture_format/) | يعيد كائن PictureFillFormat لإطار الصورة.<br/>            قراءة فقط [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ar/aspose.slides/videoframe/relative_scale_height/) | يعيد أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪.<br/>            قراءة/كتابة **float**. |
| [`relative_scale_width`](/slides/python-net/ar/aspose.slides/videoframe/relative_scale_width/) | يعيد أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪.<br/>            قراءة/كتابة **float**. |
| [`is_cameo`](/slides/python-net/ar/aspose.slides/videoframe/is_cameo/) | يحدد ما إذا كان إطار الصورة كائن Cameo أم لا.<br/>            قراءة فقط **bool**. |
| [`rewind_video`](/slides/python-net/ar/aspose.slides/videoframe/rewind_video/) | يحدد ما إذا كان يتم إرجاع الفيديو تلقائيًا إلى البداية بمجرد انتهاء تشغيل الفيلم.<br/>            قراءة/كتابة **bool**. |
| [`play_loop_mode`](/slides/python-net/ar/aspose.slides/videoframe/play_loop_mode/) | يحدد ما إذا كان الفيديو متكررًا (مكررًا).<br/>            قراءة/كتابة **bool**. |
| [`hide_at_showing`](/slides/python-net/ar/aspose.slides/videoframe/hide_at_showing/) | يحدد ما إذا كان VideoFrame مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`volume`](/slides/python-net/ar/aspose.slides/videoframe/volume/) | يعيد أو يضبط حجم الصوت.<br/>            قراءة/كتابة [`AudioVolumeMode`](/slides/python-net/ar/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ar/aspose.slides/videoframe/play_mode/) | يعيد أو يضبط وضع تشغيل الفيديو.<br/>            قراءة/كتابة [`VideoPlayModePreset`](/slides/python-net/ar/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ar/aspose.slides/videoframe/full_screen_mode/) | يحدد ما إذا كان الفيديو يُعرض في وضع ملء الشاشة.<br/>            قراءة/كتابة **bool**. |
| [`link_path_long`](/slides/python-net/ar/aspose.slides/videoframe/link_path_long/) | يعيد أو يضبط اسم ملف الفيديو المرتبط ب VideoFrame.<br/>            قراءة/كتابة **str**. |
| [`embedded_video`](/slides/python-net/ar/aspose.slides/videoframe/embedded_video/) | يعيد أو يضبط كائن الفيديو المدمج.<br/>            قراءة/كتابة [`IVideo`](/slides/python-net/ar/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ar/aspose.slides/videoframe/trim_from_start/) | بداية القص [ms] |
| [`trim_from_end`](/slides/python-net/ar/aspose.slides/videoframe/trim_from_end/) | نهاية القص [ms] |
| [`caption_tracks`](/slides/python-net/ar/aspose.slides/videoframe/caption_tracks/) | يحصل على مجموعة العناوين الفرعية المغلقة المرتبطة بإطار الفيديو.<br/>             هذه الخاصية قراءة فقط وتعيد [`ICaptionsCollection`](/slides/python-net/ar/aspose.slides/icaptionscollection) يحتوي على جميع مسارات التسمية. |

## الطرق

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يتم استخدام نوع حدود صورة مصغرة الشكل ShapeThumbnailBounds.Shape كافتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/videoframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/videoframe/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/videoframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (الشكل من التخطيط و/أو شريحة القالب التي يرث منها الشكل الحالي).<br/>            يُعاد None إذا لم يكن الشكل الحالي مُورَّثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواها المُعرض. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_geometry_paths/#) | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | يحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/videoframe/create_shape_elements/#) | ينشئ ويعيد مصفوفة من عناصر الشكل. |

### انظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)