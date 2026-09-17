---
title: MasterSlide class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/masterslide/
---
## الفئة MasterSlide

يمثل شريحة رئيسية في عرض تقديمي.

**الوراثة:**[`MasterSlide`](/slides/python-net/ar/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

نوع MasterSlide يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/masterslide/shapes/) | يعيد أشكال الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/masterslide/controls/) | يعيد مجموعة عناصر التحكم ActiveX في الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/masterslide/name/) | يعيد أو يضبط اسم الشريحة الرئيسية.<br/>            قابل للقراءة والكتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/masterslide/slide_id/) | يعيد معرف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/masterslide/custom_data/) | يعيد البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/masterslide/timeline/) | يعيد كائن مخطط الرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/masterslide/slide_show_transition/) | يعيد كائن الانتقال الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء العرض.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/masterslide/background/) | يعيد خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/masterslide/hyperlink_queries/) | يوفّر وصولًا سهلاً إلى الروابط التشعبية المتضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/masterslide/show_master_shapes/) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا.<br/>            بالنسبة للشريحة الرئيسية نفسها هذه الخاصية دائمًا تُرجع `false`.<br/>            قابل للقراءة والكتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/masterslide/presentation/) | يعيد واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/masterslide/header_footer_manager/) | يعيد مدير HeaderFooter للشريحة الرئيسية.<br/>            للقراءة فقط [`IMasterSlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ar/aspose.slides/masterslide/title_style/) | يعيد نمط نص العنوان.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ar/aspose.slides/masterslide/body_style/) | يعيد نمط نص الجسم.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ar/aspose.slides/masterslide/other_style/) | يعيد نمط النص الآخر.<br/>            للقراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ar/aspose.slides/masterslide/layout_slides/) | يعيد مجموعة شرائح التخطيط الفرعية لهذه الشريحة الرئيسية.<br/>            للقراءة فقط [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ar/aspose.slides/masterslide/preserve/) | يحدد ما إذا كان سيتم حذف الماستر المقابل عندما تُحذف جميع الشرائح التي تليه.<br/>            ملاحظة: Aspose.Slides لن يزيل أي ماستر غير مستخدم بمفرده؛ لإزالة الماسترات غير المستخدمة فعليًا استدعِ **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            قابل للقراءة والكتابة **bool**. |
| [`has_depending_slides`](/slides/python-net/ar/aspose.slides/masterslide/has_depending_slides/) | يُرجع true إذا كان هناك على الأقل شريحة واحدة تعتمد على هذه الشريحة الرئيسية.<br/>            للقراءة فقط **bool**. |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/masterslide/theme_manager/) | يعيد مدير السمة.<br/>            للقراءة فقط [`IMasterThemeManager`](/slides/python-net/ar/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ar/aspose.slides/masterslide/drawing_guides/) | يعيد مجموعة من أدوات الرسم للماستر.<br/>            للقراءة فقط [`IDrawingGuidesCollection`](/slides/python-net/ar/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ar/aspose.slides/masterslide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/masterslide/join_portions_with_same_formatting/#) | يجمع الجمل ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | يجمع الجمل ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/masterslide/equals/#ibaseslide) | يحدد ما إذا كانت كائني IBaseSlide متساويين.<br/>            تُحسب القيمة العائدة بناءً على بنية الشريحة والمحتوى الثابت.<br/>            تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريد، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالي في Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/masterslide/create_theme_effective/#) | يُرجع سمة فعّالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/masterslide/find_shape_by_alt_text/#str) | يجد أول ظهور لشكل يحمل النص البديل المحدد. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ar/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | ينشئ شريحة رئيسية جديدة بناءً على الحالية، يطبق سمة خارجية عليها <br/>            ويطبّق الشريحة الرئيسية المُنشأة على جميع الشرائح التابعة. |
| [`get_depending_slides(self)`](/slides/python-net/ar/aspose.slides/masterslide/get_depending_slides/#) | يُرجع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |


### انظر أيضًا
* الفئة [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* الفئة [`MasterSlide`](/slides/python-net/ar/aspose.slides/masterslide)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)