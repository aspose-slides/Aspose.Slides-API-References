---
title: SmartArtShape class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape क्लास

SmartArt shape का प्रतिनिधित्व करता है

**विरासत:**[`SmartArtShape`](/slides/python-net/hi/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

SmartArtShape प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/is_text_holder/) | निर्धारित करता है कि shape TextHolder_PPT है।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/placeholder/) | shape के लिए placeholder लौटाता है। यदि shape में placeholder नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/custom_data/) | shape का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/raw_frame/) | raw shape frame की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/frame/) | shape frame की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/line_format/) | shape के लिए लाइन फ़ॉर्मैट गुणों को रखने वाले LineFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: कुछ shape प्रकारों के लिए जो लाइन गुण नहीं रखते, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/three_d_format/) | shape के लिए 3d इफ़ेक्ट गुणों को रखने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: कुछ shape प्रकारों के लिए जिनमें 3d गुण नहीं हैं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/effect_format/) | shape पर लागू पिक्सेल प्रभावों को रखने वाले EffectFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: कुछ shape प्रकारों के लिए जिनमें प्रभाव गुण नहीं हैं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/fill_format/) | shape के लिए fill फ़ॉर्मेटिंग गुणों को रखने वाले FillFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: कुछ shape प्रकारों के लिए जिनमें fill गुण नहीं हैं, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/hyperlink_click/) | माउस क्लिक के लिए परिभाषित hyperlink को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित hyperlink को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/hyperlink_manager/) | hyperlink manager को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/hidden/) | निर्धारित करता है कि shape छिपा है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/z_order_position/) | z-क्रम में shape की स्थिति लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे वाले shape को लौटाता है,<br/>            और Shapes[Shapes.Count - 1] आगे वाले shape को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/connection_site_count/) | shape पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/rotation/) | निर्दिष्ट shape के z-अक्ष के चारों ओर घुमाव के डिग्री की संख्या लौटाता है या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान<br/>            उल्टी दिशा में घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/x/) | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/y/) | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/width/) | shape की चौड़ाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/height/) | shape की ऊँचाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/black_white_mode/) | गुण निर्धारित करता है कि shape काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/unique_id/) | add-ins या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः सौंपा जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल तक स्थिर रहता है और<br/>            PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/alternative_text/) | shape से जुड़े वैकल्पिक टेक्स्ट को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/alternative_text_title/) | shape से जुड़े वैकल्पिक टेक्स्ट के शीर्षक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/name/) | shape का नाम लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/is_decorative/) | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/shape_lock/) | shape के locks को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseShapeLock`](/slides/python-net/hi/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/is_grouped/) | निर्धारित करता है कि shape समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/parent_group/) | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/slide/) | shape की पैरेंट स्लाइड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/shape_style/) | shape की स्टाइल ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/shape_type/) | ज्यामिति प्रीसेट प्रकार को लौटाता है या सेट करता है।<br/>            ध्यान दें: मान बदलने पर सभी एडजस्टमेंट मूल्य अपने डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे।<br/>            पढ़ने/लिखने योग्य [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/adjustments/) | shape के एडजस्टमेंट मानों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/text_frame/) | SmartArt shape का टेक्स्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/get_image/#) | shape थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | shape थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/remove_placeholder/#) | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | एक बुनियादी placeholder shape लौटाता है (वर्तमान shape जिस layout और/या master स्लाइड से विरासत में मिला है)।<br/>            यदि वर्तमान shape विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | shape के रेंडर किए गए कंटेंट से गणना किए गए दृश्य बाउंड्स प्राप्त करता है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | ज्यामिति shape के पथ की कॉपी लौटाता है। निर्देशांक shape के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से shape की ज्यामिति अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             shape के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की एरे से shape की ज्यामिति अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             shape के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides.smartart/smartartshape/create_shape_elements/#) | shape के तत्वों की एरे बनाता और लौटाता है। |

### देखें भी
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`SmartArtShape`](/slides/python-net/hi/aspose.slides.smartart/smartartshape)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)