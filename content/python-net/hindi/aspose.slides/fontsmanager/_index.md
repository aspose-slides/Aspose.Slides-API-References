---
title: FontsManager class
second_title: Aspose.Slides फ़ॉर पाइथन वाया .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/fontsmanager/
---
## FontsManager क्लास

प्रेजेंटेशन में फ़ॉन्ट्स का प्रबंधन करता है।

FontsManager टाइप निम्नलिखित सदस्य उजागर करता है:

## प्रॉपर्टी

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hi/aspose.slides/fontsmanager/font_subst_rule_list/) | रेंडरिंग के दौरान उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन।<br/>            पढ़ें/लिखें [`IFontSubstRuleCollection`](/slides/python-net/hi/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hi/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | फ़ॉन्टFallBack नियमों का उपयोगकर्ता संग्रह दर्शाता है जो फ़ॉन्ट्स के संग्रह को फ़ॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन के लिए प्रबंधित करता है<br/>            पढ़ें/लिखें [`IFontFallBackRulesCollection`](/slides/python-net/hi/aspose.slides/ifontfallbackrulescollection). |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_substitutions/#) | प्रेजेंटेशन के रेंडरिंग पर बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [`get_substitutions(self, slides)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_substitutions/#listint) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदलने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है<br/>            फ़ॉन्ट कॉपी करते समय ध्यान रखें कि अधिकांश फ़ॉन्ट कॉपीराइटेड हैं। पहले फ़ॉन्ट का लाइसेंस ढूँढ़ें और सत्यापित करें कि इसे दूसरी मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से एम्बेडेड है तो ArgumentException उत्पन्न हो सकता है |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है<br/>            फ़ॉन्ट कॉपी करते समय ध्यान रखें कि अधिकांश फ़ॉन्ट कॉपीराइटेड हैं। पहले फ़ॉन्ट का लाइसेंस ढूँढ़ें और सत्यापित करें कि इसे दूसरी मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से एम्बेडेड है तो ArgumentException उत्पन्न हो सकता है |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | प्रेजेंटेशन में फ़ॉन्ट बदलें |
| [`replace_font(self, subst_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | प्रेजेंटेशन में फ़ॉन्ट बदलें, जानकारी [`FontSubstRule`](/slides/python-net/hi/aspose.slides/fontsubstrule) में प्रदान की गई है |
| [`replace_font(self, subst_rules)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | प्रेजेंटेशन में फ़ॉन्ट बदलें, जानकारी [`FontSubstRule`](/slides/python-net/hi/aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई है |
| [`get_fonts(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_fonts/#) | प्रेजेंटेशन में उपयोग किए गए फ़ॉन्ट लौटाता है |
| [`get_embedded_fonts(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_embedded_fonts/#) | प्रेजेंटेशन में एम्बेडेड फ़ॉन्ट लौटाता है |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hi/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | एम्बेडेड फ़ॉन्ट हटाता है |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का बाइट एरे प्राप्त करता है |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट के एम्बेडिंग स्तर का निर्धारण करता है |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)