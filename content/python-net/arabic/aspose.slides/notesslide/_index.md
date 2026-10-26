---
title: NotesSlide class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/notesslide/
---
## فئة NotesSlide

يمثّل شريحة ملاحظات في عرض تقديمي.

**الوراثة:**[`NotesSlide`](/slides/python-net/ar/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)

يعرض نوع NotesSlide الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shapes`](/slides/python-net/ar/aspose.slides/notesslide/shapes/) | يعيد الأشكال في الشريحة.<br/>            للقراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ar/aspose.slides/notesslide/controls/) | يعيد مجموعة عناصر ActiveX في الشريحة.<br/>            للقراءة فقط [`IControlCollection`](/slides/python-net/ar/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ar/aspose.slides/notesslide/name/) | يعيد أو يعيّن اسم الشريحة.<br/>            قراءة/كتابة **str**. |
| [`slide_id`](/slides/python-net/ar/aspose.slides/notesslide/slide_id/) | يعيد معرف الشريحة.<br/>            للقراءة فقط **int**. |
| [`custom_data`](/slides/python-net/ar/aspose.slides/notesslide/custom_data/) | يعيد البيانات المخصصة للشريحة.<br/>            للقراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ar/aspose.slides/notesslide/timeline/) | يعيد كائن خط الزمن للرسوم المتحركة.<br/>            للقراءة فقط [`IAnimationTimeLine`](/slides/python-net/ar/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ar/aspose.slides/notesslide/slide_show_transition/) | يعيد كائن Transition الذي يحتوي على معلومات حول<br/>            كيفية تقدم الشريحة المحددة أثناء عرض الشرائح.<br/>            للقراءة فقط [`ISlideShowTransition`](/slides/python-net/ar/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ar/aspose.slides/notesslide/background/) | يعيد خلفية الشريحة.<br/>            للقراءة فقط [`IBackground`](/slides/python-net/ar/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ar/aspose.slides/notesslide/hyperlink_queries/) | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.<br/>            للقراءة فقط [`IHyperlinkQueries`](/slides/python-net/ar/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ar/aspose.slides/notesslide/show_master_shapes/) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الأساسية في الشرائح أم لا.<br/>            قراءة/كتابة **bool**. |
| [`presentation`](/slides/python-net/ar/aspose.slides/notesslide/presentation/) | يعيد واجهة IPresentation.<br/>            للقراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ar/aspose.slides/notesslide/header_footer_manager/) | يعيد مدير HeaderFooter لشريحة الملاحظات.<br/>            للقراءة فقط [`INotesSlideHeaderFooterManager`](/slides/python-net/ar/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/ar/aspose.slides/notesslide/notes_text_frame/) | يعيد TextFrame يحتوي على نص الملاحظات إذا كان موجودًا.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/ar/aspose.slides/notesslide/theme_manager/) | يعيد مدير السمة المتجاوزة.<br/>            للقراءة فقط [`IOverrideThemeManager`](/slides/python-net/ar/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/ar/aspose.slides/notesslide/parent_slide/) | يعيد الشريحة الأصلية.<br/>            للقراءة فقط [`ISlide`](/slides/python-net/ar/aspose.slides/islide). |
| [`slide`](/slides/python-net/ar/aspose.slides/notesslide/slide/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ar/aspose.slides/notesslide/join_portions_with_same_formatting/#) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال القابلة للقبول. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ar/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال القابلة للقبول. |
| [`equals(self, slide)`](/slides/python-net/ar/aspose.slides/notesslide/equals/#ibaseslide) | يحدد ما إذا كان مثلاّ الـIBaseSlide الاثنين متساويين.<br/>            يتم حساب القيمة المرجعة استنادًا إلى بنية الشريحة والمحتوى الثابت.<br/>            تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى... متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/ar/aspose.slides/notesslide/create_theme_effective/#) | يعيد سمة فعّالة لهذه الشريحة. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ar/aspose.slides/notesslide/find_shape_by_alt_text/#str) | يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد. |

### انظر أيضاً
* فئة [`BaseSlide`](/slides/python-net/ar/aspose.slides/baseslide)
* فئة [`NotesSlide`](/slides/python-net/ar/aspose.slides/notesslide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)