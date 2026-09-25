---
title: Slide class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/slide/
---
## فئة Slide

يمثل شريحة في عرض تقديمي.

**الوراثة:**[`Slide`](/slides/python-net/ar/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

يعرض نوع Slide الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/slide/shapes/) | يرجع أشكال الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/slide/controls/) | يرجع مجموعة عناصر التحكم ActiveX في الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/slide/name/) | يرجع أو يعيّن اسم الشريحة.<br/>            للقراءة والكتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/slide/slide_id/) | يرجع معرف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/slide/custom_data/) | يرجع البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/slide/timeline/) | يرجع كائن خط الزمن للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/slide/slide_show_transition/) | يرجع كائن الانتقال الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/slide/background/) | يرجع خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/slide/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/slide/show_master_shapes/) | يحدد ما إذا كان يجب إظهار الأشكال على شريحة القالب في الشرائح أم لا.<br/>            للقراءة والكتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/slide/presentation/) | يرجع واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/slide/header_footer_manager/) | يرجع مدير HeaderFooter للشريحة.<br/>            للقراءة فقط [`ISlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/slide/theme_manager/) | يرجع مدير السمة المتجاوزة.<br/>            للقراءة فقط [`IOverrideThemeManager`](/slides/python-net/ar/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/ar/aspose.slides/slide/slide_number/) | يرجع رقم الشريحة.<br/>            فهرس الشريحة في مجموعة [`Presentation.slides`](/slides/python-net/ar/aspose.slides/presentation/slides) يكون دائمًا مساويًا لـ SlideNumber - Presentation.FirstSlideNumber.<br/>            للقراءة والكتابة **int**. |
| [`hidden`](/slides/python-net/ar/aspose.slides/slide/hidden/) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح.<br/>            للقراءة والكتابة **bool**. |
| [`layout_slide`](/slides/python-net/ar/aspose.slides/slide/layout_slide/) | يرجع أو يعيّن شريحة التخطيط للشريحة الحالية.<br/>            للقراءة والكتابة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ar/aspose.slides/slide/notes_slide_manager/) | يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها.<br/>            للقراءة فقط [`INotesSlideManager`](/slides/python-net/ar/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/ar/aspose.slides/slide/slide/) |  |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/slide/join_portions_with_same_formatting/#) | ينضم إلى النصوص المتتالية ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | ينضم إلى النصوص المتتالية ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/slide/get_image/#float-float) | يرجع كائن صورة مصغرة مع قياس مخصص. |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/slide/get_image/#) | يرجع كائن صورة مصغرة (20% من الحجم الحقيقي). |
| [`get_image(self, image_size)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidessize) | يرجع كائن صورة مصغرة بالحجم المحدد. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | يرجع كائن صورة مصغرة بصيغة tiff مع معلمات محددة. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | يرجع كائن صورة مصغرة. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | يرجع كائن صورة مصغرة مع قياس مخصص. |
| [`get_image(self, options, image_size)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | يرجع كائن صورة مصغرة بالحجم المحدد. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/slide/write_as_svg/#iorawiobase) | يحفظ محتوى الشريحة كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشريحة كملف SVG. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/slide/equals/#ibaseslide) | يحدد ما إذا كان مثليا IBaseSlide متساويين.<br/>            يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت.<br/>            تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى… متساوية. لا يأخذ المقارنة بعين الاعتبار قيم المعرف الفريد، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالي في عنصر نائبة التاريخ. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/slide/create_theme_effective/#) | يرجع سمة فعّالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/slide/find_shape_by_alt_text/#str) | يجد أول ظهور لشكل بالنص البديل المحدد. |
| [`write_as_emf(self, stream)`](/slides/python-net/ar/aspose.slides/slide/write_as_emf/#iorawiobase) | يحفظ محتوى الشريحة كملف EMF. |
| [`remove(self)`](/slides/python-net/ar/aspose.slides/slide/remove/#) | يزيل الشريحة من العرض التقديمي. |
| [`reset(self)`](/slides/python-net/ar/aspose.slides/slide/reset/#) | يعيد تعيين الموضع والحجم والتنسيق لكل شكل له نموذج في LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/ar/aspose.slides/slide/get_slide_comments/#icommentauthor) | يرجع جميع تعليقات الشريحة المضافة بواسطة مؤلف معين. |

### انظر أيضاً
* فئة [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* فئة [`Slide`](/slides/python-net/ar/aspose.slides/slide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)