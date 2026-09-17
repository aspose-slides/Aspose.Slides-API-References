---
title: MasterNotesSlide class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masternotesslide/
---
## فئة MasterNotesSlide

يمثل الشريحة الرئيسية للملاحظات.

**الوراثة:**[`MasterNotesSlide`](/slides/python-net/ar/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

The MasterNotesSlide type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/masternotesslide/shapes/) | يعيد الأشكال الخاصة بشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/masternotesslide/controls/) | يعيد مجموعة عناصر التحكم ActiveX في شريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/masternotesslide/name/) | يعيد أو يضبط اسم شريحة.<br/>            للقراءة والكتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/masternotesslide/slide_id/) | يعيد معرف شريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/masternotesslide/custom_data/) | يعيد البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/masternotesslide/timeline/) | يعيد كائن جدول زمني للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/masternotesslide/slide_show_transition/) | يعيد كائن الانتقال الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/masternotesslide/background/) | يعيد خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/masternotesslide/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/masternotesslide/show_master_shapes/) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا.<br/>            بالنسبة للشريحة الرئيسية نفسها، هذه الخاصية تعيد دائمًا `false`.<br/>            للقراءة والكتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/masternotesslide/presentation/) | يعيد واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/masternotesslide/header_footer_manager/) | يعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية.<br/>            للقراءة فقط [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/masternotesslide/theme_manager/) | يعيد مدير السمة.<br/>            للقراءة فقط [`IMasterThemeManager`](/slides/python-net/ar/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/ar/aspose.slides/masternotesslide/notes_style/) | يعيد نمط نص الملاحظات.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/ar/aspose.slides/masternotesslide/drawing_guides/) | يعيد مجموعة من الأدلة المرسومة لشريحة الملاحظات الرئيسية.<br/>            للقراءة فقط [`IDrawingGuidesCollection`](/slides/python-net/ar/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ar/aspose.slides/masternotesslide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات وجميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات في جميع الأشكال المقبولة. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/masternotesslide/equals/#ibaseslide) | يحدد ما إذا كان مثالاى IBaseSlide الاثنين متساويين.<br/>            يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت.<br/>            تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى ... متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر نائب التاريخ. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/masternotesslide/create_theme_effective/#) | يعيد سمة فعّالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد. |


### أنظر أيضًا
* الفئة [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* الفئة [`MasterNotesSlide`](/slides/python-net/ar/aspose.slides/masternotesslide)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)