---
title: ISlideCollection class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/islidecollection/
---
## ISlideCollection فئة

يمثل مجموعة من الشرائح.

يعرض نوع ISlideCollection الأعضاء التالية:

يحصل على العنصر عند الفهرس المحدد.
            قراءة فقط [`ISlide`](/slides/python-net/ar/aspose.slides/islide).

## المؤشر

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides/islidecollection/__getitem__/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/ar/aspose.slides/islidecollection/add_clone/#islide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/ar/aspose.slides/islidecollection/add_clone/#islide-isection) | Adds a copy of a specified slide to the end of the specified section. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/ar/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ar/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة.<br/>            سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد <br/>            (التخطيط المناسب هو التخطيط الذي له نفس Type أو Name مثل <br/>            تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن<br/>            تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout <br/>            صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout<br/>            خطأً). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_clone/#int-islide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة.<br/>            سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد <br/>            (التخطيط المناسب هو التخطيط الذي له نفس Type أو Name مثل <br/>            تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن<br/>            تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout <br/>            صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout<br/>            خطأً). |
| [`to_array(self)`](/slides/python-net/ar/aspose.slides/islidecollection/to_array/#) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [`to_array(self, start_index, count)`](/slides/python-net/ar/aspose.slides/islidecollection/to_array/#int-int) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |
| [`reorder(self, index, slide)`](/slides/python-net/ar/aspose.slides/islidecollection/reorder/#int-islide) | ينقل الشريحة من المجموعة إلى الموضع المحدد. |
| [`reorder(self, index, slides)`](/slides/python-net/ar/aspose.slides/islidecollection/reorder/#int-listislide) | ينقل الشرائح من المجموعة إلى الموضع المحدد.<br/>            ستوضع الشرائح بدءًا من الفهرس وفقًا لترتيب ظهورها في القائمة. |
| [`add_from_pdf(self, path)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_pdf/#str) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد pdf. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_text)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_html/#str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`add_from_html(self, html_stream)`](/slides/python-net/ar/aspose.slides/islidecollection/add_from_html/#iorawiobase) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-str) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة عند الموضع المحدد. |
| [`add_empty_slide(self, layout)`](/slides/python-net/ar/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/ar/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | يدخل نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [`remove(self, value)`](/slides/python-net/ar/aspose.slides/islidecollection/remove/#islide) | يزيل أول تكرار لكائن معين من المجموعة. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/islidecollection/remove_at/#int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [`index_of(self, slide)`](/slides/python-net/ar/aspose.slides/islidecollection/index_of/#islide) | يعيد فهرس الشريحة المحددة في المجموعة. |


### راجع أيضًا
* فئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)