---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentation/
---
## Presentation क्लास

एक Microsoft PowerPoint प्रस्तुति का प्रतिनिधित्व करता है।

The Presentation type exposes the following members:

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#) | यह कंस्ट्रक्टर नई प्रस्तुति को शुरू से बनाता है।<br/>            बनाई गई प्रस्तुति में एक खाली स्लाइड है। |
| [`__init__(self, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#loadoptions) | यह कंस्ट्रक्टर नई प्रस्तुति को शुरू से बनाता है।<br/>            बनाई गई प्रस्तुति में एक खाली स्लाइड है। |
| [`__init__(self, stream)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#iorawiobase) | यह कंस्ट्रक्टर मौजूदा Presentation को पढ़ने के लिए प्राथमिक तंत्र है। |
| [`__init__(self, stream, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | यह कंस्ट्रक्टर मौजूदा Presentation को पढ़ने के लिए प्राथमिक तंत्र है। |
| [`__init__(self, file)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#str) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे<br/>             Presentation की सामग्री पढ़ी जाती है। |
| [`__init__(self, file, load_options)`](/slides/python-net/hi/aspose.slides/presentation/__init__/#str-loadoptions) | यह कंस्ट्रक्टर स्रोत फ़ाइल पथ प्राप्त करता है जिससे<br/>            Presentation की सामग्री पढ़ी जाती है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`current_date_time`](/slides/python-net/hi/aspose.slides/presentation/current_date_time/) | तारीख और समय को लौटाता या सेट करता है जो datetime क्षेत्रों की सामग्री को प्रतिस्थापित करेगा।<br/>            इस Presentation ऑब्जेक्ट के निर्मित होने का समय डिफ़ॉल्ट रूप से।<br/>            पढ़ें/लिखें **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/presentation/header_footer_manager/) | वास्तविक HeaderFooter प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentationHeaderFooterManager`](/slides/python-net/hi/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hi/aspose.slides/presentation/protection_manager/) | इस प्रस्तुति के अनुमतियों के प्रबंधक को प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IProtectionManager`](/slides/python-net/hi/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hi/aspose.slides/presentation/slides/) | प्रस्तुति में परिभाषित सभी स्लाइडों की सूची लौटाता है।<br/hi/>            केवल-पढ़ने योग्य [`ISlideCollection`](/slides/python-net/hi/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hi/aspose.slides/presentation/sections/) | प्रस्तुति में परिभाषित सभी स्लाइड अनुभागों की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISectionCollection`](/slides/python-net/hi/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hi/aspose.slides/presentation/slide_size/) | स्लाइड आकार वस्तु को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISlideSize`](/slides/python-net/hi/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hi/aspose.slides/presentation/notes_size/) | नोट्स स्लाइड आकार वस्तु को लौटाता है।<br/>            केवल-पढ़ने योग्य [`INotesSize`](/slides/python-net/hi/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hi/aspose.slides/presentation/layout_slides/) | प्रस्तुति में परिभाषित सभी लेआउट स्लाइडों की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGlobalLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hi/aspose.slides/presentation/masters/) | प्रस्तुति में परिभाषित सभी मास्टर स्लाइडों की सूची लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterSlideCollection`](/slides/python-net/hi/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hi/aspose.slides/presentation/master_notes_slide_manager/) | नोट्स मास्टर प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterNotesSlideManager`](/slides/python-net/hi/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hi/aspose.slides/presentation/master_handout_slide_manager/) | हैंडआउट मास्टर प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterHandoutSlideManager`](/slides/python-net/hi/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hi/aspose.slides/presentation/fonts_manager/) | फ़ॉन्ट प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IFontsManager`](/slides/python-net/hi/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hi/aspose.slides/presentation/default_text_style/) | शेप्स के लिए डिफ़ॉल्ट टेक्स्ट शैली को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hi/aspose.slides/presentation/comment_authors/) | टिप्पणी लेखकों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICommentAuthorCollection`](/slides/python-net/hi/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hi/aspose.slides/presentation/document_properties/) | DocumentProperties वस्तु को लौटाता है जिसमें मानक और अनुकूलित दस्तावेज़ गुण होते हैं।<br/>            केवल-पढ़ने योग्य [`IDocumentProperties`](/slides/python-net/hi/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hi/aspose.slides/presentation/images/) | प्रस्तुति में सभी चित्रों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IImageCollection`](/slides/python-net/hi/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hi/aspose.slides/presentation/audios/) | प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAudioCollection`](/slides/python-net/hi/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hi/aspose.slides/presentation/videos/) | प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IVideoCollection`](/slides/python-net/hi/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/hi/aspose.slides/presentation/slide_show_settings/) | प्रस्तुति के स्लाइड शो सेटिंग्स को लौटाता है। |
| [`digital_signatures`](/slides/python-net/hi/aspose.slides/presentation/digital_signatures/) | प्रस्तुति पर हस्ताक्षर करने के लिए उपयोग किए गए हस्ताक्षर का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IDigitalSignatureCollection`](/slides/python-net/hi/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/presentation/custom_data/) | प्रस्तुति का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/hi/aspose.slides/presentation/all_custom_xml_parts/) | प्रस्तुति में सभी कस्टम डेटा भाग लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomXmlPart`](/slides/python-net/hi/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/hi/aspose.slides/presentation/vba_project/) | प्रस्तुति मैक्रोज़ के साथ VBA प्रोजेक्ट को प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें [`IVbaProject`](/slides/python-net/hi/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/presentation/hyperlink_queries/) | सभी प्रस्तुति स्लाइडों में सम्मिलित सभी हाइपरलिंक्स तक आसान पहुंच प्रदान करता है (मास्टर, लेआउट, नोट्स स्लाइड में नहीं)।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hi/aspose.slides/presentation/view_properties/) | प्रस्तुति-व्यापी दृश्य गुण प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IViewProperties`](/slides/python-net/hi/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hi/aspose.slides/presentation/first_slide_number/) | प्रस्तुति में पहली स्लाइड संख्या को दर्शाता है |
| [`sensitivity_labels`](/slides/python-net/hi/aspose.slides/presentation/sensitivity_labels/) | प्रस्तुति दस्तावेज़ पर लागू संवेदनशीलता लेबल का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISensitivityLabelCollection`](/slides/python-net/hi/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/hi/aspose.slides/presentation/source_format/) | प्रस्तुति किस फ़ॉर्मेट से लोड हुई, इस बारे में जानकारी लौटाता है।<br/>            केवल-पढ़ने योग्य [`SourceFormat`](/slides/python-net/hi/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/hi/aspose.slides/presentation/master_theme/) | मास्टर थीम को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterTheme`](/slides/python-net/hi/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/hi/aspose.slides/presentation/presentation/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [`save(self, stream, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में स्ट्रिम में सहेजता है। |
| [`save(self, fname, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रिम में सहेजता है। |
| [`save(self, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | प्रस्तुति की सभी स्लाइडों को XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में सहेजता है। |
| [`save(self, fname, slides, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | प्रस्तुति की निर्दिष्ट स्लाइडों को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | प्रस्तुति की निर्दिष्ट स्लाइडों को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [`save(self, stream, slides, format)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | प्रस्तुति की निर्दिष्ट स्लाइडों को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में स्ट्रिम में सहेजता है। |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | प्रस्तुति की निर्दिष्ट स्लाइडों को पृष्ठ संख्या बनाए रखते हुए निर्दिष्ट फ़ॉर्मेट में स्ट्रिम में सहेजता है। |
| [`get_images(self, options)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | प्रस्तुति की सभी स्लाइडों के लिए Image ऑब्जेक्ट्स लौटाता है। |
| [`get_images(self, options, slides)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | कस्टम स्केलिंग के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | कस्टम स्केलिंग के साथ प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [`get_images(self, options, image_size)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | निर्दिष्ट आकार के साथ प्रस्तुति की सभी स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | निर्दिष्ट आकार के साथ प्रस्तुति की निर्दिष्ट स्लाइडों के लिए थंबनेल Image ऑब्जेक्ट्स लौटाता है। |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hi/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hi/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है। |
| [`get_slide_by_id(self, id)`](/slides/python-net/hi/aspose.slides/presentation/get_slide_by_id/#int) | Id द्वारा Slide, MasterSlide या LayoutSlide लौटाता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/presentation/join_portions_with_same_formatting/#) | सभी स्लाइडों में सभी स्वीकार्य शैप्स के सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hi/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है। |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hi/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | निर्दिष्ट पाठ की सभी घटनाओं को दूसरे निर्दिष्ट पाठ से बदलता है। |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hi/aspose.slides/presentation/replace_regex/#str-str) | नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है। |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/hi/aspose.slides/presentation/refresh_charts_data/#bool) | प्रस्तुति में सभी चार्ट्स के डेटा को उनके स्रोत वर्कबुक से पुनः लोड करता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)