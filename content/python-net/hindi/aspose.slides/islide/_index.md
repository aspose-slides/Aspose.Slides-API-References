---
title: ISlide class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islide/
---
## ISlide क्लास

एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।

ISlide टाइप निम्न सदस्य प्रदर्शित करता है:

## गुण

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            केवल पढ़ने योग्य [`ISlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/hi/aspose.slides/islide/slide_number/) | स्लाइड की संख्या लौटाता है।<br/>            [`IPresentation.slides`](/slides/python-net/hi/aspose.slides/ipresentation/slides) संग्रह में स्लाइड का इंडेक्स हमेशा SlideNumber - 1 के बराबर होता है।<br/>            पढ़ने/लिखने योग्य **int**. |
| [`hidden`](/slides/python-net/hi/aspose.slides/islide/hidden/) | निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`layout_slide`](/slides/python-net/hi/aspose.slides/islide/layout_slide/) | वर्तमान स्लाइड के लिए लेआउट स्लाइड को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`ILayoutSlide`](/slides/python-net/hi/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/hi/aspose.slides/islide/notes_slide_manager/) | नोट्स स्लाइड तक पहुंच की अनुमति देता है, इसे जोड़ता और हटाता है।<br/>            केवल पढ़ने योग्य [`INotesSlideManager`](/slides/python-net/hi/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/hi/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/hi/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/hi/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/hi/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/hi/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/hi/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/hi/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/islide/theme_manager/) |  |

## मेथड्स

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/islide/get_image/#float-float) | कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/islide/get_image/#) | थंबनेल इमेज ऑब्जेक्ट लौटाता है (वास्तविक आकार का 20%). |
| [`get_image(self, image_size)`](/slides/python-net/hi/aspose.slides/islide/get_image/#asposepydrawingsize) | निर्दिष्ट आकार के साथ एक इमेज ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | निर्दिष्ट पैरामीटर्स के साथ थंबनेल TIFF बिटमैप ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options)`](/slides/python-net/hi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | कस्टम स्केलिंग के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [`get_image(self, options, image_size)`](/slides/python-net/hi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | निर्दिष्ट आकार के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/islide/write_as_svg/#iorawiobase) | स्लाइड कंटेंट को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | स्लाइड कंटेंट को SVG फ़ाइल के रूप में सहेजता है। |
| [`get_slide_comments(self, author)`](/slides/python-net/hi/aspose.slides/islide/get_slide_comments/#icommentauthor) | विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणियां लौटाता है। |
| [`write_as_emf(self, stream)`](/slides/python-net/hi/aspose.slides/islide/write_as_emf/#iorawiobase) | स्लाइड कंटेंट को EMF फ़ाइल के रूप में सहेजता है। |
| [`remove(self)`](/slides/python-net/hi/aspose.slides/islide/remove/#) | प्रस्तुति से स्लाइड हटाता है। |
| [`reset(self)`](/slides/python-net/hi/aspose.slides/islide/reset/#) | LayoutSlide पर प्रोटोटाइप वाले हर शेप की स्थिति, आकार और फॉर्मेटिंग रीसेट करता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/islide/create_theme_effective/#) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)