---
title: ISlideCollection class
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islidecollection/
---
## ISlideCollection क्लास

स्लाइड्स का एक संग्रह दर्शाता है।

ISlideCollection प्रकार निम्न सदस्य उजागर करता है:

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।  
केवल पढ़ने योग्य [`ISlide`](/slides/python-net/hi/aspose.slides/islide).

## Indexer

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides/islidecollection/__getitem__/) |  |

## मेथड

| मेथड | विवरण |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/hi/aspose.slides/islidecollection/add_clone/#islide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, section)`](/slides/python-net/hi/aspose.slides/islidecollection/add_clone/#islide-isection) | निर्दिष्ट स्लाइड की एक कॉपी निर्दिष्ट अनुभाग के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/hi/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hi/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है।<br/>            उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयन किया जाएगा <br/>            (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान है). यदि कोई उपयुक्त लेआउट नहीं है तो<br/>            स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout <br/>            सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout<br/>            असत्य है). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_clone/#int-islide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है।<br/>            उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चयन किया जाएगा <br/>            (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान है). यदि कोई उपयुक्त लेआउट नहीं है तो<br/>            स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout <br/>            सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout<br/>            असत्य है). |
| [`to_array(self)`](/slides/python-net/hi/aspose.slides/islidecollection/to_array/#) | सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [`to_array(self, start_index, count)`](/slides/python-net/hi/aspose.slides/islidecollection/to_array/#int-int) | निर्दिष्ट रेंज की सभी स्लाइड्स के साथ एक एरे बनाता और लौटाता है। |
| [`reorder(self, index, slide)`](/slides/python-net/hi/aspose.slides/islidecollection/reorder/#int-islide) | संग्रह से स्लाइड को निर्दिष्ट स्थिति पर ले जाता है। |
| [`reorder(self, index, slides)`](/slides/python-net/hi/aspose.slides/islidecollection/reorder/#int-listislide) | संग्रह से स्लाइड्स को निर्दिष्ट स्थिति पर ले जाता है।<br/>            स्लाइड्स सूची में जिन क्रम में दिखाई देती हैं, उसी क्रम में अनुक्रमांक से शुरू होकर रखी जाएँगी. |
| [`add_from_pdf(self, path)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_pdf/#str) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और PDF आयात विकल्पों को विचार में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_text)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_html/#str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_stream)`](/slides/python-net/hi/aspose.slides/islidecollection/add_from_html/#iorawiobase) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्धारित स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्धारित स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्धारित स्थिति पर संग्रह में सम्मिलित करता है। |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्धारित स्थिति पर संग्रह में सम्मिलित करता है। |
| [`add_empty_slide(self, layout)`](/slides/python-net/hi/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | संग्रह के अंत में एक नई खाली स्लाइड जोड़ता है। |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/hi/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [`remove(self, value)`](/slides/python-net/hi/aspose.slides/islidecollection/remove/#islide) | संग्रह से किसी विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/islidecollection/remove_at/#int) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [`index_of(self, slide)`](/slides/python-net/hi/aspose.slides/islidecollection/index_of/#islide) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है। |

### देखें
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)