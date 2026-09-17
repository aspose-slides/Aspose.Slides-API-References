---
title: AudioFrame class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/audioframe/
---
## AudioFrame الفئة

يمثل مقطع صوتي على شريحة.

**الوراثة:**[`AudioFrame`](/slides/python-net/ar/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع AudioFrame يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/audioframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/> قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/audioframe/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن لل شكل عنصر نائب.<br/> قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/audioframe/custom_data/) | يعيد البيانات المخصصة للشكل.<br/> قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/audioframe/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/> قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/audioframe/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/> قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/audioframe/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/> ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/> قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/audioframe/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/> ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/> قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/audioframe/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/> ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/> قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/audioframe/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/> ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/> قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/audioframe/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/> قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/audioframe/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير فوق الماوس.<br/> قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/audioframe/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/> قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/audioframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/> قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/audioframe/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/> Shapes[0] يعيد الشكل في خلفية ترتيب z،<br/> و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/> قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/audioframe/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/> قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/audioframe/rotation/) | يعيد أو يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول محور z.<br/> القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/> قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/audioframe/x/) | يحصل أو يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/audioframe/y/) | يحصل أو يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/audioframe/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/audioframe/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/audioframe/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضعية اللونين الأسود والأبيض..<br/> قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/audioframe/unique_id/) | يعيد معرفًا داخليًا، نطاقه العرض التقديمي، مخصص للاستخدام من قبل الإضافات أو أي كود آخر.<br/> نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها<br/> مفتاحًا فريدًا دائمًا.<br/> قراءة فقط **int**.<br/> انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/audioframe/office_interop_shape_id/) | يعيد معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند.<br/> قراءة فقط **int**.<br/> انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/audioframe/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/> قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/audioframe/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/> قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/audioframe/name/) | يعيد أو يضبط اسم الشكل.<br/> يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/> قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/audioframe/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كزخرفة'<br/> قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/audioframe/shape_lock/) | يعيد أقفال الشكل.<br/> قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/audioframe/is_grouped/) | يحدد ما إذا كان الشكل ضمن مجموعة.<br/> قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/audioframe/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل ضمن مجموعة. وإلا يعيد None.<br/> قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/audioframe/slide/) | يعيد الشريحة الأب للشكل.<br/> قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/audioframe/presentation/) | يعيد العرض التقديمي الأب للشريحة.<br/> قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ar/aspose.slides/audioframe/shape_style/) | يعيد كائن نمط الشكل.<br/> قراءة فقط [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/audioframe/shape_type/) | يعيد أو يضبط نوع AutoShape لإطار الصورة.<br/> هناك جميع العناصر المسموح بها في المجموعة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)، <br/> باستثناء جميع أنواع الخطوط:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/> قراءة/كتابة [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/audioframe/adjustments/) | يعيد مجموعة من قيم تعديل الشكل.<br/> قراءة فقط [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ar/aspose.slides/audioframe/picture_frame_lock/) | يعيد أقفال الشكل.<br/> قراءة فقط [`IPictureFrameLock`](/slides/python-net/ar/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ar/aspose.slides/audioframe/picture_format/) | يعيد كائن PictureFillFormat لإطار الصورة.<br/> قراءة فقط [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ar/aspose.slides/audioframe/relative_scale_height/) | يعيد أو يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪.<br/> قراءة/كتابة **float**. |
| [`relative_scale_width`](/slides/python-net/ar/aspose.slides/audioframe/relative_scale_width/) | يعيد أو يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪.<br/> قراءة/كتابة **float**. |
| [`is_cameo`](/slides/python-net/ar/aspose.slides/audioframe/is_cameo/) | يحدد ما إذا كان PictureFrame هو كائن Cameo أم لا.<br/> قراءة فقط **bool**. |
| [`audio_cd_start_track`](/slides/python-net/ar/aspose.slides/audioframe/audio_cd_start_track/) | يعيد أو يضبط فهرس مسار البداية.<br/> قراءة/كتابة **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/ar/aspose.slides/audioframe/audio_cd_start_track_time/) | يعيد أو يضبط وقت مسار البداية.<br/> قراءة/كتابة **int**. |
| [`audio_cd_end_track`](/slides/python-net/ar/aspose.slides/audioframe/audio_cd_end_track/) | يعيد أو يضبط فهرس المسار الأخير<br/> قراءة/كتابة **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/ar/aspose.slides/audioframe/audio_cd_end_track_time/) | يعيد أو يضبط وقت المسار الأخير.<br/> قراءة/كتابة **int**. |
| [`volume`](/slides/python-net/ar/aspose.slides/audioframe/volume/) | يعيد أو يضبط حجم الصوت.<br/> قراءة/كتابة [`AudioVolumeMode`](/slides/python-net/ar/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ar/aspose.slides/audioframe/play_mode/) | يعيد أو يضبط وضع تشغيل الصوت.<br/> قراءة/كتابة [`AudioPlayModePreset`](/slides/python-net/ar/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/ar/aspose.slides/audioframe/hide_at_showing/) | يحدد ما إذا كان AudioFrame مخفيًا.<br/> قراءة/كتابة **bool**. |
| [`play_loop_mode`](/slides/python-net/ar/aspose.slides/audioframe/play_loop_mode/) | يحدد ما إذا كان الصوت متكررًا.<br/> قراءة/كتابة **bool**. |
| [`play_across_slides`](/slides/python-net/ar/aspose.slides/audioframe/play_across_slides/) | يحدد ما إذا كان الصوت يُشغل عبر الشرائح.<br/> قراءة/كتابة **bool**. |
| [`rewind_audio`](/slides/python-net/ar/aspose.slides/audioframe/rewind_audio/) | يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل.<br/> قراءة/كتابة **bool**. |
| [`embedded`](/slides/python-net/ar/aspose.slides/audioframe/embedded/) | يحدد ما إذا كان الصوت مدمجًا في العرض التقديمي.<br/> قراءة فقط **bool**. |
| [`link_path_long`](/slides/python-net/ar/aspose.slides/audioframe/link_path_long/) | يعيد أو يضبط اسم ملف الصوت المرتبط بـ AudioFrame.<br/> قراءة/كتابة **str**. |
| [`embedded_audio`](/slides/python-net/ar/aspose.slides/audioframe/embedded_audio/) | يعيد أو يضبط كائن الصوت المدمج.<br/> قراءة/كتابة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/ar/aspose.slides/audioframe/fade_in_duration/) | يحدد مدة الوقت للظهور التلاشي الأولي للوسائط بالملي ثانية.<br/> قراءة/كتابة **float**. |
| [`fade_out_duration`](/slides/python-net/ar/aspose.slides/audioframe/fade_out_duration/) | يحدد مدة الوقت للانتهاء من التلاشي للوسائط بالملي ثانية.<br/> قراءة/كتابة **float**. |
| [`volume_value`](/slides/python-net/ar/aspose.slides/audioframe/volume_value/) | يعيد أو يضبط حجم الصوت بالنسبة المئوية.<br/> قراءة/كتابة **float**. |
| [`trim_from_start`](/slides/python-net/ar/aspose.slides/audioframe/trim_from_start/) | يحدد مدة الوقت لإزالتها من بداية الوسائط أثناء التشغيل، بالملي ثانية.<br/> قراءة/كتابة **float**. |
| [`trim_from_end`](/slides/python-net/ar/aspose.slides/audioframe/trim_from_end/) | يحدد مدة الوقت لإزالتها من نهاية الوسائط أثناء التشغيل، بالملي ثانية.<br/> قراءة/كتابة **float**. |
| [`caption_tracks`](/slides/python-net/ar/aspose.slides/audioframe/caption_tracks/) | يحصل على مجموعة الشروح المغلقة المرتبطة بإطار الصوت.<br/> هذه الخاصية قراءة فقط وتعيد [`ICaptionsCollection`](/slides/python-net/ar/aspose.slides/icaptionscollection) يحتوي على جميع مسارات الشرح. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/audioframe/get_image/#) | يعيد صورة مصغرة للشكل.<br/> يتم استخدام نوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/audioframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/audioframe/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/audioframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/audioframe/get_base_placeholder/#) | يعيد شكلًا عنصرًا نائبًا أساسيًا (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).<br/> يعاد None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/audioframe/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/audioframe/get_geometry_paths/#) | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل.<br/> يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | يحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل.<br/> يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/audioframe/create_shape_elements/#) | ينشئ ويعيد مصفوفة من عناصر الشكل. |

### انظر أيضًا
* الفئة [`AudioFrame`](/slides/python-net/ar/aspose.slides/audioframe)
* الفئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* الفئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)