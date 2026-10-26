---
title: MasterHandoutSlide class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide class

يمثل الشريحة الرئيسية للمطبوعات.

**الوراثة:**[`MasterHandoutSlide`](/slides/python-net/ar/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

يعرض نوع MasterHandoutSlide الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/masterhandoutslide/shapes/) | يرجع أشكال الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/masterhandoutslide/controls/) | يرجع مجموعة عناصر تحكم ActiveX على الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/masterhandoutslide/name/) | يرجع أو يحدد اسم الشريحة.<br/>            قراءة/كتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/masterhandoutslide/slide_id/) | يرجع معرف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/masterhandoutslide/custom_data/) | يررج البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/masterhandoutslide/timeline/) | يررج كائن مخطط زمني للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/masterhandoutslide/slide_show_transition/) | يررج كائن Transition الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة خلال عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/masterhandoutslide/background/) | يررج خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/masterhandoutslide/hyperlink_queries/) | يوفر وصولاً سهلاً إلى الروابط الفائقة المضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/masterhandoutslide/show_master_shapes/) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا.<br/>            بالنسبة للشريحة الرئيسية نفسها، تعود هذه الخاصية دائمًا بـ `false`.<br/>            قراءة/كتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/masterhandoutslide/presentation/) | يررج واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/masterhandoutslide/header_footer_manager/) | يررج مدير HeaderFooter لشريحة المطبوعات الرئيسية.<br/>            للقراءة فقط [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/masterhandoutslide/theme_manager/) | يررج مدير السمة.<br/>            للقراءة فقط [`IMasterThemeManager`](/slides/python-net/ar/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ar/aspose.slides/masterhandoutslide/drawing_guides/) | يررج مجموعة من أدلة الرسم لشريحة المطبوعات الرئيسية.<br/>            للقراءة فقط [`IDrawingGuidesCollection`](/slides/python-net/ar/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ar/aspose.slides/masterhandoutslide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات وجميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | يجمع السلاسل ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/masterhandoutslide/equals/#ibaseslide) | يحدد ما إذا كانت مثيلتي IBaseSlide متساويتين.<br/>            يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت.<br/>            تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى ... متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر نائب التاريخ. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/masterhandoutslide/create_theme_effective/#) | يررج سمة فعالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | يعثر على أول ظهور لشكل يحتوي على النص البديل المحدد. |

### انظر أيضًا
* class [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* class [`MasterHandoutSlide`](/slides/python-net/ar/aspose.slides/masterhandoutslide)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)