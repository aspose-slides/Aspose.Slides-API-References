---
title: InkActions class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/inkactions/
---
## InkActions वर्ग

इंक एक्शन्स की जड़ को दर्शाता है।

**विरासत:**[`InkActions`](/slides/python-net/hi/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

InkActions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides.ink/inkactions/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            केवल पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides.ink/inkactions/placeholder/) | shape के लिए placeholder लौटाता है। यदि shape के पास placeholder नहीं है तो None लौटाता है।<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides.ink/inkactions/custom_data/) | shape का कस्टम डेटा लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides.ink/inkactions/raw_frame/) | raw shape फ्रेम की गुणधर्म लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides.ink/inkactions/frame/) | shape फ्रेम की गुणधर्म लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides.ink/inkactions/line_format/) | shape के लिए लाइन फॉर्मेट ऑब्जेक्ट लौटाता है जिसमें लाइन फ़ॉर्मेटिंग गुण होते हैं।<br/>            नोट: जिन shape प्रकारों में लाइन गुण नहीं होते उनके लिए None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides.ink/inkactions/three_d_format/) | shape के लिए ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें 3D प्रभाव गुण होते हैं।<br/>            नोट: जिन shape प्रकारों में 3D गुण नहीं होते उनके लिए None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides.ink/inkactions/effect_format/) | shape पर लागू पिक्सेल प्रभावों को समेटे हुए EffectFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: जिन shape प्रकारों में प्रभाव गुण नहीं होते उनके लिए None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides.ink/inkactions/fill_format/) | shape के लिए FillFormat ऑब्जेक्ट लौटाता है जिसमें fill फ़ॉर्मेटिंग गुण होते हैं।<br/>            नोट: जिन shape प्रकारों में fill गुण नहीं होते उनके लिए None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides.ink/inkactions/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides.ink/inkactions/hyperlink_manager/) | हाइपरलिंक प्रबंधक लौटाता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides.ink/inkactions/hidden/) | Determines whether the shape is hidden.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides.ink/inkactions/z_order_position/) | z-ऑर्डर में shape की स्थिति लौटाता है।<br/>            Shapes[0] z-ऑर्डर के पीछे वाले shape को लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-ऑर्डर के सामने वाले shape को लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides.ink/inkactions/connection_site_count/) | shape पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides.ink/inkactions/rotation/) | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान उल्टी दिशा में घूर्णन दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides.ink/inkactions/x/) | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में मापकर प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.ink/inkactions/y/) | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में मापकर प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.ink/inkactions/width/) | shape की चौड़ाई को पॉइंट में मापकर प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.ink/inkactions/height/) | shape की ऊँचाई को पॉइंट में मापकर प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides.ink/inkactions/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides.ink/inkactions/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            क्योंकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामिंग के माध्यम से पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides.ink/inkactions/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            केवल पढ़ने योग्य **int**.<br/>            देखें भी [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides.ink/inkactions/alternative_text/) | shape से संबद्ध वैकल्पिक पाठ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides.ink/inkactions/alternative_text_title/) | shape से संबद्ध वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides.ink/inkactions/name/) | shape का नाम लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides.ink/inkactions/is_decorative/) | सजावटी के रूप में चिह्नित करने का विकल्प प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides.ink/inkactions/shape_lock/) | shape के लॉक लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides.ink/inkactions/is_grouped/) | Determines whether the shape is grouped.<br/>            केवल पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides.ink/inkactions/parent_group/) | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides.ink/inkactions/slide/) | shape की पैरेंट स्लाइड लौटाता है।<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides.ink/inkactions/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides.ink/inkactions/graphical_object_lock/) | shape के लॉक लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides.ink/inkactions/get_image/#) | Returns shape thumbnail.<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail.<br/>            shape थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file.<br/>            Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file.<br/>            Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides.ink/inkactions/remove_placeholder/#) | Defines that this shape isn't a placeholder.<br/>            परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one.<br/>            यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides.ink/inkactions/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited.<br/>            एक बुनियादी प्लेसहोल्डर shape लौटाता है (लेआउट और/या मास्टर स्लाइड से shape जिससे वर्तमान shape विरासत में मिला है)।<br/>            यदि वर्तमान shape विरासत में नहीं मिला है तो None लौटाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides.ink/inkactions/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content.<br/>            shape की दृश्य बाउंड्स प्राप्त करता है जो उसके रेंडर किए गए सामग्री से गणना की गई है। |

### देखें
* वर्ग [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* वर्ग [`InkActions`](/slides/python-net/hi/aspose.slides.ink/inkactions)
* वर्ग [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)