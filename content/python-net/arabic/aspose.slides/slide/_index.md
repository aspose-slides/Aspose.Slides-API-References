---
title: Slide class
second_title: مرجع API ل Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/slide/
---
## فئة Slide

يمثل شريحة في عرض تقديمي.

**الوراثة:**[`Slide`](/slides/python-net/ar/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

نوع Slide يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/slide/shapes/) | إرجاع أشكال الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/slide/controls/) | إرجاع مجموعة عناصر التحكم ActiveX في الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/slide/name/) | إرجاع أو تعيين اسم الشريحة.<br/>            قراءة/كتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/slide/slide_id/) | إرجاع معرف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/slide/custom_data/) | إرجاع البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/slide/timeline/) | إرجاع كائن خط زمني للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/slide/slide_show_transition/) | إرجاع كائن الانتقال الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/slide/background/) | إرجاع خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/slide/hyperlink_queries/) | يوفر وصولاً سهلاً إلى الروابط التشعبية المتضمنة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/slide/show_master_shapes/) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا.<br/>            قراءة/كتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/slide/presentation/) | إرجاع واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/slide/header_footer_manager/) | إرجاع مدير HeaderFooter للشريحة.<br/>            للقراءة فقط [`ISlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/slide/theme_manager/) | إرجاع مدير السمة المتجاوزة.<br/>            للقراءة فقط [`IOverrideThemeManager`](/slides/python-net/ar/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/ar/aspose.slides/slide/slide_number/) | إرجاع رقم الشريحة.<br/>            فهرس الشريحة في مجموعة [`Presentation.slides`](/slides/python-net/ar/aspose.slides/presentation/slides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber.<br/>            قراءة/كتابة **int**. |
| [`hidden`](/slides/python-net/ar/aspose.slides/slide/hidden/) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح.<br/>            قراءة/كتابة **bool**. |
| [`layout_slide`](/slides/python-net/ar/aspose.slides/slide/layout_slide/) | إرجاع أو تعيين شريحة التخطيط للشريحة الحالية.<br/>            قراءة/كتابة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ar/aspose.slides/slide/notes_slide_manager/) | السماح بالوصول إلى شريحة الملاحظات، إضافة وإزالتها.<br/>            للقراءة فقط [`INotesSlideManager`](/slides/python-net/ar/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/ar/aspose.slides/slide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/slide/join_portions_with_same_formatting/#) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/slide/get_image/#float-float) | إرجاع كائن صورة مصغرة مع تصغير مخصص. |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/slide/get_image/#) | إرجاع كائن صورة مصغرة (20% من الحجم الفعلي). |
| [`get_image(self, image_size)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposepydrawingsize) | إرجاع كائن صورة مصغرة بالحجم المحدد. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | إرجاع كائن صورة tiff مصغرة مع المعلمات المحددة. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | إرجاع كائن صورة مصغرة. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | إرجاع كائن صورة مصغرة مع تصغير مخصص. |
| [`get_image(self, options, image_size)`](/slides/python-net/ar/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | إرجاع كائن صورة مصغرة بالحجم المحدد. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/slide/write_as_svg/#iorawiobase) | حفظ محتوى الشريحة كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | حفظ محتوى الشريحة كملف SVG. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/slide/equals/#ibaseslide) | يحدد ما إذا كان مثليا IBaseSlide متساويين.<br/>            يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت.<br/>            تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة وغيرها من الإعدادات إلخ متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريد، مثل SlideId والمحتوى الديناميكي، مثل القيمة الحالية لتاريخ Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/slide/create_theme_effective/#) | إرجاع سمة فعالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/slide/find_shape_by_alt_text/#str) | العثور على أول حدوث لشكل بالنص البديل المحدد. |
| [`write_as_emf(self, stream)`](/slides/python-net/ar/aspose.slides/slide/write_as_emf/#iorawiobase) | حفظ محتوى الشريحة كملف EMF. |
| [`remove(self)`](/slides/python-net/ar/aspose.slides/slide/remove/#) | إزالة الشريحة من العرض التقديمي. |
| [`reset(self)`](/slides/python-net/ar/aspose.slides/slide/reset/#) | إعادة تعيين الموضع والحجم وتنسيق كل شكل له نموذج أولي على LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/ar/aspose.slides/slide/get_slide_comments/#icommentauthor) | إرجاع جميع تعليقات الشريحة التي أضافها مؤلف محدد. |

### انظر أيضًا
* فئة [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* فئة [`Slide`](/slides/python-net/ar/aspose.slides/slide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)