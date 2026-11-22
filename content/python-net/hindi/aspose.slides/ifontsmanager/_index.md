---
title: IFontsManager class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ifontsmanager/
---
## IFontsManager वर्ग

प्रस्तुति में फ़ॉन्ट्स का प्रबंधन करता है।

IFontsManager प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hi/aspose.slides/ifontsmanager/font_subst_rule_list/) | रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन<br/>पढ़ें/लिखें [`IFontSubstRuleCollection`](/slides/python-net/hi/aspose.slides/ifontsubstrulecollection)। |
| [`font_fall_back_rules_collection`](/slides/python-net/hi/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | फ़ॉन्ट फ़ॉलबैक नियमों का उपयोगकर्ता संग्रह दर्शाता है जो फ़ॉन्ट संग्रहों का प्रबंधन करता है ताकि फ़ॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन हो सके<br/>पढ़ें/लिखें [`IFontFallBackRulesCollection`](/slides/python-net/hi/aspose.slides/ifontfallbackrulescollection)। |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/hi/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | निर्दिष्ट करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स की तुलना में पंजीकृत फ़ॉन्ट्स को प्राथमिकता दी जानी चाहिए या नहीं।<br/>सक्षम होने पर, निर्यात के दौरान मेल खाने वाले एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है। |

## मेथड

| मेथड | विवरण |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_substitutions/#) | प्रस्तुति के रेंडरिंग के दौरान बदल दिए जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है। |
| [`get_substitutions(self, slides)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_substitutions/#listint) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदल दिए जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है।<br/>ध्यान रखें कि किसी भी फ़ॉन्ट को कॉपी करते समय अधिकांश फ़ॉन्ट कॉपीराइटेड होते हैं। सबसे पहले फ़ॉन्ट का लाइसेंस खोजें<br/>फ़ॉन्ट को अग्रिम रूप से और सत्यापित करें कि उन्हें दूसरे मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से एम्बेडेड है तो ArgumentException फेंकी जा सकती है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है।<br/>ध्यान रखें कि किसी भी फ़ॉन्ट को जोड़ते समय अधिकांश फ़ॉन्ट कॉपीराइटेड होते हैं। सबसे पहले फ़ॉन्ट का लाइसेंस खोजें<br/>फ़ॉन्ट को अग्रिम रूप से और सत्यापित करें कि उन्हें दूसरे मशीन में स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से एम्बेडेड है तो ArgumentException फेंकी जा सकती है। |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | प्रस्तुति में फ़ॉन्ट को बदलें |
| [`replace_font(self, subst_rule)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | प्रस्तुति में फ़ॉन्ट को [`IFontSubstRule`](/slides/python-net/hi/aspose.slides/ifontsubstrule) में प्रदान की गई जानकारी का उपयोग करके बदलें |
| [`replace_font(self, subst_rules)`](/slides/python-net/hi/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | प्रस्तुति में फ़ॉन्ट को [`IFontSubstRule`](/slides/python-net/hi/aspose.slides/ifontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करके बदलें |
| [`get_fonts(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_fonts/#) | प्रस्तुति में उपयोग किए गए फ़ॉन्ट्स को लौटाता है |
| [`get_embedded_fonts(self)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_embedded_fonts/#) | प्रस्तुति में एम्बेडेड फ़ॉन्ट्स को लौटाता है |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hi/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | एम्बेडेड फ़ॉन्ट को हटाता है |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाला बाइट ऐरे प्राप्त करता है। |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hi/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | दिए गए बाइट ऐरे और फ़ॉन्ट नाम से फ़ॉन्ट का एम्बेडिंग स्तर निर्धारित करता है। |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)