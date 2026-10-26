---
title: Connector class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/connector/
---
## Connector क्लास

एक कनेक्टर का प्रतिनिधित्व करता है।

**विरासत:**[`Connector`](/slides/python-net/hi/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

Connector प्रकार निम्नलिखित सदस्यों को प्रकट करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/connector/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/connector/placeholder/) | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/connector/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/connector/raw_frame/) | मूल आकार फ्रेम की प्रॉपर्टी को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/connector/frame/) | आकार फ्रेम की प्रॉपर्टी को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/connector/line_format/) | आकार के लिए लाइन फॉर्मेट ऑब्जेक्ट को लौटाता है जिसमें लाइन फ़ॉर्मेटिंग प्रॉपर्टी होती हैं।<br/>            नोट: कुछ प्रकार के आकारों के लिए जो लाइन प्रॉपर्टी नहीं रखते, None वापस किया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/connector/three_d_format/) | आकार के लिए ThreeDFormat ऑब्जेक्ट को लौटाता है जिसमें 3D इफ़ेक्ट प्रॉपर्टी होते हैं।<br/>            नोट: कुछ प्रकार के आकारों के लिए जो 3D प्रॉपर्टी नहीं रखते, None वापस किया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/connector/effect_format/) | आकार पर लागू पिक्सेल इफ़ेक्ट्स को सम्मिलित करने वाला EffectFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ प्रकार के आकारों के लिए जो इफ़ेक्ट प्रॉपर्टी नहीं रखते, None वापस किया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/connector/fill_format/) | आकार के लिए FillFormat ऑब्जेक्ट को लौटाता है जिसमें फ़िल फ़ॉर्मेटिंग प्रॉपर्टी होते हैं।<br/>            नोट: कुछ प्रकार के आकारों के लिए जो फ़िल प्रॉपर्टी नहीं रखते, None वापस किया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/connector/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/connector/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/connector/hyperlink_manager/) | हाइपरलिंक प्रबंधक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/connector/hidden/) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/connector/z_order_position/) | आकार की z-क्रम में स्थिति को लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे का आकार देता है,<br/>            और Shapes[Shapes.Count - 1] z-क्रम के आगे का आकार देता है।<br/>            केवल-पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/connector/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/connector/rotation/) | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/connector/x/) | आकार के ऊपरी बाएँ कोने के x-निर्देशांक को पॉइंट में मापे हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/connector/y/) | आकार के ऊपरी बाएँ कोने के y-निर्देशांक को पॉइंट में मापे हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/connector/width/) | आकार की चौड़ाई को पॉइंट में मापे हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/connector/height/) | आकार की ऊँचाई को पॉइंट में मापे हुए लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/connector/black_white_mode/) | यह प्रॉपर्टी निर्धारित करती है कि आकार काली-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/connector/unique_id/) | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**।<br/>            अन्य देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/connector/office_interop_shape_id/) | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल-पढ़ने योग्य **int**।<br/>            अन्य देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/connector/alternative_text/) | आकार से संबंधित वैकल्पिक पाठ को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/connector/alternative_text_title/) | आकार से संबंधित वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/connector/name/) | आकार का नाम लौटाता या सेट करता है।<br/>            None नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान का उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/connector/is_decorative/) | 'सजावटी के रूप में चिह्नित' विकल्प को प्राप्त या सेट करता है<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/connector/shape_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IConnectorLock`](/slides/python-net/hi/aspose.slides/iconnectorlock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/connector/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/connector/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट को लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/connector/slide/) | आकार की पैरेंट स्लाइड को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/connector/presentation/) | स्लाइड की पैरेंट प्रस्तुति को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/connector/shape_style/) | आकार की शैली ऑब्जेक्ट को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/connector/shape_type/) | AutoShape प्रकार को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/connector/adjustments/) | आकार के समायोजन मानों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`connector_lock`](/slides/python-net/hi/aspose.slides/connector/connector_lock/) | कनेक्टर के लॉक को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IConnectorLock`](/slides/python-net/hi/aspose.slides/iconnectorlock)। |
| [`start_shape_connected_to`](/slides/python-net/hi/aspose.slides/connector/start_shape_connected_to/) | कनेक्टर की शुरुआत को संलग्न करने के लिए आकार को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape)। |
| [`end_shape_connected_to`](/slides/python-net/hi/aspose.slides/connector/end_shape_connected_to/) | कनेक्टर के अंत को संलग्न करने के लिए आकार को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape)। |
| [`start_shape_connection_site_index`](/slides/python-net/hi/aspose.slides/connector/start_shape_connection_site_index/) | प्रारंभिक आकार के लिए कनेक्शन साइट का इंडेक्स लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`end_shape_connection_site_index`](/slides/python-net/hi/aspose.slides/connector/end_shape_connection_site_index/) | समाप्ति आकार के लिए कनेक्शन साइट का इंडेक्स लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/connector/get_image/#) | आकार थंबनेल लौटाता है।<br/>            ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/connector/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/connector/remove_placeholder/#) | यह परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/connector/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टी को निर्दिष्ट वाले में सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/connector/get_base_placeholder/#) | बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिससे वर्तमान आकार विरासत में मिला है)।<br/>            यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/connector/get_visual_bounds/#) | आकार की दृश्य सीमा को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/connector/get_geometry_paths/#) | ज्यामिति आकार के पाथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/connector/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकार ज्यामिति को अपडेट करता है। निर्देशांक बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए।<br/>            आकार प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की array से आकार ज्यामिति को अपडेट करता है। निर्देशांक बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए।<br/>            आकार प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/connector/create_shape_elements/#) | आकार के तत्वों की array बनाता और लौटाता है। |
| [`reroute(self)`](/slides/python-net/hi/aspose.slides/connector/reroute/#) | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़ी हुई आकारों के बीच सबसे छोटा संभव पथ ले। |

### देखें
* क्लास [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)