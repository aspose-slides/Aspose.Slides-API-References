---
title: IMasterSlide class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imasterslide/
---
## IMasterSlide فئة

يمثل شريحة رئيسية في عرض تقديمي.

يعرض نوع IMasterSlide الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/imasterslide/header_footer_manager/) | إرجاع مدير HeaderFooter للشريحة الرئيسية.<br/>            قراءة فقط [`IMasterSlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ar/aspose.slides/imasterslide/title_style/) | إرجاع نمط نص العنوان.<br/>            قراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ar/aspose.slides/imasterslide/body_style/) | إرجاع نمط نص الجسم.<br/>            قراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ar/aspose.slides/imasterslide/other_style/) | إرجاع نمط نص آخر.<br/>            قراءة فقط [`ITextStyle`](/slides/python-net/ar/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ar/aspose.slides/imasterslide/layout_slides/) | إرجاع مجموعة الشرائح الفرعية لتخطيط هذه الشريحة الرئيسية.<br/>            قراءة فقط [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ar/aspose.slides/imasterslide/preserve/) | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع <br/>            الشرائح التي تتبع تلك الشريحة الرئيسية.<br/>            ملاحظة: Aspose.Slides لن يقوم أبداً بإزالة أي شريحة رئيسية غير مستخدمة بنفسه، <br/>            لإزالة الشرائح الرئيسية غير المستخدمة فعلياً قم باستدعاء **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            قراءة/كتابة **bool**. |
| [`has_depending_slides`](/slides/python-net/ar/aspose.slides/imasterslide/has_depending_slides/) | إرجاع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية.<br/>            قراءة فقط **bool**. |
| [`drawing_guides`](/slides/python-net/ar/aspose.slides/imasterslide/drawing_guides/) | إرجاع مجموعة من أدلة الرسم للشريحة الرئيسية.<br/>            قراءة فقط [`IDrawingGuidesCollection`](/slides/python-net/ar/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/ar/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/ar/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/ar/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/ar/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ar/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/ar/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ar/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/imasterslide/theme_manager/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ar/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | إنشاء شريحة رئيسية جديدة بناءً على الحالية، وتطبيق سمة خارجية عليها <br/>            وتطبيق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح المعتمدة. |
| [`get_depending_slides(self)`](/slides/python-net/ar/aspose.slides/imasterslide/get_depending_slides/#) | إرجاع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/imasterslide/create_theme_effective/#) |  |

### انظر أيضا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)