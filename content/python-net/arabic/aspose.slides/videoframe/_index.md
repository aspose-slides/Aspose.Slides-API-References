---
title: VideoFrame class
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/videoframe/
---
## فئة VideoFrame

Represents a video clip on a slide.

**Inheritance:**[`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

The VideoFrame type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/videoframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/videoframe/placeholder/) | يُرجِع العنصر النائب للشكل. يُرجِع None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/videoframe/custom_data/) | يُرجِع البيانات المخصَّصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/videoframe/raw_frame/) | يُرجِع أو يُعيّن خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/videoframe/frame/) | يُرجِع أو يُعيّن خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/videoframe/line_format/) | يُرجِع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: يمكن أن يُرجِع None لأنواع معينة من الأشكال التي لا تملك خصائص خط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/videoframe/three_d_format/) | يُرجِع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: يمكن أن يُرجِع None لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/videoframe/effect_format/) | يُرجِع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: يمكن أن يُرجِع None لأنواع معينة من الأشكال التي لا تملك خصائص تأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/videoframe/fill_format/) | يُرجِع كائن FillFormat الذي يحتوي على خصائص تنسيق الملء للشكل.<br/>            ملاحظة: يمكن أن يُرجِع None لأنواع معينة من الأشكال التي لا تملك خصائص ملء.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_click/) | يُرجِع أو يُعيّن الرابط الفائق المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_mouse_over/) | يُرجِع أو يُعيّن الرابط الفائق المحدد لتمرير الماوس فوقه.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/videoframe/hyperlink_manager/) | يُرجِع مدير الروابط الفائقة.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/videoframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/videoframe/z_order_position/) | يُرجِع موقع الشكل في ترتيب المحور Z.<br/>            Shapes[0] تُرجِع الشكل في مؤخرة ترتيب Z،<br/>            و Shapes[Shapes.Count - 1] تُرجِع الشكل في مقدمة ترتيب Z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/videoframe/connection_site_count/) | يُرجِع عدد نقاط الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/videoframe/rotation/) | يُرجِع أو يُعيّن عدد الدرجات التي يُدوَّر بها الشكل المحدد حول محور Z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/videoframe/x/) | يُعيد أو يعيّن الإحداثي X للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/videoframe/y/) | يُعيد أو يعيّن الإحداثي Y للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/videoframe/width/) | يُعيد أو يعيّن عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/videoframe/height/) | يُعيد أو يعيّن ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/videoframe/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/videoframe/unique_id/) | يُرجِع معرفًا داخليًا يخص العرض ويُقصد به للاستخدام من قبل الإضافات أو الشيفرات الأخرى.<br/>            نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا مستمرًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/videoframe/office_interop_shape_id/) | يُرجِع معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل و<br/>            يتيح لبرنامج PowerPoint أو شفرة التفاعل الإشارة إلى الشكل من أي مكان في المستند بثقة.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/videoframe/alternative_text/) | يُرجِع أو يُعيّن النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/videoframe/alternative_text_title/) | يُرجِع أو يُعيّن عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/videoframe/name/) | يُرجِع أو يُعيّن اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/videoframe/is_decorative/) | يُعيد أو يُعيّن خيار 'تمييز كزخرفية'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/videoframe/shape_lock/) | يُرجِع أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/videoframe/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/videoframe/parent_group/) | يُرجِع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُرجِع None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/videoframe/slide/) | يُرجِع الشريحة الأب للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/videoframe/presentation/) | يُرجِع العرض الأب للشرائح.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/videoframe/shape_style/) | يُرجِع كائن نمط الشكل.<br/>            قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/videoframe/shape_type/) | يُرجِع أو يُعيّن نوع AutoShape لإطار الصورة.<br/>            جميع العناصر المسموح بها في مجموعة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) متاحة، <br/>            باستثناء جميع أنواع الخطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/videoframe/adjustments/) | يُرجِع مجموعةً من قيم تعديل الشكل.<br/>            قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ar/aspose.slides/videoframe/picture_frame_lock/) | يُرجِع أقفال الشكل.<br/>            قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ar/aspose.slides/videoframe/picture_format/) | يُرجِع كائن PictureFillFormat لإطار الصورة.<br/>            قراءة فقط [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ar/aspose.slides/videoframe/relative_scale_height/) | يُرجِع أو يُعيّن مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪.<br/>            قراءة/كتابة **float**. |
| [`relative_scale_width`](/slides/python-net/ar/aspose.slides/videoframe/relative_scale_width/) | يُرجِع أو يُعيّن مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪.<br/>            قراءة/كتابة **float**. |
| [`is_cameo`](/slides/python-net/ar/aspose.slides/videoframe/is_cameo/) | يحدد ما إذا كان إطار الصورة كائن Cameo أم لا.<br/>            قراءة فقط **bool**. |
| [`rewind_video`](/slides/python-net/ar/aspose.slides/videoframe/rewind_video/) | يحدد ما إذا كان الفيديو يُعيد تشغيله تلقائيًا إلى البداية<br/>            بمجرد انتهاء تشغيل الفيلم.<br/>            قراءة/كتابة **bool**. |
| [`play_loop_mode`](/slides/python-net/ar/aspose.slides/videoframe/play_loop_mode/) | يحدد ما إذا كان الفيديو يُعاد تشغيله بشكل متكرر.<br/>            قراءة/كتابة **bool**. |
| [`hide_at_showing`](/slides/python-net/ar/aspose.slides/videoframe/hide_at_showing/) | يحدد ما إذا كان إطار الفيديو مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`volume`](/slides/python-net/ar/aspose.slides/videoframe/volume/) | يُرجِع أو يُعيّن مستوى صوت الصوت.<br/>            قراءة/كتابة [`AudioVolumeMode`](/slides/python-net/ar/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/ar/aspose.slides/videoframe/volume_value/) | يُرجِع أو يُعيّن مستوى صوت الفيديو الدقيق كنسبة مئوية.<br/>             تُعبّر القيمة كنسبة مئوية من 0 إلى 100. استخدم هذه الخاصية<br/>             لقراءة أو تعيين قيم الصوت بدقة أكبر من المستويات predefined المتاحة عبر الخاصية [`VideoFrame.volume`](/slides/python-net/ar/aspose.slides/videoframe/volume).<br/>             قراءة/كتابة **float**. |
| [`play_mode`](/slides/python-net/ar/aspose.slides/videoframe/play_mode/) | يُرجِع أو يُعيّن وضع تشغيل الفيديو.<br/>            قراءة/كتابة [`VideoPlayModePreset`](/slides/python-net/ar/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ar/aspose.slides/videoframe/full_screen_mode/) | يحدد ما إذا تم عرض الفيديو في وضع ملء الشاشة.<br/>            قراءة/كتابة **bool**. |
| [`link_path_long`](/slides/python-net/ar/aspose.slides/videoframe/link_path_long/) | يُرجِع أو يُعيّن اسم ملف الفيديو المرتبط بإطار الفيديو.<br/>            قراءة/كتابة **str**. |
| [`embedded_video`](/slides/python-net/ar/aspose.slides/videoframe/embedded_video/) | يُرجِع أو يُعيّن كائن الفيديو المضمن.<br/>            قراءة/كتابة [`IVideo`](/slides/python-net/ar/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ar/aspose.slides/videoframe/trim_from_start/) | تقليم البداية [مللي ثانية] |
| [`trim_from_end`](/slides/python-net/ar/aspose.slides/videoframe/trim_from_end/) | تقليم النهاية [مللي ثانية] |
| [`caption_tracks`](/slides/python-net/ar/aspose.slides/videoframe/caption_tracks/) | يُعيد مجموعة الترجمات المغلقة المرتبطة بإطار الفيديو.<br/>             هذه الخاصية قراءة فقط وتُرجِع [`ICaptionsCollection`](/slides/python-net/ar/aspose.slides/icaptionscollection) يحتوي على جميع مسارات الترجمة. |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_image/#) | يُرجِع الصورة المصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة للشكل كإعداد افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | يُرجِع الصورة المصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/videoframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/videoframe/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/videoframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويعيّن خصائص العنصر النائب إلى ما هو محدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_base_placeholder/#) | يُرجِع شكلًا عنصرًا نائبًا أساسيًا (شكل من التخطيط و/أو شريحة القالب التي يرث منها الشكل الحالي).<br/>            يُرجِع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_visual_bounds/#) | يُحصل على حدود الشكل البصرية المحسوبة من محتواه المُرَسَم. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/videoframe/get_geometry_paths/#) | يُرجِع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية اليسرى العليا للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | يُحدِّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى<br/>             العليا للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | يُحدِّث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية للزاوية اليسرى<br/>             العليا للشكل.<br/>             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/videoframe/create_shape_elements/#) | ينشئ ويُرجِع مصفوفة من عناصر الشكل. |

### انظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)