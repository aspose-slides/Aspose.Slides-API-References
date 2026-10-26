---
title: SummaryZoomFrame class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame वर्ग

एक slide में Summary Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

**विरासत:**[`SummaryZoomFrame`](/slides/python-net/hi/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

SummaryZoomFrame टाइप निम्न सदस्य दिखाता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/summaryzoomframe/is_text_holder/) | निर्धारित करता है कि shape TextHolder_PPT है या नहीं।<br/>            केवल पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/summaryzoomframe/placeholder/) | shape के लिए placeholder लौटाता है। यदि shape में placeholder नहीं है तो None लौटाता है।<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/summaryzoomframe/custom_data/) | shape के कस्टम डेटा को लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/summaryzoomframe/raw_frame/) | raw shape frame की प्रॉपर्टीज़ को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/summaryzoomframe/frame/) | shape frame की प्रॉपर्टीज़ को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/summaryzoomframe/line_format/) | shape के लिए line formatting प्रॉपर्टीज़ रखने वाला LineFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ प्रकार के shapes जिनमें लाइन प्रॉपर्टीज़ नहीं होते हैं, उनमें None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/summaryzoomframe/three_d_format/) | shape के लिए 3d इफ़ेक्ट प्रॉपर्टीज़ रखने वाला ThreeDFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ प्रकार के shapes जिनमें 3d प्रॉपर्टीज़ नहीं होते हैं, उनमें None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/summaryzoomframe/effect_format/) | shape पर लागू पिक्सेल इफ़ेक्ट्स रखने वाला EffectFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ प्रकार के shapes जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होते हैं, उनमें None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/summaryzoomframe/fill_format/) | shape के लिए fill formatting प्रॉपर्टीज़ रखने वाला FillFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ प्रकार के shapes जिनमें fill प्रॉपर्टीज़ नहीं होते हैं, उनमें None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/summaryzoomframe/hyperlink_click/) | mouse click के लिए परिभाषित hyperlink को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | mouse over के लिए परिभाषित hyperlink को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/summaryzoomframe/hyperlink_manager/) | hyperlink manager को लौटाता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/summaryzoomframe/hidden/) | निर्धारित करता है कि shape छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/summaryzoomframe/z_order_position/) | z-order में shape की स्थिति लौटाता है।<br/>            Shapes[0] z-order के पीछे वाले shape को लौटाता है,<br/>            और Shapes[Shapes.Count - 1] आगे वाले shape को लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/summaryzoomframe/connection_site_count/) | shape पर कनेक्शन साइट्स की संख्या लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/summaryzoomframe/rotation/) | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान clockwise घुमाव दर्शाता है; नकारात्मक मान counterclockwise घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/summaryzoomframe/x/) | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में माप कर लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/summaryzoomframe/y/) | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में माप कर लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/summaryzoomframe/width/) | shape की चौड़ाई को पॉइंट्स में माप कर लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/summaryzoomframe/height/) | shape की ऊँचाई को पॉइंट्स में माप कर लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/summaryzoomframe/black_white_mode/) | प्रॉपर्टी यह निर्धारित करती है कि shape काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/summaryzoomframe/unique_id/) | add-ins या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुन: असाइन किया जा सकता है, इसे लगातार अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल पढ़ने योग्य **int**.<br/>            साथ ही देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/summaryzoomframe/office_interop_shape_id/) | shape के जीवनकाल के दौरान स्थिर रहने वाला slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल पढ़ने योग्य **int**.<br/>            साथ ही देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/summaryzoomframe/alternative_text/) | shape से जुड़ा वैकल्पिक टेक्स्ट लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/summaryzoomframe/alternative_text_title/) | shape से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/summaryzoomframe/name/) | shape का नाम लौटाता या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/summaryzoomframe/is_decorative/) | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/summaryzoomframe/shape_lock/) | shape के locks को लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/summaryzoomframe/is_grouped/) | निर्धारित करता है कि shape समूहित है या नहीं।<br/>            केवल पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/summaryzoomframe/parent_group/) | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/summaryzoomframe/slide/) | shape की पैरेंट slide को लौटाता है।<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/summaryzoomframe/presentation/) | slide की पैरेंट प्रस्तुति को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides/summaryzoomframe/graphical_object_lock/) | shape के locks को लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/hi/aspose.slides/summaryzoomframe/layout/) | फ़्रेम में Summary Zoom सेक्शन के लेआउट को प्राप्त करता है।<br/>            डिफ़ॉल्ट मान GridLayout है। |
| [`summary_zoom_collection`](/slides/python-net/hi/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Summary Zoom Frame ऑब्जेक्ट के लिए [`ISummaryZoomSectionCollection`](/slides/python-net/hi/aspose.slides/isummaryzoomsectioncollection) प्राप्त करता है। |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/get_image/#) | shape थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | shape थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/remove_placeholder/#) | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | यदि कोई नहीं है तो नया placeholder जोड़ता है और placeholder प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/get_base_placeholder/#) | एक बेसिक placeholder shape लौटाता है (layout और/या master slide से shape जिसे वर्तमान shape विरासत में प्राप्त करता है)।<br/>            यदि वर्तमान shape विरासत में नहीं है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/summaryzoomframe/get_visual_bounds/#) | rendered सामग्री से गणना किए गए shape के visual bounds को प्राप्त करता है। |

### संबंधित देखें
* वर्ग [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* वर्ग [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* वर्ग [`SummaryZoomFrame`](/slides/python-net/hi/aspose.slides/summaryzoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)