---
title: GroupShape class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/groupshape/
---
## GroupShape क्लास

स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।

**विरासत:**[`GroupShape`](/slides/python-net/hi/aspose.slides/groupshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

GroupShape प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/groupshape/is_text_holder/) | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/groupshape/placeholder/) | आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति के पास प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/groupshape/custom_data/) | आकृति के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/groupshape/raw_frame/) | कच्चे आकृति फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/groupshape/frame/) | आकृति फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/groupshape/line_format/) | आकृति के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ वाला LineFormat ऑब्जेक्ट लौटाता है।<br/>            ध्यान दें: GroupShape ऑब्जेक्ट्स के लिए None लौटाता है क्योंकि उनके पास लाइन प्रॉपर्टीज़ नहीं होते।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/groupshape/three_d_format/) | आकृति के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ वाला ThreeDFormat ऑब्जेक्ट लौटाता है।<br/>            ध्यान दें: कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज़ नहीं होते।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/groupshape/effect_format/) | आकृति पर लागू पिक्सेल इफ़ेक्ट्स वाला EffectFormat ऑब्जेक्ट लौटाता है।<br/>            ध्यान दें: कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होते।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/groupshape/fill_format/) | आकृति के लिए फील फॉर्मेटिंग प्रॉपर्टीज़ वाला FillFormat ऑब्जेक्ट लौटाता है।<br/>            ध्यान दें: कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें फ़िल प्रॉपर्टीज़ नहीं होते।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/groupshape/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/groupshape/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/groupshape/hyperlink_manager/) | हाइपरलिंक मैनेजर लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/groupshape/hidden/) | निर्धारित करता है कि आकृति छिपी हुई है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/groupshape/z_order_position/) | z-क्रम में आकृति की स्थिति लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे की आकृति लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-क्रम के सामने की आकृति लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/groupshape/connection_site_count/) | आकृति पर कनेक्शन साइट्स की संख्या लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/groupshape/rotation/) | निर्दिष्ट आकृति को z-एक्सिस के चारों ओर घुमाने के डिग्री की संख्या लौटाता है या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगामी घूर्णन दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/groupshape/x/) | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को बिंदुओं में मापते हुए प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/groupshape/y/) | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को बिंदुओं में मापते हुए प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/groupshape/width/) | आकृति की चौड़ाई को बिंदुओं में मापते हुए प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/groupshape/height/) | आकृति की ऊँचाई को बिंदुओं में मापते हुए प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/groupshape/black_white_mode/) | प्रॉपर्टी निर्दिष्ट करती है कि आकृति काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/groupshape/unique_id/) | एक आंतरिक, प्रस्तुति-स्कोपेड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग करने के लिए बनाया गया है।<br/>            क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी अनन्य कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/groupshape/office_interop_shape_id/) | स्लाइड-स्कोपेड एक अनन्य पहचानकर्ता लौटाता है जो आकृति के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/groupshape/alternative_text/) | आकृति से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/groupshape/alternative_text_title/) | आकृति से जुड़ी वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/groupshape/name/) | आकृति का नाम लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/groupshape/is_decorative/) | विकल्प 'Mark as decorative' प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/groupshape/shape_lock/) | आकृति के लॉक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShapeLock`](/slides/python-net/hi/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/groupshape/is_grouped/) | निर्धारित करता है कि आकृति समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/groupshape/parent_group/) | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/groupshape/slide/) | आकृति की पैरेंट स्लाइड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/groupshape/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/hi/aspose.slides/groupshape/group_shape_lock/) | आकृति के लॉक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShapeLock`](/slides/python-net/hi/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/hi/aspose.slides/groupshape/shapes/) | समूह के अंदर की आकृतियों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/groupshape/get_image/#) | आकृति थंबनेल लौटाता है।<br/>            ShapeThumbnailBounds.Shape आकृति थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | आकृति थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/groupshape/write_as_svg/#iorawiobase) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/groupshape/remove_placeholder/#) | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/groupshape/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर के गुण सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/groupshape/get_base_placeholder/#) | एक बुनियादी प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से आकृति जो वर्तमान आकृति से विरासत में मिली है)।<br/>            यदि वर्तमान आकृति विरासत में नहीं है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/groupshape/get_visual_bounds/#) | रेंडर की गई सामग्री से गणना किए गए आकृति के दृश्य बाउंड्स प्राप्त करता है। |

### देखें भी
* क्लास [`GroupShape`](/slides/python-net/hi/aspose.slides/groupshape)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)