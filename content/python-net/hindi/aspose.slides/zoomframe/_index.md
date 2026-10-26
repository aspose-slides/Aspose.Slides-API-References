---
title: ZoomFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/zoomframe/
---
## ZoomFrame क्लास

एक स्लाइड में Slide Zoom ऑब्जेक्ट को दर्शाता है।

**Inheritance:**[`ZoomFrame`](/slides/python-net/hi/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/hi/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

ZoomFrame प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/zoomframe/is_text_holder/) | निर्धारित करता है कि shape TextHolder_PPT है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides/zoomframe/placeholder/) | shape के लिए placeholder लौटाता है। यदि shape के पास कोई placeholder नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides/zoomframe/custom_data/) | shape का कस्टम डेटा लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/zoomframe/raw_frame/) | raw shape फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides/zoomframe/frame/) | shape फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides/zoomframe/line_format/) | shape के लिए लाइन फ़ॉर्मेट ऑब्जेक्ट लौटाता है जिसमें लाइन फ़ॉर्मेटिंग प्रॉपर्टी होती है।<br/>            नोट: कुछ प्रकार के shape जिनमें लाइन प्रॉपर्टी नहीं होती, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/zoomframe/three_d_format/) | shape के लिए ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें 3d इफ़ेक्ट प्रॉपर्टी होती है।<br/>            नोट: कुछ प्रकार के shape जिनमें 3d प्रॉपर्टी नहीं होती, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides/zoomframe/effect_format/) | shape के लिए EffectFormat ऑब्जेक्ट लौटाता है जिसमें पिक्सेल इफ़ेक्ट लागू होते हैं।<br/>            नोट: कुछ प्रकार के shape जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides/zoomframe/fill_format/) | shape के लिए FillFormat ऑब्जेक्ट लौटाता है जिसमें fill फ़ॉर्मेटिंग प्रॉपर्टी होती है।<br/>            नोट: कुछ प्रकार के shape जिनमें fill प्रॉपर्टी नहीं होती, उनके लिए None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/zoomframe/hyperlink_click/) | माउस क्लिक के लिए परिभाषित hyperlink को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/zoomframe/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित hyperlink को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/zoomframe/hyperlink_manager/) | hyperlink manager को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides/zoomframe/hidden/) | निर्धारित करता है कि shape छिपी हुई है या नहीं।<br/>            पढ़ने-और-लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/zoomframe/z_order_position/) | z-order में shape की स्थिति को लौटाता है।<br/>            Shapes[0] z-order के पीछे का shape लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-order के सामने का shape लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/zoomframe/connection_site_count/) | shape पर कनेक्शन साइटों की संख्या को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides/zoomframe/rotation/) | निर्दिष्ट shape को z-axis के आसपास घुमाए जाने वाले डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी के उल्टे दिशा में घुमाव दर्शाता है।<br/>            पढ़ने-और-लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides/zoomframe/x/) | shape के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में माप कर लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides/zoomframe/y/) | shape के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में माप कर लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides/zoomframe/width/) | shape की चौड़ाई को पॉइंट्स में माप कर लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides/zoomframe/height/) | shape की ऊँचाई को पॉइंट्स में माप कर लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/zoomframe/black_white_mode/) | प्रॉपर्टी निर्धारित करती है कि shape काली-और-सफेद डिस्प्ले मोड में कैसे रेंडर होगी।<br/>            पढ़ने-और-लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides/zoomframe/unique_id/) | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे add-ins या अन्य कोड द्वारा उपयोग किया जा सकता है।<br/>            क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा फिर से असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/zoomframe/office_interop_shape_id/) | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है।<br/>            केवल-पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/zoomframe/alternative_text/) | shape से संबंधित वैकल्पिक टेक्स्ट को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/zoomframe/alternative_text_title/) | shape से संबंधित वैकल्पिक टेक्स्ट के शीर्षक को लौटाता है या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides/zoomframe/name/) | shape के नाम को लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का प्रयोग करें।<br/>            पढ़ने-और-लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/zoomframe/is_decorative/) | 'Mark as decorative' विकल्प को प्राप्त या सेट करता है<br/>            पढ़ने-और-लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/zoomframe/shape_lock/) | shape के locks को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/zoomframe/is_grouped/) | निर्धारित करता है कि shape समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides/zoomframe/parent_group/) | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides/zoomframe/slide/) | shape की पैरेंट स्लाइड को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides/zoomframe/presentation/) | स्लाइड की पैरेंट प्रस्तुति को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides/zoomframe/graphical_object_lock/) | shape के locks को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/hi/aspose.slides/zoomframe/image_type/) | zoom ऑब्जेक्ट की इमेज प्रकार को प्राप्त या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`ZoomImageType`](/slides/python-net/hi/aspose.slides/zoomimagetype).<br/>            डिफ़ॉल्ट मान: Preview |
| [`return_to_parent`](/slides/python-net/hi/aspose.slides/zoomframe/return_to_parent/) | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **bool**.<br/>            डिफ़ॉल्ट मान: false |
| [`show_background`](/slides/python-net/hi/aspose.slides/zoomframe/show_background/) | निर्धारित करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं।<br/>            पढ़ने-और-लिखने योग्य **bool**.<br/>            डिफ़ॉल्ट मान: true |
| [`zoom_image`](/slides/python-net/hi/aspose.slides/zoomframe/zoom_image/) | zoom ऑब्जेक्ट के लिए इमेज को प्राप्त या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/hi/aspose.slides/zoomframe/transition_duration/) | Zoom और स्लाइड के बीच संक्रमण की अवधि को प्राप्त या सेट करता है।<br/>            पढ़ने-और-लिखने योग्य **float**.<br/>            डिफ़ॉल्ट मान: 1.0f |
| [`target_slide`](/slides/python-net/hi/aspose.slides/zoomframe/target_slide/) | स्लाइड ऑब्जेक्ट को प्राप्त या सेट करता है जिससे Slide Zoom ऑब्जेक्ट लिंक करता है।<br/>            पढ़ने-और-लिखने योग्य [`ISlide`](/slides/python-net/hi/aspose.slides/islide). |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/zoomframe/get_image/#) | shape थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार का उपयोग होता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | shape थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/zoomframe/remove_placeholder/#) | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/zoomframe/get_base_placeholder/#) | बेसिक placeholder shape लौटाता है (layout और/या master स्लाइड से shape जिससे वर्तमान shape विरासत में मिला है)।<br/>            यदि वर्तमान shape विरासत में नहीं मिली है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/zoomframe/get_visual_bounds/#) | rendered सामग्री से गणना किए गए shape के दृश्य बाउंड्स प्राप्त करता है। |

### देखें
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`ZoomFrame`](/slides/python-net/hi/aspose.slides/zoomframe)
* क्लास [`ZoomObject`](/slides/python-net/hi/aspose.slides/zoomobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)