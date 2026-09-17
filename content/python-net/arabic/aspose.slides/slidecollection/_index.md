---
title: SlideCollection class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/slidecollection/
---
## SlideCollection فئة

يمثل مجموعة من الشرائح.

يعرض نوع SlideCollection الأعضاء التالية:

يحصل على العنصر عند الفهرس المحدد.
            قراءة فقط [`Slide`](/slides/python-net/ar/aspose.slides/slide).

## المؤشر

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides/slidecollection/__getitem__/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ar/aspose.slides/slidecollection/add_clone/#islide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ar/aspose.slides/slidecollection/add_clone/#islide-isection) | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ar/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ar/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة.<br/>            سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد <br/>            (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل <br/>            تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن <br/>            تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout <br/>            صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout <br/>            خاطئًا). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_clone/#int-islide) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | يدرج نسخة من شريحة مصدر محددة إلى الموضع المحدد في المجموعة.<br/>            سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد <br/>            (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل <br/>            تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن <br/>            تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout <br/>            صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout <br/>            خاطئًا). |
| [`to_array(self)`](/slides/python-net/ar/aspose.slides/slidecollection/to_array/#) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [`to_array(self, start_index, count)`](/slides/python-net/ar/aspose.slides/slidecollection/to_array/#int-int) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد فيها.<br/>            فهرس أول شريحة للإضافة. عدد الشرائح للإضافة. |
| [`reorder(self, index, slide)`](/slides/python-net/ar/aspose.slides/slidecollection/reorder/#int-islide) | ينقل الشريحة من المجموعة إلى الموضع المحدد. |
| [`reorder(self, index, slides)`](/slides/python-net/ar/aspose.slides/slidecollection/reorder/#int-listislide) | ينقل الشرائح من المجموعة إلى الموضع المحدد.<br/>            ستُوضع الشرائح بدءًا من الفهرس وفقًا للترتيب الذي تظهر فيه في القائمة. |
| [`add_from_pdf(self, path)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_pdf/#str) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_text)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_html/#str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_stream)`](/slides/python-net/ar/aspose.slides/slidecollection/add_from_html/#iorawiobase) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-str) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [`add_empty_slide(self, layout)`](/slides/python-net/ar/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ar/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [`remove(self, value)`](/slides/python-net/ar/aspose.slides/slidecollection/remove/#islide) | يزيل أول ظهور لكائن محدد من المجموعة. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/slidecollection/remove_at/#int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [`index_of(self, slide)`](/slides/python-net/ar/aspose.slides/slidecollection/index_of/#islide) | يعيد فهرس الشريحة المحددة في المجموعة. |

### انظر أيضًا
* فئة [`Slide`](/slides/python-net/ar/aspose.slides/slide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)