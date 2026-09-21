---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ifontsmanager/
---
## IFontsManager क्लास

प्रस्तुति में फ़ोंट का प्रबंधन करता है।

IFontsManager प्रकार निम्नलिखित सदस्य प्रकट करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hi/aspose.slides/ifontsmanager/font_subst_rule_list/) | रेंडरिंग के समय उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन<br/>            पढ़ना/लिखना [`IFontSubstRuleCollection`](/slides/python-net/hi/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hi/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | उपयोगकर्ता के FontFallBack नियमों का संग्रह जो फ़ॉन्ट के उचित प्रतिस्थापन के लिए fallback कार्यक्षमता द्वारा संग्रहों के प्रबंधन हेतु है<br/>            पढ़ना/लिखना [`IFontFallBackRulesCollection`](/slides/python-net/hi/aspose.slides/ifontfallbackrulescollection). |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_substitutions/#) | प्रस्तुति के रेंडरिंग पर बदलने वाले फ़ॉन्ट की जानकारी प्राप्त करता है। |
| [`get_substitutions(self, slides)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_substitutions/#listint) | निर्दिष्ट स्लाइडों के रेंडरिंग के दौरान बदलने वाले फ़ॉन्ट की जानकारी प्राप्त करता है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | एंबेडेड फ़ॉन्ट जोड़ता है।<br/>            ध्यान रखें कि अधिकांश फ़ॉन्ट कॉपीराइटेड होते हैं। पहले फ़ॉन्ट के लाइसेंस को खोजें <br/>            और जांचें कि क्या इसे दूसरे मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या फ़ॉन्ट पहले से एंबेडेड है तो एक ArgumentException फेंका जा सकता है |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | एंबेडेड फ़ॉन्ट जोड़ता है<br/>            ध्यान रखें कि अधिकांश फ़ॉन्ट कॉपीराइटेड होते हैं। पहले फ़ॉन्ट के लाइसेंस को खोजें <br/>            और जांचें कि क्या इसे दूसरे मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या फ़ॉन्ट पहले से एंबेडेड है तो एक ArgumentException फेंका जा सकता है |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | प्रस्तुति में फ़ॉन्ट बदलें |
| [`replace_font(self, subst_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | प्रस्तुति में फ़ॉन्ट बदलें, जिसमें [`IFontSubstRule`](/slides/python-net/hi/aspose.slides/ifontsubstrule) में प्रदान की गई जानकारी का उपयोग किया गया है |
| [`replace_font(self, subst_rules)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | प्रस्तुति में फ़ॉन्ट बदलें, जहाँ [`IFontSubstRule`](/slides/python-net/hi/aspose.slides/ifontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग किया गया है |
| [`get_fonts(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_fonts/#) | प्रस्तुति में उपयोग किए गए फ़ॉन्ट लौटाता है |
| [`get_embedded_fonts(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_embedded_fonts/#) | प्रस्तुति में एंबेडेड फ़ॉन्ट लौटाता है |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hi/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | एंबेडेड फ़ॉन्ट हटाता है |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाले बाइट एरे को प्राप्त करता है। |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एंबेडिंग स्तर का निर्धारण करता है। |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)