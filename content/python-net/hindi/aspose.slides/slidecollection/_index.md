---
title: SlideCollection class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidecollection/
---
## SlideCollection वर्ग

स्लाइड्स के संग्रह का प्रतिनिधित्व करता है।

SlideCollection प्रकार निम्नलिखित सदस्यों को उजागर करता है:

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।  
केवल पढ़ने योग्य [`Slide`](/slides/python-net/hi/aspose.slides/slide).

## Indexer

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides/slidecollection/__getitem__/) |  |

## Methods

| विधि | विवरण |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/hi/aspose.slides/slidecollection/add_clone/#islide) | निर्दिष्ट स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, section)`](/slides/python-net/hi/aspose.slides/slidecollection/add_clone/#islide-isection) | निर्दिष्ट स्लाइड की एक कॉपी को निर्दिष्ट सेक्शन के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/hi/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hi/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी को संग्रह के अंत में जोड़ता है।<br/>            उपयुक्त लेआउट को निर्दिष्ट <br/>            मास्टर से स्वचालित रूप से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि कोई उपयुक्त लेआउट नहीं है तो<br/>            स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout <br/>            सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout<br/>            असत्य है)। |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_clone/#int-islide) | निर्दिष्ट स्लाइड की एक कॉपी को संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी को संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | निर्दिष्ट स्रोत स्लाइड की एक कॉपी को संग्रह में निर्दिष्ट स्थिति पर डालता है।<br/>            उपयुक्त लेआउट को निर्दिष्ट <br/>            मास्टर से स्वचालित रूप से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका Type या Name स्रोत स्लाइड के लेआउट के समान हो)। यदि कोई उपयुक्त लेआउट नहीं है तो<br/>            स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout <br/>            सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout<br/>            असत्य है)। |
| [`to_array(self)`](/slides/python-net/hi/aspose.slides/slidecollection/to_array/#) | सभी स्लाइड्स के साथ एक ऐरे बनाता है और लौटाता है। |
| [`to_array(self, start_index, count)`](/slides/python-net/hi/aspose.slides/slidecollection/to_array/#int-int) | निर्दिष्ट सीमा से सभी स्लाइड्स के साथ एक ऐरे बनाता है और लौटाता है।<br/>            जोड़ने के लिए पहले स्लाइड का सूचकांक। जोड़ने के लिए स्लाइड्स की संख्या। |
| [`reorder(self, index, slide)`](/slides/python-net/hi/aspose.slides/slidecollection/reorder/#int-islide) | स्लाइड को संग्रह से हटाकर निर्दिष्ट स्थिति पर ले जाता है। |
| [`reorder(self, index, slides)`](/slides/python-net/hi/aspose.slides/slidecollection/reorder/#int-listislide) | स्लाइड्स को संग्रह से हटाकर निर्दिष्ट स्थिति पर ले जाता है।<br/>            स्लाइड्स को सूचकांक से शुरू करके सूची में जिस क्रम में वे दिखाई देते हैं, उसी क्रम में रखा जाएगा। |
| [`add_from_pdf(self, path)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_pdf/#str) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और PDF आयात विकल्पों को ध्यान में रखकर उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_text)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_html/#str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`add_from_html(self, html_stream)`](/slides/python-net/hi/aspose.slides/slidecollection/add_from_html/#iorawiobase) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`add_empty_slide(self, layout)`](/slides/python-net/hi/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | संग्रह के अंत में एक नया खाली स्लाइड जोड़ता है। |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/hi/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | निर्दिष्ट स्लाइड की एक कॉपी को संग्रह में निर्दिष्ट स्थिति पर डालता है। |
| [`remove(self, value)`](/slides/python-net/hi/aspose.slides/slidecollection/remove/#islide) | संग्रह से विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/slidecollection/remove_at/#int) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [`index_of(self, slide)`](/slides/python-net/hi/aspose.slides/slidecollection/index_of/#islide) | संग्रह में निर्दिष्ट स्लाइड का सूचकांक लौटाता है। |


### देखें भी
* वर्ग [`Slide`](/slides/python-net/hi/aspose.slides/slide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)