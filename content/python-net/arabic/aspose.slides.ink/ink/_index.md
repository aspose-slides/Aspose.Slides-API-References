---
title: Ink class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ink/ink/
---
## فئة Ink

يمثل كائن حبر على شريحة.

**الوراثة:**[`Ink`](/slides/python-net/ar/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يعرض نوع Ink الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides.ink/ink/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides.ink/ink/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides.ink/ink/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides.ink/ink/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides.ink/ink/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides.ink/ink/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص خط.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides.ink/ink/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص ثلاثية الأبعاد.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides.ink/ink/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات بكسل مطبقة على الشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص تأثير.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides.ink/ink/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل.<br/>            ملاحظة: يمكن إرجاع None لأنواع معينة من الأشكال التي لا تملك خصائص تعبئة.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides.ink/ink/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد لنقر الفأرة.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides.ink/ink/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد لتحريك الفأرة فوقه.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides.ink/ink/hyperlink_manager/) | يعيد مدير الارتباطات التشعبية.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides.ink/ink/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides.ink/ink/z_order_position/) | يعيد موقع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides.ink/ink/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides.ink/ink/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم فيها تدوير الشكل المحدد حول محور z.<br/>            قيمة موجبة تشير إلى تدوير باتجاه عقارب الساعة؛ قيمة سالبة تشير إلى تدوير عكس اتجاه العقارب.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides.ink/ink/x/) | يحصل أو يضبط إحداثي x لزاوية الشكل العليا اليسرى، يُقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides.ink/ink/y/) | يحصل أو يضبط إحداثي y لزاوية الشكل العليا اليسرى، يُقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides.ink/ink/width/) | يحصل أو يضبط عرض الشكل، يُقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides.ink/ink/height/) | يحصل أو يضبط ارتفاع الشكل، يُقاس بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides.ink/ink/black_white_mode/) | الخاصية تحدد كيف سيُظهر الشكل في وضع العرض بالأبيض والأسود..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides.ink/ink/unique_id/) | يعيد معرفًا داخليًا يخص العرض ومخصّص للاستخدام من قبل الإضافات أو رموز أخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها<br/>            مفتاحًا فريدًا دائمًا.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides.ink/ink/office_interop_shape_id/) | يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويتيح لبرنامج PowerPoint أو رمز التفاعل الإشارة إلى الشكل بأمان من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides.ink/ink/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides.ink/ink/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides.ink/ink/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides.ink/ink/is_decorative/) | يحصل أو يضبط خيار 'Mark as decorative'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides.ink/ink/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides.ink/ink/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides.ink/ink/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides.ink/ink/slide/) | يعيد الشريحة الأب للشكل.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides.ink/ink/presentation/) | يعيد العرض الأب للشريحة.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides.ink/ink/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/ar/aspose.slides.ink/ink/traces/) | يحصل على جميع الآثار الموجودة في عنصر IInk [`IInkTrace`](/slides/python-net/ar/aspose.slides.ink/iinktrace).<br/>            قراءة فقط. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides.ink/ink/get_image/#) | يعيد الصورة المصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | يعيد الصورة المصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides.ink/ink/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن هناك ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides.ink/ink/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة الرئيسة التي يُورث منها الشكل الحالي).<br/>            يُرجع None إذا لم يكن الشكل الحالي مُورثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides.ink/ink/get_visual_bounds/#) | يحصل على حدود الشكل البصرية المحسوبة من محتواه المرسوم. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/ar/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | يسجل صورة في مجموعة الصور المخصصة المستخدمة لمحاكاة تأثيرات بصرية لفرش الحبر.<br/>            تُستخدم هذه الصور عند عرض الحبر بقيم [`InkEffectType`](/slides/python-net/ar/aspose.slides.ink/inkeffecttype) محددة،<br/>            مثل Galaxy، Rainbow، إلخ. من خلال توفير صورك الخاصة، يمكنك التحكم في مظهر كل تأثير حبر. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/ar/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | يُلغاء تسجيل صورة من مجموعة الصور المخصصة المستخدمة لمحاكاة تأثيرات بصرية لفرش الحبر<br/>            التي تم تسجيلها مسبقًا عبر **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`Ink`](/slides/python-net/ar/aspose.slides.ink/ink)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* المكتبة [`Aspose.Slides`](/slides/python-net)