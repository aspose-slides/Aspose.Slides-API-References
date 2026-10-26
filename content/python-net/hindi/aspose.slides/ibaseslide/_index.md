---
title: IBaseSlide class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ibaseslide/
---
## IBaseSlide वर्ग

सभी स्लाइड प्रकारों के लिए सामान्य डेटा को दर्शाता है।

IBaseSlide प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/ibaseslide/shapes/) | स्लाइड की आकृतियों को लौटाता है।<br/>केवल-पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)। |
| [`controls`](/slides/python-net/hi/aspose.slides/ibaseslide/controls/) | स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है।<br/>केवल-पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection)। |
| [`name`](/slides/python-net/hi/aspose.slides/ibaseslide/name/) | स्लाइड का नाम लौटाता है या सेट करता है।<br/>पढ़ने/लिखने योग्य **str**। |
| [`slide_id`](/slides/python-net/hi/aspose.slides/ibaseslide/slide_id/) | स्लाइड की आईडी को लौटाता है।<br/>केवल-पढ़ने योग्य **int**। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/ibaseslide/custom_data/) | स्लाइड के कस्टम डेटा को लौटाता है।<br/>केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`timeline`](/slides/python-net/hi/aspose.slides/ibaseslide/timeline/) | एनिमेशन टाइमलाइन ऑब्जेक्ट को लौटाता है।<br/>केवल-पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline)। |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/ibaseslide/slide_show_transition/) | वह TransitionEx ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है।<br/>केवल-पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition)। |
| [`background`](/slides/python-net/hi/aspose.slides/ibaseslide/background/) | स्लाइड की पृष्ठभूमि को लौटाता है।<br/>केवल-पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground)। |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/ibaseslide/hyperlink_queries/) | सम्मिलित हाइपरलिंक्स तक आसान पहुँच प्रदान करता है।<br/>केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries)। |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/ibaseslide/show_master_shapes/) | निर्धारित करता है कि मास्टर स्लाइड पर आकृतियां स्लाइडों पर दिखनी चाहिए या नहीं।<br/>मास्टर स्लाइड के लिए यह गुण हमेशा `false` लौटाता है।<br/>पढ़ने/लिखने योग्य **bool**। |
| [`slide`](/slides/python-net/hi/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/ibaseslide/presentation/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक पाठ वाली आकृति की पहली उपस्थिति को खोजता है। |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | सभी स्वीकार्य आकृतियों में सभी पैराग्राफ़ में समान स्वरूपण वाले रन को जोड़ता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/ibaseslide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं।<br/>रिटर्न मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है।<br/>दो स्लाइड समान मानी जाती हैं यदि सभी आकृतियां, शैलियां, पाठ, एनिमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे तिथि प्लेसहोल्डर में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)