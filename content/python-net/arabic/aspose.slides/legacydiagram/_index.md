---
title: LegacyDiagram class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/legacydiagram/
---
## LegacyDiagram فئة

يمثل كائن مخطط قديم.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/ar/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

يُظهر نوع LegacyDiagram الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/legacydiagram/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/> قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/legacydiagram/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/> للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/legacydiagram/custom_data/) | يعيد البيانات المخصّصة للشكل.<br/> للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/legacydiagram/raw_frame/) | يعيد أو يعيّن خصائص إطار الشكل الخام.<br/> قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/legacydiagram/frame/) | يعيد أو يعيّن خصائص إطار الشكل.<br/> قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/legacydiagram/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/> ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص الخط.<br/> للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/legacydiagram/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد للشكل.<br/> ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/> للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/legacydiagram/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل.<br/> ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص التأثير.<br/> للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/legacydiagram/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/> ملاحظة: قد يُعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص التعبئة.<br/> للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/legacydiagram/hyperlink_click/) | يعيد أو يعيّن الارتباط التشعبي المحدد للنقر بالماوس.<br/> قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/legacydiagram/hyperlink_mouse_over/) | يعيد أو يعيّن الارتباط التشعبي المحدد للتمرير فوق الماوس.<br/> قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/legacydiagram/hyperlink_manager/) | يعيد مدير الارتباط التشعبي.<br/> للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/legacydiagram/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/> قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/legacydiagram/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/> Shapes[0] يعيد الشكل في خلفية ترتيب z،<br/> و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/> للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/legacydiagram/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/> للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/legacydiagram/rotation/) | يعيد أو يعيّن عدد الدرجات التي يتم تدوير الشكل المحدد حول محور z.<br/> القيمة الموجبة تشير إلى الدوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى الدوران عكس اتجاه عقارب الساعة.<br/> قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/legacydiagram/x/) | يعيد أو يعيّن الإحداثي السيني للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/legacydiagram/y/) | يعيد أو يعيّن الإحداثي الصادي للزاوية العليا اليسرى للشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/legacydiagram/width/) | يعيد أو يعيّن عرض الشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/legacydiagram/height/) | يعيد أو يعيّن ارتفاع الشكل، مقاسًا بالنقاط.<br/> قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/legacydiagram/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود..<br/> قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/legacydiagram/unique_id/) | يعيد معرفًا داخليًا يخص العرض التقديمي موجهًا لاستخدام الإضافات أو أي كود آخر.<br/> لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا.<br/> للقراءة فقط **int**.<br/> انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/legacydiagram/office_interop_shape_id/) | يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل و<br/> يتيح لـ PowerPoint أو كود التفاعل الإشارة إلى الشكل بثقة من أي مكان في المستند.<br/> للقراءة فقط **int**.<br/> انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/legacydiagram/alternative_text/) | يعيد أو يعيّن النص البديل المرتبط بالشكل.<br/> قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/legacydiagram/alternative_text_title/) | يعيد أو يعيّن عنوان النص البديل المرتبط بالشكل.<br/> قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/legacydiagram/name/) | يعيد أو يعيّن اسم الشكل.<br/> يجب ألا يكون None. استخدم قيمة سلسلة فارغة إذا لزم الأمر.<br/> قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/legacydiagram/is_decorative/) | يعيد أو يعيّن خيار 'وضع علامة كديكور'<br/> Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/legacydiagram/shape_lock/) | يعيد أقفال الشكل.<br/> للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/legacydiagram/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/> للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/legacydiagram/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجمعًا. وإلا يعيد None.<br/> للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/legacydiagram/slide/) | يعيد الشريحة الأم للشكل.<br/> للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/legacydiagram/presentation/) | يعيد العرض التقديمي الأب للشرائح.<br/> للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/legacydiagram/graphical_object_lock/) | يعيد أقفال الشكل.<br/> للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/get_image/#) | يعيد صورة مصغرة للشكل.<br/> يُستخدم نوع ShapeThumbnailBounds.Shape لتحديد حدود الصورة المصغرة بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن هناك ويضبط خصائص العنصر النائب إلى المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/get_base_placeholder/#) | يعيد شكلًا أساسيًا عنصرًا نائبًا (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).<br/> يُرجَع None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/get_visual_bounds/#) | يعيد حدود الشكل المرئية المحسوبة من محتواه المُعرض. |
| [`convert_to_smart_art(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/convert_to_smart_art/#) | يحوّل المخطط القديم إلى كائن SmartArt قابل للتحرير.<br/> يُضاف كائن SmartArt المُنشأ إلى مجموعة الشكل الأصلية في نفس الموضع. |
| [`convert_to_group_shape(self)`](/slides/python-net/ar/aspose.slides/legacydiagram/convert_to_group_shape/#) | يحوّل المخطط القديم إلى مجموعة أشكال قابلة للتحرير.<br/> يُضاف كائن GroupShape المُنشأ إلى مجموعة الشكل الأصلية في نفس الموضع. |

### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`LegacyDiagram`](/slides/python-net/ar/aspose.slides/legacydiagram)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)