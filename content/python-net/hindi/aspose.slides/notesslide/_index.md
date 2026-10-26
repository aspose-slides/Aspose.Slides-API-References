---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/notesslide/
---
## NotesSlide वर्ग

प्रेज़ेंटेशन में एक नोट्स स्लाइड को दर्शाता है।

**विरासत:**[`NotesSlide`](/slides/python-net/hi/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)

NotesSlide प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shapes`](/slides/python-net/hi/aspose.slides/notesslide/shapes/) | स्लाइड के शैप्स को लौटाता है।<br/>            केवल पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hi/aspose.slides/notesslide/controls/) | स्लाइड पर ActiveX नियंत्रकों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IControlCollection`](/slides/python-net/hi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hi/aspose.slides/notesslide/name/) | स्लाइड का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`slide_id`](/slides/python-net/hi/aspose.slides/notesslide/slide_id/) | स्लाइड की ID लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`custom_data`](/slides/python-net/hi/aspose.slides/notesslide/custom_data/) | स्लाइड का कस्टम डेटा लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hi/aspose.slides/notesslide/timeline/) | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`IAnimationTimeLine`](/slides/python-net/hi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hi/aspose.slides/notesslide/slide_show_transition/) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जो स्लाइड शो के दौरान निर्दिष्ट स्लाइड के आगे बढ़ने की जानकारी रखता है।<br/>            केवल पढ़ने योग्य [`ISlideShowTransition`](/slides/python-net/hi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hi/aspose.slides/notesslide/background/) | स्लाइड की पृष्ठभूमि लौटाता है।<br/>            केवल पढ़ने योग्य [`IBackground`](/slides/python-net/hi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hi/aspose.slides/notesslide/hyperlink_queries/) | सम्मिलित हाइपरलिंक्स तक आसान पहुँच प्रदान करता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkQueries`](/slides/python-net/hi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hi/aspose.slides/notesslide/show_master_shapes/) | निर्दिष्ट करता है कि मास्टर स्लाइड पर शैप्स को स्लाइड्स पर दिखाया जाए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`presentation`](/slides/python-net/hi/aspose.slides/notesslide/presentation/) | IPresentation इंटरफ़ेस लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hi/aspose.slides/notesslide/header_footer_manager/) | नोट्स स्लाइड के HeaderFooter प्रबंधक को लौटाता है।<br/>            केवल पढ़ने योग्य [`INotesSlideHeaderFooterManager`](/slides/python-net/hi/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/hi/aspose.slides/notesslide/notes_text_frame/) | यदि मौजूद हो तो नोट्स के टेक्स्ट के साथ एक TextFrame लौटाता है।<br/>            केवल पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/hi/aspose.slides/notesslide/theme_manager/) | ओवरराइडिंग थीम प्रबंधक लौटाता है।<br/>            केवल पढ़ने योग्य [`IOverrideThemeManager`](/slides/python-net/hi/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/hi/aspose.slides/notesslide/parent_slide/) | पैरेंट स्लाइड लौटाता है।<br/>            केवल पढ़ने योग्य [`ISlide`](/slides/python-net/hi/aspose.slides/islide). |
| [`slide`](/slides/python-net/hi/aspose.slides/notesslide/slide/) |  |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hi/aspose.slides/notesslide/join_portions_with_same_formatting/#) | सभी स्वीकार्य आकारों में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hi/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | सभी स्वीकार्य आकारों में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [`equals(self, slide)`](/slides/python-net/hi/aspose.slides/notesslide/equals/#ibaseslide) | निर्धारित करता है कि दो IBaseSlide इंस्टेंस समान हैं या नहीं।<br/>            लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है।<br/>            दो स्लाइड समान होते हैं यदि सभी शैप्स, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान को नहीं माना जाता। |
| [`create_theme_effective(self)`](/slides/python-net/hi/aspose.slides/notesslide/create_theme_effective/#) | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hi/aspose.slides/notesslide/find_shape_by_alt_text/#str) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले शैप की पहली उपस्थिति को खोजता है। |


### संबंधित देखें
* वर्ग [`BaseSlide`](/slides/python-net/hi/aspose.slides/baseslide)
* वर्ग [`NotesSlide`](/slides/python-net/hi/aspose.slides/notesslide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)