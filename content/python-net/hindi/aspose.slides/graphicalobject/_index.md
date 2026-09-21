---
title: GraphicalObject class
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/graphicalobject/
---
## GraphicalObject क्लास

अव्यवस्थित ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।

**विरासत:**[`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

GraphicalObject प्रकार निम्न सदस्य उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/graphicalobject/is_text_holder/) | निर्धारित करता है कि क्या आकार TextHolder_PPT है।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/graphicalobject/placeholder/) | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/graphicalobject/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/graphicalobject/raw_frame/) | कच्चे shape फ्रेम की गुणों को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/graphicalobject/frame/) | shape फ्रेम की गुणों को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/graphicalobject/line_format/) | आकार के लिए लाइन फ़ॉर्मेट गुणों को रखने वाले LineFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ प्रकार के आकार जिनमें लाइन गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/graphicalobject/three_d_format/) | आकार के लिए 3D प्रभाव गुणों को रखने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/graphicalobject/effect_format/) | आकार पर लागू पिक्सेल प्रभावों को रखने वाले EffectFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ प्रकार के आकार जिनमें प्रभाव गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/graphicalobject/fill_format/) | आकार के लिए भराव फ़ॉर्मेटिंग गुणों को रखने वाले FillFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ प्रकार के आकार जिनमें भराव गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/graphicalobject/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/graphicalobject/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/graphicalobject/hyperlink_manager/) | हाइपरलिंक मैनेजर को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/graphicalobject/hidden/) | निर्धारित करता है कि क्या आकार छुपा हुआ है।<br/>            पढ़ें/लिखें **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/graphicalobject/z_order_position/) | आकार की z-क्रम में स्थिति को लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे वाला आकार लौटाता है,<br/>            और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/graphicalobject/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/graphicalobject/rotation/) | निर्दिष्ट आकार को z-धुरी के चारों ओर घुमाने के डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घूर्णन दर्शाता है।<br/>            पढ़ें/लिखें **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/graphicalobject/x/) | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/graphicalobject/y/) | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/graphicalobject/width/) | आकार की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/graphicalobject/height/) | आकार की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/graphicalobject/black_white_mode/) | प्रॉपर्टी निर्दिष्ट करती है कि आकार काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ें/लिखें [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/graphicalobject/unique_id/) | ऐड-इन या अन्य कोड द्वारा उपयोग हेतु एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/graphicalobject/office_interop_shape_id/) | स्लाइड-स्कोप्ड एक अनोखा पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ के कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/graphicalobject/alternative_text/) | आकार से संबंधित वैकल्पिक टेक्स्ट को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/graphicalobject/alternative_text_title/) | आकार से संबंधित वैकल्पिक टेक्स्ट के शीर्षक को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/graphicalobject/name/) | आकार का नाम लौटाता या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान प्रयोग करें।<br/>            पढ़ें/लिखें **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/graphicalobject/is_decorative/) | 'डेकोरेटिव के रूप में चिह्नित' विकल्प प्राप्त या सेट करता है।<br/>            पढ़ें/लिखें **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/graphicalobject/shape_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/graphicalobject/is_grouped/) | निर्धारित करता है कि क्या आकार समूहित है।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/graphicalobject/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट को लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/graphicalobject/slide/) | आकार की पैरेंट स्लाइड को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/graphicalobject/presentation/) | स्लाइड की पैरेंट प्रेज़ेंटेशन को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides/graphicalobject/graphical_object_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/graphicalobject/get_image/#) | आकार का थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | आकार का थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/graphicalobject/remove_placeholder/#) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/graphicalobject/get_base_placeholder/#) | एक मूलभूत प्लेसहोल्डर आकार लौटाता है (वह आकार जो लेआउट और/या मास्टर स्लाइड से आता है जिससे वर्तमान आकार विरासत में मिला है)।<br/>            यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/graphicalobject/get_visual_bounds/#) | रेंडर्ड सामग्री से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है। |

### देखें

* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)