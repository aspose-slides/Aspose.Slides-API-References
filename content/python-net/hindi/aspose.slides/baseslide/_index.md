---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/baseslide/
---
## BaseSlide क्लास

सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।

BaseSlide प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/baseslide/shapes/) | स्लाइड के आकार लौटाता है।<br/>            केवल पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)। |
| [`controls`](/slides/python-net/hi/aspose.slides/baseslide/controls/) | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection)। |
| [`name`](/slides/python-net/hi/aspose.slides/baseslide/name/) | स्लाइड का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`slide_id`](/slides/python-net/hi/aspose.slides/baseslide/slide_id/) | स्लाइड की ID लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/baseslide/custom_data/) | स्लाइड की कस्टम डेटा लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`timeline`](/slides/python-net/hi/aspose.slides/baseslide/timeline/) | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline)। |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/baseslide/slide_show_transition/) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जो जानकारी रखता है<br/>            कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है।<br/>            केवल पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition)। |
| [`background`](/slides/python-net/hi/aspose.slides/baseslide/background/) | स्लाइड की पृष्ठभूमि लौटाता है।<br/>            केवल पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground)। |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/baseslide/hyperlink_queries/) | समावेशित हाइपरलिंक तक आसान पहुंच प्रदान करता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries)। |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/baseslide/show_master_shapes/) | निर्दिष्ट करता है कि मास्टर स्लाइड पर के आकार स्लाइड्स पर दिखाए जाने चाहिए या नहीं।<br/>            मास्टर स्लाइड स्वयं के लिए यह गुण हमेशा `false` लौटाता है।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`presentation`](/slides/python-net/hi/aspose.slides/baseslide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`slide`](/slides/python-net/hi/aspose.slides/baseslide/slide/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/baseslide/join_portions_with_same_formatting/#) | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/baseslide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं।<br/>            लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है।<br/>            दो स्लाइड समान मानी जाती हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स इत्यादि समान हों। तुलना में अद्वितीय पहचानकर्ता मूल्यों जैसे SlideId और गतिशील सामग्री जैसे तिथि प्लेसहोल्डर में वर्तमान तिथि मान को ध्यान में नहीं रखा जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/baseslide/create_theme_effective/#) | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/baseslide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की प्रथम उपस्थिति खोजता है। |

### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)