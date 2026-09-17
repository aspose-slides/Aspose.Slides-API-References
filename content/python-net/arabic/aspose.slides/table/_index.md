---
title: Table class
second_title: Aspose.Slides للبرمجة بلغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/table/
---
## فئة Table

يمثل جدولًا على الشريحة.

**Inheritance:**[`Table`](/slides/python-net/ar/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

نوع Table يعرّض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/table/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder_PPT.<br/>            للقراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/table/placeholder/) | يعيد العنصر النائب للشكل. يعيد None إذا لم يكن للشكل عنصر نائب.<br/>            للقراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/table/custom_data/) | يعيد بيانات مخصصة للشكل.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/table/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/table/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/table/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص خط.<br/>            للقراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/table/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل.<br/>            ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد.<br/>            للقراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/table/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            ملاحظة: قد يعيد None لبعض أنواع الأشكال التي لا تمتلك خصائص تأثير.<br/>            للقراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/table/fill_format/) | يعيد كائن TableFormat.FillFormat يحتوي على تنسيق التعبئة للجدول.<br/>            للقراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/table/hyperlink_click/) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/table/hyperlink_mouse_over/) | يعيد أو يضبط الارتباط التشعبي المحدد لتجاوز الماوس.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/table/hyperlink_manager/) | يعيد مدير الارتباطات التشعبية.<br/>            للقراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/table/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/table/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في الخلفية،<br/>            وShapes[Shapes.Count - 1] يعيد الشكل في المقدمة.<br/>            للقراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/table/connection_site_count/) | يعيد عدد نقاط الاتصال على الشكل.<br/>            للقراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/table/rotation/) | يعيد أو يضبط عدد درجات تدوير الشكل حول محور z.<br/>            القيمة الموجبة تشير إلى تدوير باتجاه عقارب الساعة؛ والقيمة السالبة تشير إلى تدوير عكس اتجاه العقارب.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/table/x/) | يحصل أو يضبط إحداثي x لزاوية الشكل العلوية اليسرى، مقاسة بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/table/y/) | يحصل أو يضبط إحداثي y لزاوية الشكل العلوية اليسرى، مقاسة بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/table/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/table/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/table/black_white_mode/) | الخاصية تحدد كيف سيُظهر الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/table/unique_id/) | يعيد معرفًا داخليًا خاصًا بالعرض مخصصًا للاستخدام من قِبل الإضافات أو الشيفرات الأخرى.<br/>            لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب ألا تُعامل كمفتاح فريد دائم.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/table/office_interop_shape_id/) | يعيد معرفًا فريدًا خاصًا بالشرائح يظل ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو شفرة التفاعل بالإشارة إلى الشكل من أي مكان في المستند.<br/>            للقراءة فقط **int**.<br/>            انظر أيضًا [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/table/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/table/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/table/name/) | يعيد أو يضبط اسم الشكل.<br/>            يجب ألا يكون None. استخدم سلسلة فارغة إذا لزم الأمر.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/table/is_decorative/) | يحصل أو يضبط خيار 'التصميم كديكور'.<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/table/shape_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/table/is_grouped/) | يحدد ما إذا كان الشكل ضمن مجموعة.<br/>            للقراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/table/parent_group/) | يعيد كائن GroupShape الأصل إذا كان الشكل ضمن مجموعة. وإلا يعيد None.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/table/slide/) | يعيد الشريحة الأصلية للشكل.<br/>            للقراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/table/presentation/) | يعيد العرض الأصلي للشرحة.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ar/aspose.slides/table/graphical_object_lock/) | يعيد أقفال الشكل.<br/>            للقراءة فقط [`IGraphicalObjectLock`](/slides/python-net/ar/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/ar/aspose.slides/table/rows/) | يعيد مجموعة الصفوف.<br/>            للقراءة فقط [`IRowCollection`](/slides/python-net/ar/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/ar/aspose.slides/table/columns/) | يعيد مجموعة الأعمدة.<br/>            للقراءة فقط [`IColumnCollection`](/slides/python-net/ar/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/ar/aspose.slides/table/table_format/) | يعيد كائن TableFormat الذي يحتوي على خصائص تنسيق هذا الجدول.<br/>            للقراءة فقط [`ITableFormat`](/slides/python-net/ar/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/ar/aspose.slides/table/style_preset/) | يحصل أو يضبط نمط الجدول المدمج.<br/>            قراءة/كتابة [`TableStylePreset`](/slides/python-net/ar/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/ar/aspose.slides/table/right_to_left/) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار.<br/>            قراءة/كتابة **bool**. |
| [`first_row`](/slides/python-net/ar/aspose.slides/table/first_row/) | يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص.<br/>            قراءة/كتابة **bool**. |
| [`first_col`](/slides/python-net/ar/aspose.slides/table/first_col/) | يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص.<br/>            قراءة/كتابة **bool**. |
| [`last_row`](/slides/python-net/ar/aspose.slides/table/last_row/) | يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص.<br/>            قراءة/كتابة **bool**. |
| [`last_col`](/slides/python-net/ar/aspose.slides/table/last_col/) | يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص.<br/>            قراءة/كتابة **bool**. |
| [`horizontal_banding`](/slides/python-net/ar/aspose.slides/table/horizontal_banding/) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف.<br/>            قراءة/كتابة **bool**. |
| [`vertical_banding`](/slides/python-net/ar/aspose.slides/table/vertical_banding/) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف.<br/>            قراءة/كتابة **bool**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/table/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يتم استخدام نوع ShapeThumbnailBounds.Shape لحدود الصورة المصغرة بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/table/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`set_text_format(self, source)`](/slides/python-net/ar/aspose.slides/table/set_text_format/#iportionformat) | يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء خلايا الجدول. |
| [`set_text_format(self, source)`](/slides/python-net/ar/aspose.slides/table/set_text_format/#iparagraphformat) | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات خلايا الجدول. |
| [`set_text_format(self, source)`](/slides/python-net/ar/aspose.slides/table/set_text_format/#itextframeformat) | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات نص خلايا الجدول. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/table/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/table/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/table/get_base_placeholder/#) | يعيد شكلًا نائبًا أساسيًا (شكل من التخطيط و/أو الشريحة الرئيسة التي يرث منها الشكل الحالي).<br/>            يعيد None إذا لم يكن الشكل الحالي موروثًا. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/table/get_visual_bounds/#) | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/ar/aspose.slides/table/merge_cells/#icell-icell-bool) | يدمج الخلايا المجاورة. |

### انظر أيضًا
* الفئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الفئة [`Table`](/slides/python-net/ar/aspose.slides/table)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)