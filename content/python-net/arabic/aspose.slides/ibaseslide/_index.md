---
title: IBaseSlide class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ibaseslide/
---
## IBaseSlide فئة

يمثل البيانات المشتركة لجميع أنواع الشرائح.

يعرض نوع IBaseSlide الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/ibaseslide/shapes/) | إرجاع أشكال الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/ibaseslide/controls/) | إرجاع مجموعة عناصر التحكم ActiveX في الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/ibaseslide/name/) | إرجاع أو تعيين اسم الشريحة.<br/>            قابل للقراءة والكتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/ibaseslide/slide_id/) | إرجاع معرّف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/ibaseslide/custom_data/) | إرجاع البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/ibaseslide/timeline/) | إرجاع كائن جدول الزمن للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/ibaseslide/slide_show_transition/) | إرجاع كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/ibaseslide/background/) | إرجاع خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/ibaseslide/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/ibaseslide/show_master_shapes/) | يحدّد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا.<br/>            بالنسبة إلى الشريحة الرئيسية نفسها، تُعيد هذه الخاصية دائمًا `false`.<br/>            قابل للقراءة والكتابة **bool**. |
| [`slide`](/slides/python-net/ar/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/ibaseslide/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | يبحث عن أول حدوث لشكل يحتوي على النص البديل المحدد. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | يجمع النصوص المتتابعة ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/ibaseslide/equals/#ibaseslide) | يحدد ما إذا كانت مثاليْي IBaseSlide متساويين.<br/>            القيمة المرجعة محسوبة استنادًا إلى بنية الشريحة والمحتوى الثابت.<br/>            تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى... متساوية. المقارنة لا تأخذ في الاعتبار قيم المعرفات الفريدة، مثل SlideId، ولا المحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر النائب Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### انظر أيضاً
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)