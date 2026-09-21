---
title: IMasterSlide class
second_title: Aspose.Slides के लिए Python, .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/imasterslide/
---
## IMasterSlide क्लास

एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।

IMasterSlide प्रकार निम्न सदस्य उजागर करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/imasterslide/header_footer_manager/) | मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है।<br/>            केवल पढ़ने योग्य [`IMasterSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/hi/aspose.slides/imasterslide/title_style/) | शीर्षक पाठ की शैली लौटाता है।<br/>            केवल पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/hi/aspose.slides/imasterslide/body_style/) | मुख्य पाठ की शैली लौटाता है।<br/>            केवल पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/hi/aspose.slides/imasterslide/other_style/) | अन्य पाठ की शैली लौटाता है।<br/>            केवल पढ़ने योग्य [`ITextStyle`](/slides/python-net/hi/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/hi/aspose.slides/imasterslide/layout_slides/) | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IMasterLayoutSlideCollection`](/slides/python-net/hi/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/hi/aspose.slides/imasterslide/preserve/) | निर्धारित करता है कि क्या संबंधित मास्टर को हटाया जाता है जब सभी<br/>            उस मास्टर के बाद वाली स्लाइड्स हटाई जाती हैं।<br/>            नोट: Aspose.Slides कभी भी स्वयं किसी अनउपयोगी मास्टर को नहीं हटाएगा,<br/>            वास्तविक रूप से अनउपयोगी मास्टर को हटाने के लिए **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste** को कॉल करें<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`has_depending_slides`](/slides/python-net/hi/aspose.slides/imasterslide/has_depending_slides/) | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है।<br/>            केवल पढ़ने योग्य **bool**. |
| [`drawing_guides`](/slides/python-net/hi/aspose.slides/imasterslide/drawing_guides/) | मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IDrawingGuidesCollection`](/slides/python-net/hi/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/hi/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/hi/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/hi/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/hi/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/hi/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/hi/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/hi/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/imasterslide/theme_manager/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/hi/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | वर्तमान पर आधारित नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है <br/>            और निर्मित मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [`get_depending_slides(self)`](/slides/python-net/hi/aspose.slides/imasterslide/get_depending_slides/#) | सभी स्लाइड्स की एक एरे लौटाता है, जो इस मास्टर स्लाइड पर निर्भर हैं। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/imasterslide/create_theme_effective/#) |  |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)