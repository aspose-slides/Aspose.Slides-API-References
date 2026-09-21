---
title: MasterSlide class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/masterslide/
---
## MasterSlide क्लास

प्रस्तुति में एक मास्टर स्लाइड का प्रतिनिधित्व करता है।

**विरासत:**[`MasterSlide`](/slides/python-net/hi/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)

MasterSlide प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/masterslide/shapes/) | एक स्लाइड के आकार लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hi/aspose.slides/masterslide/controls/) | एक स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hi/aspose.slides/masterslide/name/) | मास्टर स्लाइड का नाम लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`slide_id`](/slides/python-net/hi/aspose.slides/masterslide/slide_id/) | स्लाइड की ID लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`custom_data`](/slides/python-net/hi/aspose.slides/masterslide/custom_data/) | स्लाइड का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hi/aspose.slides/masterslide/timeline/) | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/masterslide/slide_show_transition/) | Transition ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइडशो के दौरान कैसे आगे बढ़ती है।<br/>            केवल-पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hi/aspose.slides/masterslide/background/) | स्लाइड की पृष्ठभूमि लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/masterslide/hyperlink_queries/) | समाविष्ट हाइपरलिंक तक आसान पहुँच प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/masterslide/show_master_shapes/) | निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइड्स पर दिखाने चाहिए या नहीं।<br/>            मास्टर स्लाइड स्वयं के लिए यह गुण हमेशा `false` लौटाता है।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`presentation`](/slides/python-net/hi/aspose.slides/masterslide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/masterslide/header_footer_manager/) | मास्टर स्लाइड के HeaderFooter प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/hi/aspose.slides/masterslide/title_style/) | शीर्षक पाठ की शैली लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/hi/aspose.slides/masterslide/body_style/) | बॉडी पाठ की शैली लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/hi/aspose.slides/masterslide/other_style/) | अन्य पाठ की शैली लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/hi/aspose.slides/masterslide/layout_slides/) | इस मास्टर स्लाइड के चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/hi/aspose.slides/masterslide/preserve/) | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद आने वाले सभी स्लाइड हटाए जाएँ।<br/>            नोट: Aspose.Slides स्वतः किसी भी अनउपयोगित मास्टर को नहीं हटाएगा, वास्तव में अनउपयोगित मास्टर हटाने के लिए **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** को कॉल करें<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`has_depending_slides`](/slides/python-net/hi/aspose.slides/masterslide/has_depending_slides/) | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/masterslide/theme_manager/) | थीम प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IMasterThemeManager`](/slides/python-net/hi/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/hi/aspose.slides/masterslide/drawing_guides/) | मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IDrawingGuidesCollection`](/slides/python-net/hi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/hi/aspose.slides/masterslide/slide/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/masterslide/join_portions_with_same_formatting/#) | सभी अनुच्छेदों और सभी स्वीकार्य आकारों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | सभी अनुच्छेदों में और सभी स्वीकार्य आकारों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/masterslide/equals/#ibaseslide) | निर्धारित करता है कि क्या दो IBaseSlide इंस्टेंस समान हैं।<br/>            लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है।<br/>            दो स्लाइड समान होती हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे डेट प्लेसहोल्डर में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/masterslide/create_theme_effective/#) | इस स्लाइड के लिए एक प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/masterslide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली उपस्थिति खोजता है। |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/hi/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | वर्तमान मास्टर स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है <br/>            और बनायी गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [`get_depending_slides(self)`](/slides/python-net/hi/aspose.slides/masterslide/get_depending_slides/#) | एक एरे लौटाता है जिसमें सभी स्लाइड्स होते हैं, जो इस मास्टर स्लाइड पर निर्भर हैं। |

### देखें
* क्लास [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)
* क्लास [`MasterSlide`](/slides/python-net/hi/aspose.slides/masterslide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)