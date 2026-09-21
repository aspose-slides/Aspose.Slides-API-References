---
title: Slide class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slide/
---
## Slide क्लास

एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।

**Inheritance:**[`Slide`](/slides/python-net/hi/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)

The Slide type exposes the following members:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/slide/shapes/) | स्लाइड के आकार लौटाता है।<br/>            केवल पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)। |
| [`controls`](/slides/python-net/hi/aspose.slides/slide/controls/) | स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है।<br/>            केवल पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection)। |
| [`name`](/slides/python-net/hi/aspose.slides/slide/name/) | स्लाइड का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`slide_id`](/slides/python-net/hi/aspose.slides/slide/slide_id/) | स्लाइड का ID लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/slide/custom_data/) | स्लाइड का कस्टम डेटा लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`timeline`](/slides/python-net/hi/aspose.slides/slide/timeline/) | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline)। |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/slide/slide_show_transition/) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जो यह जानकारी रखता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है।<br/>            केवल पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition)। |
| [`background`](/slides/python-net/hi/aspose.slides/slide/background/) | स्लाइड की बैकग्राउंड लौटाता है।<br/>            केवल पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground)। |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/slide/hyperlink_queries/) | सम्मिलित हाइपरलिंक तक आसान पहुंच प्रदान करता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries)। |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/slide/show_master_shapes/) | निर्धारित करता है कि मास्टर स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`presentation`](/slides/python-net/hi/aspose.slides/slide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/slide/header_footer_manager/) | स्लाइड की HeaderFooter प्रबंधक लौटाता है।<br/>            केवल पढ़ने योग्य [`ISlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/islideheaderfootermanager)। |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/slide/theme_manager/) | ओवरराइडिंग थीम मैनेजर लौटाता है।<br/>            केवल पढ़ने योग्य [`IOverrideThemeManager`](/slides/python-net/hi/aspose.slides.theme/ioverridethememanager)। |
| [`slide_number`](/slides/python-net/hi/aspose.slides/slide/slide_number/) | स्लाइड की संख्या लौटाता है।<br/>            स्लाइड का सूचकांक [`Presentation.slides`](/slides/python-net/hi/aspose.slides/presentation/slides) संग्रह में हमेशा SlideNumber - Presentation.FirstSlideNumber के बराबर होता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`hidden`](/slides/python-net/hi/aspose.slides/slide/hidden/) | निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी हुई है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`layout_slide`](/slides/python-net/hi/aspose.slides/slide/layout_slide/) | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide)। |
| [`notes_slide_manager`](/slides/python-net/hi/aspose.slides/slide/notes_slide_manager/) | नोट्स स्लाइड तक पहुंच की अनुमति देता है, इसे जोड़ता और हटाता है।<br/>            केवल पढ़ने योग्य [`INotesSlideManager`](/slides/python-net/hi/aspose.slides/inotesslidemanager)। |
| [`slide`](/slides/python-net/hi/aspose.slides/slide/slide/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/slide/join_portions_with_same_formatting/#) | सभी उपयुक्त आकारों में सभी पैराग्राफों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | सभी उपयुक्त आकारों में सभी पैराग्राफों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/slide/get_image/#float-float) | कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/slide/get_image/#) | थंबनेल इमेज ऑब्जेक्ट (वास्तविक आकार का 20%) लौटाता है। |
| [`get_image(self, image_size)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposepydrawingsize) | निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | निर्दिष्ट पैरामीटरों के साथ थंबनेल TIFF इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, image_size)`](/slides/python-net/hi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/slide/write_as_svg/#iorawiobase) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/slide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide इंस्टैंस समान हैं या नहीं।<br/>            लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है।<br/>            दो स्लाइड समान होती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/slide/create_theme_effective/#) | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/slide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली उपस्थिति खोजता है। |
| [`write_as_emf(self, stream)`](/slides/python-net/hi/aspose.slides/slide/write_as_emf/#iorawiobase) | स्लाइड सामग्री को EMF फ़ाइल के रूप में सहेजता है। |
| [`remove(self)`](/slides/python-net/hi/aspose.slides/slide/remove/#) | प्रस्तुति से स्लाइड हटाता है। |
| [`reset(self)`](/slides/python-net/hi/aspose.slides/slide/reset/#) | LayoutSlide पर प्रोटोटाइप वाले प्रत्येक आकार की स्थिति, आकार और फ़ॉर्मेटिंग रीसेट करता है। |
| [`get_slide_comments(self, author)`](/slides/python-net/hi/aspose.slides/slide/get_slide_comments/#icommentauthor) | विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणी लौटाता है। |

### संबंधित देखें
* क्लास [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)
* क्लास [`Slide`](/slides/python-net/hi/aspose.slides/slide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)