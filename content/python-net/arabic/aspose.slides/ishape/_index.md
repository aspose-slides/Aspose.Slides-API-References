---
title: IShape class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishape/
---
## IShape فئة

يمثل شكلاً على شريحة.

نوع IShape يظهر الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/ishape/is_text_holder/) | يحدد ما إذا كان الشكل هو TextHolder.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/ishape/placeholder/) | يعيد العنصر النائب (placeholder) للشكل.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/ishape/custom_data/) | يعيد البيانات المخصصة للشكل.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/ishape/raw_frame/) | يعيد أو يضبط خصائص إطار الشكل الخام.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/ishape/frame/) | يعيد أو يضبط خصائص إطار الشكل.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/ishape/line_format/) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/ishape/three_d_format/) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/ishape/effect_format/) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/ishape/fill_format/) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/ar/aspose.slides/ishape/hidden/) | يحدد ما إذا كان الشكل مخفيًا.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/ishape/z_order_position/) | يعيد موضع الشكل في ترتيب z.<br/>            Shapes[0] يعيد الشكل في خلفية ترتيب z،<br/>            و Shapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/ishape/connection_site_count/) | يعيد عدد مواقع الاتصال على الشكل.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/ishape/rotation/) | يعيد أو يضبط عدد الدرجات التي يتم تدوير الشكل المحدد حول محور z.<br/>            القيمة الموجبة تشير إلى دوران عقارب الساعة؛ القيمة السلبية تشير إلى دوران عكس عقارب الساعة.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/ishape/x/) | يحصل أو يضبط الإحداثي x لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/ishape/y/) | يحصل أو يضبط الإحداثي y لزاوية الشكل العلوية اليسرى، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/ishape/width/) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/ishape/height/) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط.<br/>            قراءة/كتابة **float**. |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/ishape/alternative_text/) | يعيد أو يضبط النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/ishape/alternative_text_title/) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/ishape/name/) | يعيد أو يضبط اسم الشكل.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/ishape/is_decorative/) | يحصل أو يضبط خيار 'تمييز كديكور'<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/ishape/shape_lock/) | يعيد أقفال الشكل.<br/>            قراءة فقط [`IBaseShapeLock`](/slides/python-net/ar/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/ishape/unique_id/) | يعيد معرفًا داخليًا ذو نطاق عرض تقديمي مخصص للاستخدام من قبل الإضافات أو كود آخر.<br/>            بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب ألا تُعامل<br/>            كمفتاح فريد دائم.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`IShape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/ishape/office_interop_shape_id/) | يعيد معرفًا فريدًا ذو نطاق شريحة يظل ثابتًا طوال عمر الشكل ويتيح لـ PowerPoint أو كود التفاعل الإشاري الإشارة إلى الشكل من أي مكان في المستند.<br/>            قراءة فقط **int**.<br/>            انظر أيضًا [`IShape.unique_id`](/slides/python-net/ar/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/ishape/is_grouped/) | يحدد ما إذا كان الشكل مجموعة.<br/>            قراءة فقط **bool**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/ishape/black_white_mode/) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود.<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/ar/aspose.slides/ishape/parent_group/) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يعيد None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/ishape/hyperlink_manager/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/ishape/get_image/#) | يعيد صورة مصغرة للشكل.<br/>            يُستخدم النوع ShapeThumbnailBounds.Shape كنوع حدود الصورة المصغرة للشكل بشكل افتراضي. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | يعيد صورة مصغرة للشكل. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/ishape/write_as_svg/#iorawiobase) | يحفظ محتوى الشكل كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشكل كملف SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/ishape/add_placeholder/#iplaceholder) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/ishape/remove_placeholder/#) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/ishape/get_base_placeholder/#) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).<br/>            يتم إرجاع None إذا لم يكن الشكل الحالي موروثًا. |


### أنظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)