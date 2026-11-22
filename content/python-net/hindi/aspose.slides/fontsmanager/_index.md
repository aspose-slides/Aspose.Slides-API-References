---
title: FontsManager class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/fontsmanager/
---
## FontsManager कक्षा

Manages fonts across the presentation.

The FontsManager type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hi/aspose.slides/fontsmanager/font_subst_rule_list/) | रेंडरिंग के दौरान उपयोग करने के लिए फ़ॉन्ट प्रतिस्थापन।<br/>            Read/write [`IFontSubstRuleCollection`](/slides/python-net/hi/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hi/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | एक उपयोगकर्ता के FontFallBack नियमों के संग्रह का प्रतिनिधित्व करता है जो उचित प्रतिस्थापन के लिए फ़ॉन्ट संग्रह को प्रबंधित करता है<br/>            Read/write [`IFontFallBackRulesCollection`](/slides/python-net/hi/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/hi/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | निर्दिष्ट करता है कि समान फ़ॉन्ट नाम और शैली वाले एम्बेडेड फ़ॉन्ट्स की तुलना में पंजीकृत फ़ॉन्ट्स को प्राथमिकता देनी चाहिए या नहीं।<br/>            सक्षम होने पर, निर्यात के दौरान मेल खाने वाले एम्बेडेड फ़ॉन्ट्स को अस्थायी रूप से संबंधित पंजीकृत फ़ॉन्ट्स से बदल दिया जाता है। |

## विधियाँ

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_substitutions/#) | प्रेज़ेंटेशन के रेंडरिंग पर प्रतिस्थापित होने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [`get_substitutions(self, slides)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_substitutions/#listint) | निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान प्रतिस्थापित होने वाले फ़ॉन्ट्स की जानकारी प्राप्त करता है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है<br/>            ध्यान रखें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। पहले फ़ॉन्ट की लाइसेंस खोजें और सुनिश्चित करें कि वह अन्य मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से ही एम्बेडेड है तो ArgumentException फेंका जा सकता है। |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | एम्बेडेड फ़ॉन्ट जोड़ता है<br/>            ध्यान रखें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। पहले फ़ॉन्ट की लाइसेंस खोजें और सुनिश्चित करें कि वह अन्य मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है। यदि फ़ॉन्ट डेटा None है या यह फ़ॉन्ट पहले से ही एम्बेडेड है तो ArgumentException फेंका जा सकता है। |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | प्रेज़ेंटेशन में फ़ॉन्ट बदलें |
| [`replace_font(self, subst_rule)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | प्रेज़ेंटेशन में फ़ॉन्ट बदलें, जो [`FontSubstRule`](/slides/python-net/hi/aspose.slides/fontsubstrule) में प्रदान की गई जानकारी का उपयोग करता है |
| [`replace_font(self, subst_rules)`](/slides/python-net/hi/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | प्रेज़ेंटेशन में फ़ॉन्ट बदलें, जो [`FontSubstRule`](/slides/python-net/hi/aspose.slides/fontsubstrule) के संग्रह में प्रदान की गई जानकारी का उपयोग करता है |
| [`get_fonts(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_fonts/#) | प्रेज़ेंटेशन में उपयोग किए गए फ़ॉन्ट्स लौटाता है |
| [`get_embedded_fonts(self)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_embedded_fonts/#) | प्रेज़ेंटेशन में एम्बेडेड फ़ॉन्ट्स लौटाता है |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hi/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | एम्बेडेड फ़ॉन्ट को हटाता है |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाले बाइट ऐरे को पुनः प्राप्त करता है। |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hi/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | दिए गए बाइट ऐरे और फ़ॉन्ट नाम से फ़ॉन्ट का एम्बेडिंग स्तर निर्धारित करता है। |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)