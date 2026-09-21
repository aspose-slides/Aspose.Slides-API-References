---
title: Shape class
second_title: Aspose.Slides Python के लिये .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/shape/
---
## Shape क्लास

स्लाइड पर एक आकार का प्रतिनिधित्व करता है।

Shape प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुण

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/shape/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>केवल पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/shape/placeholder/) | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/shape/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/shape/raw_frame/) | कच्चे आकार फ्रेम की गुणधर्मों को प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/shape/frame/) | आकार फ्रेम की गुणधर्मों को प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/shape/line_format/) | LineFormat ऑब्जेक्ट लौटाता है जो आकार के लिए रेखा फ़ॉर्मेटिंग गुणधर्म रखता है।<br/>ध्यान दें: कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें रेखा गुणधर्म नहीं होते।<br/>केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/shape/three_d_format/) | ThreeDFormat ऑब्जेक्ट लौटाता है जो आकार के 3D इफ़ेक्ट गुणधर्म रखता है।<br/>ध्यान दें: कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें 3D गुणधर्म नहीं होते।<br/>केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/shape/effect_format/) | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं।<br/>ध्यान दें: कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें इफ़ेक्ट गुणधर्म नहीं होते।<br/>केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/shape/fill_format/) | FillFormat ऑब्जेक्ट लौटाता है जो आकार के लिए भराव फ़ॉर्मेटिंग गुणधर्म रखता है।<br/>ध्यान दें: कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें भराव गुणधर्म नहीं होते।<br/>केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/shape/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/shape/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/shape/hyperlink_manager/) | हाइपरलिंक मैनेजर को लौटाता है।<br/>केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/shape/hidden/) | निर्धारित करता है कि आकार छुपा हुआ है या नहीं।<br/>पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/shape/z_order_position/) | आकार की z-क्रम में स्थिति लौटाता है।<br/>Shapes[0] z-क्रम के पीछे का आकार लौटाता है,<br/>और Shapes[Shapes.Count - 1] आगे का आकार लौटाता है।<br/>केवल पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/shape/connection_site_count/) | आकार पर मौजूद कनेक्शन साइटों की संख्या लौटाता है।<br/>केवल पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/shape/rotation/) | निर्दिष्ट आकार को z-अक्ष के आसपास घुमाने के डिग्री की संख्या को प्राप्त या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध घड़ी दिशा में घुमाव दर्शाता है।<br/>पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/shape/x/) | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/shape/y/) | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/shape/width/) | आकार की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/shape/height/) | आकार की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/shape/black_white_mode/) | यह गुण निर्धारित करता है कि आकार काले-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा।<br/>पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id/) | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है।<br/>क्योंकि यह मान उपयोगकर्ता या कोड द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>केवल पढ़ने योग्य **int**।<br/>और देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id/) | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल भर अपरिवर्तित रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की सुविधा देता है।<br/>केवल पढ़ने योग्य **int**।<br/>और देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/shape/alternative_text/) | आकार से संबंधित वैकल्पिक पाठ को प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/shape/alternative_text_title/) | आकार से संबंधित वैकल्पिक पाठ का शीर्षक प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/shape/name/) | आकार का नाम प्राप्त या सेट करता है।<br/>None नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग का उपयोग करें।<br/>पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/shape/is_decorative/) | 'Mark as decorative' विकल्प प्राप्त या सेट करता है।<br/>पढ़ने/लिखने योग्य **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/shape/shape_lock/) | आकार के लॉक को लौटाता है।<br/>केवल पढ़ने योग्य [`IBaseShapeLock`](/slides/python-net/hi/aspose.slides/ibaseshapelock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/shape/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>केवल पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/shape/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/shape/slide/) | आकार की पैरेंट स्लाइड को लौटाता है।<br/>केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/shape/presentation/) | स्लाइड की पैरेंट प्रस्तुति को लौटाता है।<br/>केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |

## मेथड्स

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/shape/get_image/#) | आकार थंबनेल लौटाता है।<br/>डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/shape/write_as_svg/#iorawiobase) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/shape/remove_placeholder/#) | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/shape/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणधर्म को निर्दिष्ट मान पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/shape/get_base_placeholder/#) | एक बेसिक प्लेसहोल्डर आकार लौटाता है (वर्तमान आकार जिस लेआउट या मास्टर स्लाइड से विरासत में मिला है)।<br/>यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/shape/get_visual_bounds/#) | आकार के दृश्य बाउंड्स को उसके रेंडर किए गए सामग्री से गणना करके प्राप्त करता है। |


### देखें
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)