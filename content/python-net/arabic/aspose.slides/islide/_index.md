---
title: ISlide class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/islide/
---
## ISlide فئة

يمثل شريحة في عرض تقديمي.

النوع ISlide يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/islide/header_footer_manager/) | يرجع مدير HeaderFooter للشريحة.<br/>            للقراءة فقط [`ISlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/ar/aspose.slides/islide/slide_number/) | يرجع رقم الشريحة.<br/>            فهرس الشريحة في مجموعة [`IPresentation.slides`](/slides/python-net/ar/aspose.slides/ipresentation/slides) يكون دائمًا مساويًا لـ SlideNumber - 1.<br/>            للقراءة والكتابة **int**. |
| [`hidden`](/slides/python-net/ar/aspose.slides/islide/hidden/) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح.<br/>            للقراءة والكتابة **bool**. |
| [`layout_slide`](/slides/python-net/ar/aspose.slides/islide/layout_slide/) | يرجع أو يضبط شريحة التخطيط للشريحة الحالية.<br/>            للقراءة والكتابة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ar/aspose.slides/islide/notes_slide_manager/) | يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها.<br/>            للقراءة فقط [`INotesSlideManager`](/slides/python-net/ar/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/ar/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/ar/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/ar/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/ar/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ar/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/ar/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ar/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/islide/theme_manager/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/islide/get_image/#float-float) | يرجع كائن صورة بمقياس مخصص. |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/islide/get_image/#) | يرجع كائن صورة مصغرة (20% من الحجم الفعلي). |
| [`get_image(self, image_size)`](/slides/python-net/ar/aspose.slides/islide/get_image/#asposepydrawingsize) | يرجع كائن صورة بالحجم المحدد. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | يرجع كائن صورة مصغرة بتنسيق tiff مع المعلمات المحددة. |
| [`get_image(self, options)`](/slides/python-net/ar/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | يرجع كائن Bitmap مصغر. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | يرجع كائن Bitmap مصغر بمقياس مخصص. |
| [`get_image(self, options, image_size)`](/slides/python-net/ar/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | يرجع كائن Bitmap مصغر بالحجم المحدد. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/islide/write_as_svg/#iorawiobase) | يحفظ محتوى الشريحة كملف SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | يحفظ محتوى الشريحة كملف SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/ar/aspose.slides/islide/get_slide_comments/#icommentauthor) | يرجع جميع تعليقات الشريحة التي أضافها مؤلف معين. |
| [`write_as_emf(self, stream)`](/slides/python-net/ar/aspose.slides/islide/write_as_emf/#iorawiobase) | يحفظ محتوى الشريحة كملف EMF. |
| [`remove(self)`](/slides/python-net/ar/aspose.slides/islide/remove/#) | يزيل الشريحة من العرض التقديمي. |
| [`reset(self)`](/slides/python-net/ar/aspose.slides/islide/reset/#) | يعيد ضبط الموضع والحجم والتنسيق لكل شكل لديه نموذج في LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/islide/create_theme_effective/#) |  |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)