---
title: Table class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/table/
---
## Table क्लास

एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।

**विरासत:**[`Table`](/slides/python-net/hi/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

Table प्रकार निम्नलिखित सदस्य प्रदान करता है:

## गुणधर्म

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/table/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/table/placeholder/) | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/table/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/table/raw_frame/) | कच्चे आकार फ्रेम की गुणधर्मों को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/table/frame/) | आकार फ्रेम की गुणधर्मों को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/table/line_format/) | एक आकार के लिए रेखा फ़ॉर्मेट गुणों को समाहित करने वाले LineFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: उन कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें रेखा गुण नहीं होते।<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/table/three_d_format/) | एक आकार के लिए 3D प्रभाव गुणों को समाहित करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: उन कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें 3D गुण नहीं होते।<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/table/effect_format/) | एक आकार पर लागू पिक्सेल प्रभावों को समाहित करने वाले EffectFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: उन कुछ प्रकार के आकारों के लिए None लौटाया जा सकता है जिनमें प्रभाव गुण नहीं होते।<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/table/fill_format/) | Table के लिए भराव फ़ॉर्मेटिंग को समाहित करने वाले TableFormat.FillFormat ऑब्जेक्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/table/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/table/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/table/hyperlink_manager/) | हाइपरलिंक प्रबंधक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/table/hidden/) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/table/z_order_position/) | z-क्रम में आकार की स्थिति लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे का आकार लौटाता है,<br/>            और Shapes[Shapes.Count - 1] z-क्रम के सामने का आकार लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/table/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/table/rotation/) | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान<br/>            विपरीत दिशा में घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/table/x/) | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/table/y/) | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/table/width/) | आकार की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/table/height/) | आकार की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/table/black_white_mode/) | गुणधर्म निर्धारित करता है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/table/unique_id/) | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अनूठी कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल पढ़ने योग्य **int**।<br/>            देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/table/office_interop_shape_id/) | एक स्लाइड-स्कोप्ड अनूठा पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और<br/>            PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल पढ़ने योग्य **int**।<br/>            देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/table/alternative_text/) | एक आकार से जुड़े वैकल्पिक टेक्स्ट को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/table/alternative_text_title/) | एक आकार से जुड़े वैकल्पिक टेक्स्ट के शीर्षक को लौटाता या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/table/name/) | एक आकार का नाम लौटाता या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/table/is_decorative/) | 'सजावटी के रूप में चिन्हित करें' विकल्प को प्राप्त या सेट करता है<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/table/shape_lock/) | आकार की लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/table/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/table/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/table/slide/) | एक आकार की पैरेंट स्लाइड को लौटाता है।<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/table/presentation/) | एक स्लाइड की पैरेंट प्रेजेंटेशन को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides/table/graphical_object_lock/) | आकार की लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock)। |
| [`rows`](/slides/python-net/hi/aspose.slides/table/rows/) | पंक्तियों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IRowCollection`](/slides/python-net/hi/aspose.slides/irowcollection)। |
| [`columns`](/slides/python-net/hi/aspose.slides/table/columns/) | स्तंभों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IColumnCollection`](/slides/python-net/hi/aspose.slides/icolumncollection)। |
| [`table_format`](/slides/python-net/hi/aspose.slides/table/table_format/) | इस तालिका के फ़ॉर्मेटिंग गुणों को समाहित करने वाले TableFormat ऑब्जेक्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`ITableFormat`](/slides/python-net/hi/aspose.slides/itableformat)। |
| [`style_preset`](/slides/python-net/hi/aspose.slides/table/style_preset/) | निर्मित तालिका शैली को प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`TableStylePreset`](/slides/python-net/hi/aspose.slides/tablestylepreset)। |
| [`right_to_left`](/slides/python-net/hi/aspose.slides/table/right_to_left/) | निर्धारित करता है कि तालिका में दाएँ से बाएँ पढ़ने क्रम है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`first_row`](/slides/python-net/hi/aspose.slides/table/first_row/) | निर्धारित करता है कि तालिका की पहली पंक्ति विशेष फ़ॉर्मेटिंग के साथ बनाई जानी चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`first_col`](/slides/python-net/hi/aspose.slides/table/first_col/) | निर्धारित करता है कि तालिका की पहली स्तंभ विशेष फ़ॉर्मेटिंग के साथ बनाई जानी चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`last_row`](/slides/python-net/hi/aspose.slides/table/last_row/) | निर्धारित करता है कि तालिका की अंतिम पंक्ति विशेष फ़ॉर्मेटिंग के साथ बनाई जानी चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`last_col`](/slides/python-net/hi/aspose.slides/table/last_col/) | निर्धारित करता है कि तालिका की अंतिम स्तंभ विशेष फ़ॉर्मेटिंग के साथ बनाई जानी चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`horizontal_banding`](/slides/python-net/hi/aspose.slides/table/horizontal_banding/) | निर्धारित करता है कि सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ बनाया जाना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`vertical_banding`](/slides/python-net/hi/aspose.slides/table/vertical_banding/) | निर्धारित करता है कि सम स्तंभों को अलग फ़ॉर्मेटिंग के साथ बनाया जाना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/table/get_image/#) | आकार थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/table/write_as_svg/#iorawiobase) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`set_text_format(self, source)`](/slides/python-net/hi/aspose.slides/table/set_text_format/#iportionformat) | परिभाषित पोर्शन फ़ॉर्मेट गुणों को सभी तालिका कोशिकाओं के पोर्शन पर सेट करता है। |
| [`set_text_format(self, source)`](/slides/python-net/hi/aspose.slides/table/set_text_format/#iparagraphformat) | परिभाषित पैराग्राफ़ फ़ॉर्मेट गुणों को सभी तालिका कोशिकाओं के पैराग्राफ़ पर सेट करता है। |
| [`set_text_format(self, source)`](/slides/python-net/hi/aspose.slides/table/set_text_format/#itextframeformat) | परिभाषित टेक्स्ट फ़्रेम फ़ॉर्मेट गुणों को सभी तालिका कोशिकाओं के टेक्स्ट फ़्रेम पर सेट करता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/table/remove_placeholder/#) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/table/add_placeholder/#iplaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर के गुण सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/table/get_base_placeholder/#) | बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)।<br/>            यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/table/get_visual_bounds/#) | रेंडर किए गए सामग्री से गणना किए गए आकार की दृश्य बाउंड्स प्राप्त करता है। |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/hi/aspose.slides/table/merge_cells/#icell-icell-bool) | सन्निकट कोशिकाओं को मिलाता है। |

### संबंधित देखें
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`Table`](/slides/python-net/hi/aspose.slides/table)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)