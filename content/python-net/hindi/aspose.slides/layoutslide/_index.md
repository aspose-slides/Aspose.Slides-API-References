---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/layoutslide/
---
## LayoutSlide क्लास

लेआउट स्लाइड का प्रतिनिधित्व करता है।

**विरासत:**[`LayoutSlide`](/slides/python-net/hi/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)

LayoutSlide प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/layoutslide/shapes/) | स्लाइड के आकार लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hi/aspose.slides/layoutslide/controls/) | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hi/aspose.slides/layoutslide/name/) | स्लाइड का नाम लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`slide_id`](/slides/python-net/hi/aspose.slides/layoutslide/slide_id/) | स्लाइड की ID लौटाता है।<br/>            केवल-पढ़ने-योग्य **int**. |
| [`custom_data`](/slides/python-net/hi/aspose.slides/layoutslide/custom_data/) | स्लाइड का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने-योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hi/aspose.slides/layoutslide/timeline/) | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/layoutslide/slide_show_transition/) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें इस बात की जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है।<br/>            केवल-पढ़ने-योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hi/aspose.slides/layoutslide/background/) | स्लाइड की पृष्ठभूमि लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/layoutslide/hyperlink_queries/) | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने-योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/layoutslide/show_master_shapes/) | निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाएँ या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`presentation`](/slides/python-net/hi/aspose.slides/layoutslide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/layoutslide/header_footer_manager/) | लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है।<br/>            केवल-पढ़ने-योग्य [`ILayoutSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/hi/aspose.slides/layoutslide/placeholder_manager/) | लेआउट स्लाइड के प्लेसहोल्डर प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने-योग्य [`ILayoutPlaceholderManager`](/slides/python-net/hi/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/hi/aspose.slides/layoutslide/master_slide/) | लेआउट के लिए मास्टर स्लाइड लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IMasterSlide`](/slides/python-net/hi/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/layoutslide/theme_manager/) | ओवरराइडिंग थीम प्रबंधक लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IOverrideThemeManager`](/slides/python-net/hi/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/hi/aspose.slides/layoutslide/layout_type/) | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है।<br/>            केवल-पढ़ने-योग्य [`SlideLayoutType`](/slides/python-net/hi/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/hi/aspose.slides/layoutslide/has_depending_slides/) | यदि कम से कम एक स्लाइड इस लेआउट स्लाइड पर निर्भर करता है तो true लौटाता है।<br/>            केवल-पढ़ने-योग्य **bool**. |
| [`drawing_guides`](/slides/python-net/hi/aspose.slides/layoutslide/drawing_guides/) | लेआउट स्लाइड के ड्राइंग गाइड का संग्रह लौटाता है।<br/>            केवल-पढ़ने-योग्य [`IDrawingGuidesCollection`](/slides/python-net/hi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/hi/aspose.slides/layoutslide/slide/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/layoutslide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide इंस्टेंस बराबर हैं या नहीं।<br/>            लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है।<br/>            दो स्लाइड बराबर मानी जाती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनिमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अनन्य पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे डेट प्लेसहोल्डर में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/layoutslide/create_theme_effective/#) | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले आकार की पहली घटना खोजता है। |
| [`remove(self)`](/slides/python-net/hi/aspose.slides/layoutslide/remove/#) | प्रेज़ेंटेशन से लेआउट हटाता है। |
| [`get_depending_slides(self)`](/slides/python-net/hi/aspose.slides/layoutslide/get_depending_slides/#) | एक array लौटाता है जिसमें सभी स्लाइड्स शामिल हैं जो इस लेआउट स्लाइड पर निर्भर करती हैं। |

### देखें
* क्लास [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)
* क्लास [`LayoutSlide`](/slides/python-net/hi/aspose.slides/layoutslide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)