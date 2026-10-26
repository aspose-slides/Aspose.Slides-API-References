---
title: Slide class
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slide/
---
## Slide क्लास

एक प्रस्तुति में slide का प्रतिनिधित्व करता है।

**विरासत:**[`Slide`](/slides/python-net/hi/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)

Slide प्रकार निम्नलिखित सदस्यों को उजागर करता है।

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/slide/shapes/) | एक slide के shapes लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hi/aspose.slides/slide/controls/) | एक slide पर ActiveX controls के संग्रह को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hi/aspose.slides/slide/name/) | एक slide का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`slide_id`](/slides/python-net/hi/aspose.slides/slide/slide_id/) | एक slide का ID लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`custom_data`](/slides/python-net/hi/aspose.slides/slide/custom_data/) | slide के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hi/aspose.slides/slide/timeline/) | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/slide/slide_show_transition/) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें जानकारी होती है<br/>            कि निर्दिष्ट slide स्लाइड शो के दौरान कैसे आगे बढ़ता है।<br/>            केवल-पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hi/aspose.slides/slide/background/) | slide की पृष्ठभूमि लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/slide/hyperlink_queries/) | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/slide/show_master_shapes/) | निर्धारित करता है कि master slide पर shapes स्लाइड्स पर दिखाए जाएँ या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`presentation`](/slides/python-net/hi/aspose.slides/slide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/slide/header_footer_manager/) | slide के HeaderFooter प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ISlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/slide/theme_manager/) | ओवरराइडिंग थीम मैनेजर को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IOverrideThemeManager`](/slides/python-net/hi/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/hi/aspose.slides/slide/slide_number/) | slide की संख्या लौटाता है।<br/>            [`Presentation.slides`](/slides/python-net/hi/aspose.slides/presentation/slides) संग्रह में slide का इंडेक्स हमेशा SlideNumber - Presentation.FirstSlideNumber के बराबर होता है।<br/>            पढ़ने/लिखने योग्य **int**. |
| [`hidden`](/slides/python-net/hi/aspose.slides/slide/hidden/) | निर्धारित करता है कि निर्दिष्ट slide स्लाइड शो के दौरान छिपा है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`layout_slide`](/slides/python-net/hi/aspose.slides/slide/layout_slide/) | वर्तमान slide के लिए layout slide लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/hi/aspose.slides/slide/notes_slide_manager/) | नोट्स slide तक पहुँच की अनुमति देता है, इसे जोड़ता और हटाता है।<br/>            केवल-पढ़ने योग्य [`INotesSlideManager`](/slides/python-net/hi/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/hi/aspose.slides/slide/slide/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/slide/join_portions_with_same_formatting/#) | सभी स्वीकार्य shapes में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | सभी स्वीकार्य shapes में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/slide/get_image/#float-float) | कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/slide/get_image/#) | एक Thumbnail Image ऑब्जेक्ट लौटाता है (वास्तविक आकार का 20%)। |
| [`get_image(self, image_size)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidessize) | निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | निर्दिष्ट पैरामीटर के साथ एक Thumbnail tiff इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, image_size)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/slide/write_as_svg/#iorawiobase) | slide की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | slide की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/slide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide इंस्टेंस समान हैं या नहीं।<br/>            लौटाया गया मान slide की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है।<br/>            दो slides समान होते हैं यदि सभी shapes, styles, texts, animation और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान को नहीं माना जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/slide/create_theme_effective/#) | इस slide के लिए प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/slide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक पाठ वाले shape की पहली घटना खोजता है। |
| [`write_as_emf(self, stream)`](/slides/python-net/hi/aspose.slides/slide/write_as_emf/#iorawiobase) | slide की सामग्री को EMF फ़ाइल के रूप में सहेजता है। |
| [`remove(self)`](/slides/python-net/hi/aspose.slides/slide/remove/#) | presentation से slide को हटाता है। |
| [`reset(self)`](/slides/python-net/hi/aspose.slides/slide/reset/#) | LayoutSlide पर प्रोटोटाइप वाले प्रत्येक shape की स्थिति, आकार और फ़ॉर्मेटिंग को रीसेट करता है। |
| [`get_slide_comments(self, author)`](/slides/python-net/hi/aspose.slides/slide/get_slide_comments/#icommentauthor) | विशिष्ट लेखक द्वारा जोड़े गए सभी slide टिप्पणियों को लौटाता है। |

### देखें
* क्लास [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)
* क्लास [`Slide`](/slides/python-net/hi/aspose.slides/slide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)