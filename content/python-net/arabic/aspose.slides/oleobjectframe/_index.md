---
title: OleObjectFrame class
second_title: Aspose.Slides لـ Python عبر مرجع API لـ .NET
description: 
type: docs
url: /ar/aspose.slides/oleobjectframe/
---
## فئة OleObjectFrame

يمثل كائن OLE على شريحة.

**الوراثة:**[`OleObjectFrame`](/slides/python-net/ar/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض النوع OleObjectFrame الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/oleobjectframe/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/oleobjectframe/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/oleobjectframe/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/oleobjectframe/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/oleobjectframe/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/oleobjectframe/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: يمكن أن يعيد None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/oleobjectframe/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: يمكن أن يعيد None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/oleobjectframe/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: يمكن أن يعيد None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/oleobjectframe/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            ملاحظة: يمكن أن يعيد None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/oleobjectframe/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/oleobjectframe/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/oleobjectframe/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/oleobjectframe/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل الموجود في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل الموجود في مقدمة ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/oleobjectframe/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/oleobjectframe/rotation/) | يعيد أو يضبط عدد الدرجات التي يُدور بها الشكل المحدد حول المحور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى دوران عكس عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/oleobjectframe/x/) | يحصل أو يضبط الإحداثي x للزاوية العلوية اليسرى للشكل، المقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/oleobjectframe/y/) | يحصل أو يضبط الإحداثي y للزاوية العلوية اليسرى للشكل، المقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/oleobjectframe/width/) | يحصل أو يضبط عرض الشكل، المقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/oleobjectframe/height/) | يحصل أو يضبط ارتفاع الشكل، المقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/oleobjectframe/black_white_mode/) | الخاصية تحدد كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/oleobjectframe/unique_id/) | يعيد معرفًا داخليًا يخص العرض ومصمم للاستخدام من قبل الإضافات أو التعليمات البرمجية الأخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب ألا تُعامل<br/>            كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/oleobjectframe/office_interop_shape_id/) | يعيد معرفًا فريدًا يخص الشريحة يظل ثابتًا طوال عمر الشكل و<br/>            يتيح لبرنامج PowerPoint أو كود التفاعل الإشارة إلى الشكل بثقة من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/oleobjectframe/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/oleobjectframe/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/oleobjectframe/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/oleobjectframe/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كزينة'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/oleobjectframe/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/oleobjectframe/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/oleobjectframe/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/oleobjectframe/slide/) | يعيد الشريحة الأب للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/oleobjectframe/presentation/) | يعيد العرض الأب للشريحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/oleobjectframe/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/ar/aspose.slides/oleobjectframe/substitute_picture_format/) | يعيد كائن خصائص تعبئة صورة OleObject.<br/>            للقراءة فقط [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/ar/aspose.slides/oleobjectframe/substitute_picture_title/) | يعيد أو يضبط عنوان أيقونة OleObject.<br/>            قراءة/كتابة **str**. |
| [`object_name`](/slides/python-net/ar/aspose.slides/oleobjectframe/object_name/) | يعيد أو يضبط اسم الكائن.<br/>            قراءة/كتابة **str**. |
| [`object_prog_id`](/slides/python-net/ar/aspose.slides/oleobjectframe/object_prog_id/) | يعيد ProgID للكائن.<br/>            للقراءة فقط **str**. |
| [`link_file_name`](/slides/python-net/ar/aspose.slides/oleobjectframe/link_file_name/) | يعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف القصير.<br/>            للقراءة فقط **str**. |
| [`link_path_long`](/slides/python-net/ar/aspose.slides/oleobjectframe/link_path_long/) | يعيد المسار الكامل لملف مرتبط. سيتم استخدام اسم الملف الطويل.<br/>            قراءة/كتابة **str**. |
| [`link_path_relative`](/slides/python-net/ar/aspose.slides/oleobjectframe/link_path_relative/) | يعيد المسار النسبي لملف مرتبط إذا كان موجودًا، وإلا يعيد سلسلة فارغة.<br/>            للقراءة فقط **str**. |
| [`embedded_file_label`](/slides/python-net/ar/aspose.slides/oleobjectframe/embedded_file_label/) | يعيد اسم ملف كائن OLE المضمن |
| [`embedded_file_name`](/slides/python-net/ar/aspose.slides/oleobjectframe/embedded_file_name/) | يعيد مسار كائن OLE المضمن |
| [`embedded_data`](/slides/python-net/ar/aspose.slides/oleobjectframe/embedded_data/) | يحصل أو يضبط معلومات حول بيانات OLE المضمنة.<br/>            قراءة/كتابة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/ar/aspose.slides/oleobjectframe/is_object_icon/) | يحدد ما إذا كان الكائن مرئيًا كأيقونة.<br/>            قراءة/كتابة **bool**. |
| [`is_object_link`](/slides/python-net/ar/aspose.slides/oleobjectframe/is_object_link/) | يحدد ما إذا كان الكائن مرتبطًا بملف خارجي.<br/>            للقراءة فقط **bool**. |
| [`update_automatic`](/slides/python-net/ar/aspose.slides/oleobjectframe/update_automatic/) | يحدد ما إذا كان الكائن المضمن المرتبط يتم تحديثه تلقائيًا عند فتح العرض أو طباعته.<br/>            قراءة/كتابة **bool**. |

## الأساليب

| طريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/oleobjectframe/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية لحدود الصورة المصغرة. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/oleobjectframe/remove_placeholder/#) | يعرف أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/oleobjectframe/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي).<br/>            يُعاد None إذا لم يكن الشكل الحالي مورثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/oleobjectframe/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواه المُعرض. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/ar/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | يضبط معلومات حول بيانات OLE المضمنة.<br/>            <br/>            يغيّر هذا الأسلوب خصائص الكائن لتعكس البيانات الجديدة و <br/>            يضبط علم IsObjectLink إلى false، مما يدل على أن كائن OLE مضمّن. |

### انظر أيضًا
* الفئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* الفئة [`OleObjectFrame`](/slides/python-net/ar/aspose.slides/oleobjectframe)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)