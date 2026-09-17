---
title: SmartArt class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.smartart/smartart/
---
## فئة SmartArt

يمثل مخطط SmartArt

**الوراثة:**[`SmartArt`](/slides/python-net/ar/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع SmartArt يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides.smartart/smartart/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides.smartart/smartart/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides.smartart/smartart/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides.smartart/smartart/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides.smartart/smartart/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            للقراءة والكتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides.smartart/smartart/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: يمكن أن يُعيد None لبعض أنواع الأشكال التي لا تملك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides.smartart/smartart/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: يمكن أن يُعيد None لبعض أنواع الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides.smartart/smartart/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على شكل.<br/>            ملاحظة: يمكن أن يُعيد None لبعض أنواع الأشكال التي لا تملك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides.smartart/smartart/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: يمكن أن يُعيد None لبعض أنواع الأشكال التي لا تملك خصائص تعبئة.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides.smartart/smartart/hyperlink_click/) | يعيد أو يضبط الرابط التشعبي المحدد للنقر بالفأرة.<br/>            للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | يعيد أو يضبط الرابط التشعبي المحدد عند مرور الفأرة.<br/>            للقراءة والكتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides.smartart/smartart/hyperlink_manager/) | يعيد مدير الروابط التشعبية.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides.smartart/smartart/hidden/) | يحدد ما إذا كان الشكل مخفياً.<br/>            للقراءة والكتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides.smartart/smartart/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يُعيد الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يُعيد الشكل في مقدمة ترتيب z.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides.smartart/smartart/connection_site_count/) | يعيد عدد نقاط الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides.smartart/smartart/rotation/) | يعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة.<br/>            للقراءة والكتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides.smartart/smartart/x/) | يُحصل أو يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.smartart/smartart/y/) | يُحصل أو يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.smartart/smartart/width/) | يُحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.smartart/smartart/height/) | يُحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            للقراءة والكتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides.smartart/smartart/black_white_mode/) | تحدد الخاصية كيفية عرض الشكل في وضع العرض بالأبيض والأسود..<br/>            للقراءة والكتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides.smartart/smartart/unique_id/) | يعيد معرفًا داخليًا يقتصر على العرض مخصصًا للاستخدام من قبل الإضافات أو الشيفرة الأخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا ينبغي اعتبارها مفتاحًا فريدًا دائمًا.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides.smartart/smartart/office_interop_shape_id/) | يعيد معرفًا فريدًا مقيدًا بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides.smartart/smartart/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            للقراءة والكتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides.smartart/smartart/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            للقراءة والكتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides.smartart/smartart/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            للقراءة والكتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides.smartart/smartart/is_decorative/) | يحصل أو يضبط خيار 'وضع علامة كزخرف'<br/>            للقراءة والكتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides.smartart/smartart/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides.smartart/smartart/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides.smartart/smartart/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides.smartart/smartart/slide/) | يعيد الشريحة الأم للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides.smartart/smartart/presentation/) | يعيد العرض الأم للشريحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides.smartart/smartart/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/ar/aspose.slides.smartart/smartart/all_nodes/) | يعيد مجموعات جميع العقد في كائن SmartArt.<br/>            للقراءة فقط [`ISmartArtNodeCollection`](/slides/python-net/ar/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/ar/aspose.slides.smartart/smartart/nodes/) | يعيد مجموعات عقد الجذر في كائن SmartArt.<br/>            للقراءة فقط [`ISmartArtNodeCollection`](/slides/python-net/ar/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/ar/aspose.slides.smartart/smartart/layout/) | يعيد أو يضبط تخطيط كائن SmartArt.<br/>            للقراءة والكتابة [`SmartArtLayoutType`](/slides/python-net/ar/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/ar/aspose.slides.smartart/smartart/quick_style/) | يعيد أو يضبط النمط السريع لكائن SmartArt.<br/>            للقراءة والكتابة [`SmartArtQuickStyleType`](/slides/python-net/ar/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/ar/aspose.slides.smartart/smartart/color_style/) | يعيد أو يضبط نمط اللون لكائن SmartArt.<br/>            للقراءة والكتابة [`SmartArtColorType`](/slides/python-net/ar/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/ar/aspose.slides.smartart/smartart/is_reversed/) | يعيد أو يضبط حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس.<br/>            للقراءة والكتابة **bool**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides.smartart/smartart/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape لتحديد حدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides.smartart/smartart/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides.smartart/smartart/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي).<br/>            يُعيد None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides.smartart/smartart/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم. |

### انظر أيضا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* فئة [`SmartArt`](/slides/python-net/ar/aspose.slides.smartart/smartart)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)