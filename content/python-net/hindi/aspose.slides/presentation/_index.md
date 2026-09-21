---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentation/
---
## प्रेजेंटेशन क्लास

Microsoft PowerPoint प्रेजेंटेशन का प्रतिनिधित्व करता है।

Presentation प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#) | यह कन्स्ट्रक्टर प्रारंभ से नया प्रेजेंटेशन बनाता है।<br/>            निर्मित प्रेजेंटेशन में एक खाली स्लाइड होता है। |
| [`__init__(self, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#loadoptions) | यह कन्स्ट्रक्टर प्रारंभ से नया प्रेजेंटेशन बनाता है।<br/>            निर्मित प्रेजेंटेशन में एक खाली स्लाइड होता है। |
| [`__init__(self, stream)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#iorawiobase) | यह कन्स्ट्रक्टर मौजूदा Presentation को पढ़ने के लिए प्राथमिक तंत्र है। |
| [`__init__(self, stream, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | यह कन्स्ट्रक्टर मौजूदा Presentation को पढ़ने के लिए प्राथमिक तंत्र है। |
| [`__init__(self, file)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#str) | यह कन्स्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे<br/>             Presentation की सामग्री पढ़ी जाती है। |
| [`__init__(self, file, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#str-loadoptions) | यह कन्स्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे<br/>            Presentation की सामग्री पढ़ी जाती है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`current_date_time`](/slides/python-net/hi/aspose.slides/presentation/current_date_time/) | डेट और टाइम को लौटाता या सेट करता है जो datetime फ़ील्ड्स की सामग्री को प्रतिस्थापित करेगा।<br/>            डिफ़ॉल्ट रूप से इस Presentation ऑब्जेक्ट के निर्माण का समय।<br/>            पढ़ने-और-लिखने योग्य **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/presentation/header_footer_manager/) | वास्तविक HeaderFooter प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentationHeaderFooterManager`](/slides/python-net/hi/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hi/aspose.slides/presentation/protection_manager/) | इस प्रेजेंटेशन के अनुमतियों के प्रबंधक को प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IProtectionManager`](/slides/python-net/hi/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hi/aspose.slides/presentation/slides/) | प्रेजेंटेशन में परिभाषित सभी स्लाइड्स की सूची लौटाता है।<br/hi/>            केवल-पढ़ने योग्य [`ISlideCollection`](/slides/python-net/hi/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hi/aspose.slides/presentation/sections/) | प्रेजेंटेशन में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISectionCollection`](/slides/python-net/hi/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hi/aspose.slides/presentation/slide_size/) | स्लाइड आकार वस्तु लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISlideSize`](/slides/python-net/hi/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hi/aspose.slides/presentation/notes_size/) | नोट्स स्लाइड आकार वस्तु लौटाता है।<br/>            केवल-पढ़ने योग्य [`INotesSize`](/slides/python-net/hi/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hi/aspose.slides/presentation/layout_slides/) | प्रेजेंटेशन में परिभाषित सभी लेआउट स्लाइड्स की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hi/aspose.slides/presentation/masters/) | प्रेजेंटेशन में परिभाषित सभी मास्टर स्लाइड्स की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterSlideCollection`](/slides/python-net/hi/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hi/aspose.slides/presentation/master_notes_slide_manager/) | नोट्स मास्टर प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterNotesSlideManager`](/slides/python-net/hi/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hi/aspose.slides/presentation/master_handout_slide_manager/) | हैंडआउट मास्टर प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterHandoutSlideManager`](/slides/python-net/hi/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hi/aspose.slides/presentation/fonts_manager/) | फ़ॉन्ट प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IFontsManager`](/slides/python-net/hi/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hi/aspose.slides/presentation/default_text_style/) | आकारों के लिए डिफ़ॉल्ट टेक्स्ट स्टाइल लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hi/aspose.slides/presentation/comment_authors/) | टिप्पणी लेखक का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICommentAuthorCollection`](/slides/python-net/hi/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hi/aspose.slides/presentation/document_properties/) | DocumentProperties वस्तु लौटाता है जिसमें मानक और कस्टम दस्तावेज़ गुण होते हैं।<br/>            केवल-पढ़ने योग्य [`IDocumentProperties`](/slides/python-net/hi/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hi/aspose.slides/presentation/images/) | प्रेजेंटेशन में सभी छवियों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IImageCollection`](/slides/python-net/hi/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hi/aspose.slides/presentation/audios/) | प्रेजेंटेशन में सभी अंतर्निहित ऑडियो फ़ाइलों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAudioCollection`](/slides/python-net/hi/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hi/aspose.slides/presentation/videos/) | प्रेजेंटेशन में सभी अंतर्निहित वीडियो फ़ाइलों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IVideoCollection`](/slides/python-net/hi/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/hi/aspose.slides/presentation/slide_show_settings/) | प्रेजेंटेशन के स्लाइड शो सेटिंग्स लौटाता है। |
| [`digital_signatures`](/slides/python-net/hi/aspose.slides/presentation/digital_signatures/) | प्रेजेंटेशन पर हस्ताक्षर करने के लिए उपयोग की गई हस्ताक्षर का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IDigitalSignatureCollection`](/slides/python-net/hi/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/presentation/custom_data/) | प्रेजेंटेशन का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/hi/aspose.slides/presentation/all_custom_xml_parts/) | प्रेजेंटेशन में सभी कस्टम डेटा भाग लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomXmlPart`](/slides/python-net/hi/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/hi/aspose.slides/presentation/vba_project/) | प्रेजेंटेशन मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IVbaProject`](/slides/python-net/hi/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/presentation/hyperlink_queries/) | सभी प्रेजेंटेशन स्लाइड्स (मास्टर, लेआउट, नोट्स स्लाइड्स में नहीं) में मौजूद सभी हाइपरलिंक का आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hi/aspose.slides/presentation/view_properties/) | प्रेजेंटेशन-व्यापी दृश्य गुण प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IViewProperties`](/slides/python-net/hi/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hi/aspose.slides/presentation/first_slide_number/) | प्रेजेंटेशन में पहली स्लाइड नंबर को दर्शाता है |
| [`sensitivity_labels`](/slides/python-net/hi/aspose.slides/presentation/sensitivity_labels/) | प्रेजेंटेशन दस्तावेज़ पर लागू संवेदनशीलता लेबल का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISensitivityLabelCollection`](/slides/python-net/hi/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/hi/aspose.slides/presentation/source_format/) | प्रेजेंटेशन किस प्रारूप से लोड किया गया था, इस बारे में जानकारी लौटाता है।<br/>            केवल-पढ़ने योग्य [`SourceFormat`](/slides/python-net/hi/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/hi/aspose.slides/presentation/master_theme/) | मास्टर थीम लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterTheme`](/slides/python-net/hi/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/hi/aspose.slides/presentation/presentation/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | प्रेजेंटेशन की सभी स्लाइड्स को निर्दिष्ट स्वरूप के साथ फ़ाइल में सहेजता है। |
| [`save(self, stream, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | प्रेजेंटेशन की सभी स्लाइड्स को निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है। |
| [`save(self, fname, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | प्रेजेंटेशन की सभी स्लाइड्स को निर्दिष्ट स्वरूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है। |
| [`save(self, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | प्रेजेंटेशन की सभी स्लाइड्स को XAML मार्कअप दर्शाती फ़ाइलों के सेट में सहेजता है। |
| [`save(self, fname, slides, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट स्वरूप के साथ फ़ाइल में सहेजता है। |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | प्रेजेंटेशन की निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट स्वरूप के साथ फ़ाइल में सहेजता है। |
| [`save(self, stream, slides, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है। |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है। |
| [`get_images(self, options)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | प्रेजेंटेशन की सभी स्लाइड्स के लिए Image वस्तुएँ लौटाता है। |
| [`get_images(self, options, slides)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए थंबनेल Image वस्तुएँ लौटाता है। |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | प्रेजेंटेशन की सभी स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल Image वस्तुएँ लौटाता है। |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए कस्टम स्केलिंग के साथ थंबनेल Image वस्तुएँ लौटाता है। |
| [`get_images(self, options, image_size)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | प्रेजेंटेशन की सभी स्लाइड्स के लिए निर्दिष्ट आकार के साथ थंबनेल Image वस्तुएँ लौटाता है। |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए निर्दिष्ट आकार के साथ थंबनेल Image वस्तुएँ लौटाता है। |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | उदाहरण टेक्स्ट के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | उदाहरण टेक्स्ट के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [`get_slide_by_id(self, id)`](/slides/python-net/hi/aspose.slides/presentation/get_slide_by_id/#int) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/presentation/join_portions_with_same_formatting/#) | सभी स्लाइड्स में सभी स्वीकार्य आकृतियों के सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | रेगुलर एक्सप्रेशन के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट टेक्स्ट की सभी घटनाओं को दूसरे निर्दिष्ट टेक्स्ट से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/presentation/replace_regex/#str-str) | रेगुलर एक्सप्रेशन के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)