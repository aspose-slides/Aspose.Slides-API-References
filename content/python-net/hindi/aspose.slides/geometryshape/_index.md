---
title: GeometryShape class
second_title: Aspose.Slides for Python के माध्यम से .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/geometryshape/
---
## GeometryShape क्लास

सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।

**विरासत:**[`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

GeometryShape प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/geometryshape/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/geometryshape/placeholder/) | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/geometryshape/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/geometryshape/raw_frame/) | कच्चे आकार फ्रेम के गुणों को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/geometryshape/frame/) | आकार फ्रेम के गुणों को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/geometryshape/line_format/) | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं।<br/>            नोट: कुछ प्रकार के आकार जिनमें लाइन गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/geometryshape/three_d_format/) | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3डी इफ़ेक्ट गुण होते हैं।<br/>            नोट: कुछ प्रकार के आकार जिनमें 3डी गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/geometryshape/effect_format/) | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं।<br/>            नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/geometryshape/fill_format/) | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए फ़िल फ़ॉर्मेटिंग गुण होते हैं।<br/>            नोट: कुछ प्रकार के आकार जिनमें फ़िल गुण नहीं होते, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/geometryshape/hyperlink_click/) | माउस क्लिक के लिए निर्धारित हाइपरलिंक को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/geometryshape/hyperlink_mouse_over/) | माउस ओवर के लिए निर्धारित हाइपरलिंक को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/geometryshape/hyperlink_manager/) | हाइपरलिंक प्रबंधक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/geometryshape/hidden/) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं।<br/>            पढ़ें/लिखें **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/geometryshape/z_order_position/) | z-क्रम में आकार की स्थिति लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे वाले आकार को लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-क्रम के सामने वाले आकार को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/geometryshape/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/geometryshape/rotation/) | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या को प्राप्त करता है या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है।<br/>            पढ़ें/लिखें **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/geometryshape/x/) | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ें/लिखें **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/geometryshape/y/) | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ें/लिखें **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/geometryshape/width/) | आकार की चौड़ाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ें/लिखें **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/geometryshape/height/) | आकार की ऊँचाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ें/लिखें **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/geometryshape/black_white_mode/) | गुण यह निर्दिष्ट करता है कि आकार काले-और-सफेद डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ें/लिखें [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/geometryshape/unique_id/) | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखिए [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/geometryshape/office_interop_shape_id/) | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखिए [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/geometryshape/alternative_text/) | आकार से संबंधित वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/geometryshape/alternative_text_title/) | आकार से संबंधित वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/geometryshape/name/) | आकार के नाम को प्राप्त करता है या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें।<br/>            पढ़ें/लिखें **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/geometryshape/is_decorative/) | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है<br/>            पढ़ें/लिखें **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/geometryshape/shape_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseShapeLock`](/slides/python-net/hi/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/geometryshape/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/geometryshape/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/geometryshape/slide/) | आकार की पैरेंट स्लाइड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/geometryshape/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hi/aspose.slides/geometryshape/shape_style/) | आकार के स्टाइल ऑब्जेक्ट को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type/) | ज्यामिति प्रीसेट प्रकार को प्राप्त करता है या सेट करता है।<br/>            नोट: मान बदलने पर सभी एडजस्टमेंट मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे।<br/>            पढ़ें/लिखें [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hi/aspose.slides/geometryshape/adjustments/) | आकार के एडजस्टमेंट मानों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection). |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/geometryshape/get_image/#) | आकार थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/geometryshape/remove_placeholder/#) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/geometryshape/get_base_placeholder/#) | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (वर्तमान आकार जिस लेआउट और/या मास्टर स्लाइड से विरासत में मिला है)।<br/>            यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/geometryshape/get_visual_bounds/#) | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/geometryshape/get_geometry_paths/#) | ज्यामितीय आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | आकार की ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ<br/>             ऊपर कोने के सापेक्ष होने चाहिए।<br/>             आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | आकार की ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की एरे से अपडेट करता है। निर्देशांक आकार के बाएँ<br/>             ऊपर कोने के सापेक्ष होने चाहिए।<br/>             आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/geometryshape/create_shape_elements/#) | आकार के तत्वों की एरे बनाता और लौटाता है। |

### देखें भी
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)