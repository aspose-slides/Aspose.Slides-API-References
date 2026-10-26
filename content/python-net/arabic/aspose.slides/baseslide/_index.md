---
title: BaseSlide class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/baseslide/
---
## BaseSlide فئة

يمثل بيانات مشتركة لجميع أنواع الشرائح.

يظهر نوع BaseSlide الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/baseslide/shapes/) | يرجع أشكال الشريحة.<br/>            قراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/baseslide/controls/) | يرجع مجموعة عناصر التحكم ActiveX في الشريحة.<br/>            قراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/baseslide/name/) | يرجع أو يحدد اسم الشريحة.<br/>            قراءة/كتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/baseslide/slide_id/) | يرجع معرف الشريحة.<br/>            قراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/baseslide/custom_data/) | يرجع البيانات المخصصة للشريحة.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/baseslide/timeline/) | يرجع كائن جدول زمني للرسوم المتحركة.<br/>            قراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/baseslide/slide_show_transition/) | يرجع كائن الانتقال الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            قراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/baseslide/background/) | يرجع خلفية الشريحة.<br/>            قراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/baseslide/hyperlink_queries/) | يوفر وصولاً سهلاً إلى الروابط التشعبية المحتواة.<br/>            قراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/baseslide/show_master_shapes/) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا.<br/>            بالنسبة للشريحة الرئيسية نفسها تكون هذه الخاصية دائمًا `false`.<br/>            قراءة/كتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/baseslide/presentation/) | يرجع واجهة IPresentation.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/ar/aspose.slides/baseslide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/baseslide/join_portions_with_same_formatting/#) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات لجميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/baseslide/equals/#ibaseslide) | يحدد ما إذا كان مثالاَين من IBaseSlide متساويين.<br/>            يتم حساب القيمة المرتجعة استنادًا إلى بنية الشريحة والمحتوى الثابت.<br/>            تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى وما إلى ذلك متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرف الفريد، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/baseslide/create_theme_effective/#) | يرجع موضوعًا فعالًا لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/baseslide/find_shape_by_alt_text/#str) | يجد أول ظهور لشكل بالنص البديل المحدد. |


### انظر أيضا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)