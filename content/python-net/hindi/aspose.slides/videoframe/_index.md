---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videoframe/
---
## VideoFrame क्लास

एक स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।

**Inheritance:**[`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

VideoFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## प्रॉपर्टीज

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/videoframe/is_text_holder/) | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/videoframe/placeholder/) | आकृति के प्लेसहोल्डर को लौटाता है। यदि आकृति का प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/videoframe/custom_data/) | आकृति के कस्टम डेटा को लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/videoframe/raw_frame/) | कच्चे आकृति फ्रेम की प्रॉपर्टीज को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/videoframe/frame/) | आकृति फ्रेम की प्रॉपर्टीज को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/videoframe/line_format/) | आकृति के लिए रेखा स्वरूपण प्रॉपर्टीज़ वाला LineFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें रेखा प्रॉपर्टीज नहीं होतीं।<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/videoframe/three_d_format/) | आकृति के 3D इफ़ेक्ट प्रॉपर्टीज़ वाला ThreeDFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज नहीं होतीं।<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/videoframe/effect_format/) | आकृति पर लागू पिक्सेल इफ़ेक्ट्स वाला EffectFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज नहीं होतीं।<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/videoframe/fill_format/) | आकृति के भराव स्वरूपण प्रॉपर्टीज़ वाला FillFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: उन कुछ प्रकार की आकृतियों के लिए None लौटाया जा सकता है जिनमें भराव प्रॉपर्टीज नहीं होतीं।<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_click/) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_mouse_over/) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_manager/) | हाइपरलिंक प्रबंधक लौटाता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/videoframe/hidden/) | निर्धारित करता है कि आकृति छिपी हुई है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/videoframe/z_order_position/) | Z-क्रम में आकृति की स्थिति लौटाता है।<br/>            Shapes[0] Z-क्रम के पीछे वाली आकृति लौटाता है,<br/>            और Shapes[Shapes.Count - 1] Z-क्रम के सामने वाली आकृति लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/videoframe/connection_site_count/) | आकृति पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/videoframe/rotation/) | निर्दिष्ट आकृति को z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है।<br/>            सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/videoframe/x/) | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/videoframe/y/) | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/videoframe/width/) | आकृति की चौड़ाई को पॉइंट में प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/videoframe/height/) | आकृति की ऊँचाई को पॉइंट में प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/videoframe/black_white_mode/) | यह प्रॉपर्टी निर्धारित करती है कि आकृति काली-रंगीन (ब्लैक-एंड-व्हाइट) डिस्प्ले मोड में कैसे प्रदर्शित होगी।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/videoframe/unique_id/) | एक आंतरिक, प्रस्तुति-स्तर का पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल पढ़ने योग्य **int**।<br/>            देखिए [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/videoframe/office_interop_shape_id/) | एक स्लाइड-स्तर का अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकृति को विश्वसनीयरूप से संदर्भित करने में सक्षम बनाता है।<br/>            केवल पढ़ने योग्य **int**।<br/>            देखिए [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/videoframe/alternative_text/) | आकृति से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/videoframe/alternative_text_title/) | आकृति से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/videoframe/name/) | आकृति का नाम लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/videoframe/is_decorative/) | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/videoframe/shape_lock/) | आकृति के लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/videoframe/is_grouped/) | निर्धारित करता है कि आकृति समूहबद्ध है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/videoframe/parent_group/) | यदि आकृति समूहबद्ध है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा None लौटाता है।<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/videoframe/slide/) | आकृति की पैरेंट स्लाइड लौटाता है।<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/videoframe/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/videoframe/shape_style/) | आकृति की शैली ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/videoframe/shape_type/) | PictureFrame के लिए AutoShape प्रकार लौटाता है या सेट करता है। सेट [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में सभी अनुमत आइटम हैं, <br/>            लेकिन सभी प्रकार की रेखाएँ नहीं:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            पढ़ने/लिखने योग्य [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/videoframe/adjustments/) | आकृति के समायोजन मानों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`picture_frame_lock`](/slides/python-net/hi/aspose.slides/videoframe/picture_frame_lock/) | आकृति के लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`picture_format`](/slides/python-net/hi/aspose.slides/videoframe/picture_format/) | PictureFrame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFillFormat`](/slides/python-net/hi/aspose.slides/ipicturefillformat)। |
| [`relative_scale_height`](/slides/python-net/hi/aspose.slides/videoframe/relative_scale_height/) | PictureFrame की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100 % के बराबर है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`relative_scale_width`](/slides/python-net/hi/aspose.slides/videoframe/relative_scale_width/) | PictureFrame की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100 % के बराबर है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`is_cameo`](/slides/python-net/hi/aspose.slides/videoframe/is_cameo/) | निर्धारित करता है कि PictureFrame कैमियो ऑब्जेक्ट है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`rewind_video`](/slides/python-net/hi/aspose.slides/videoframe/rewind_video/) | निर्धारित करता है कि वीडियो पूरा चलने के बाद स्वचालित रूप से शुरू से रिवाइंड हो जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`play_loop_mode`](/slides/python-net/hi/aspose.slides/videoframe/play_loop_mode/) | निर्धारित करता है कि वीडियो लूप में चलाया जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`hide_at_showing`](/slides/python-net/hi/aspose.slides/videoframe/hide_at_showing/) | निर्धारित करता है कि VideoFrame छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`volume`](/slides/python-net/hi/aspose.slides/videoframe/volume/) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`AudioVolumeMode`](/slides/python-net/hi/aspose.slides/audiovolumemode)। |
| [`volume_value`](/slides/python-net/hi/aspose.slides/videoframe/volume_value/) | सटीक वीडियो वॉल्यूम को प्रतिशत के रूप में लौटाता है या सेट करता है।<br/>             मान 0 से 100 तक प्रतिशत में व्यक्त किया जाता है। इस प्रॉपर्टी का उपयोग उन वॉल्यूम मानों को पढ़ने या सेट करने के लिए करें जो [`VideoFrame.volume`](/slides/python-net/hi/aspose.slides/videoframe/volume) प्रॉपर्टी द्वारा उपलब्ध पूर्वनिर्धारित स्तरों से अधिक सटीक हों।<br/>             पढ़ने/लिखने योग्य **float**। |
| [`play_mode`](/slides/python-net/hi/aspose.slides/videoframe/play_mode/) | वीडियो प्ले मोड को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`VideoPlayModePreset`](/slides/python-net/hi/aspose.slides/videoplaymodepreset)। |
| [`full_screen_mode`](/slides/python-net/hi/aspose.slides/videoframe/full_screen_mode/) | निर्धारित करता है कि वीडियो फुल-स्क्रीन मोड में दिखाया जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`link_path_long`](/slides/python-net/hi/aspose.slides/videoframe/link_path_long/) | VideoFrame से जुड़े वीडियो फ़ाइल का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`embedded_video`](/slides/python-net/hi/aspose.slides/videoframe/embedded_video/) | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo)। |
| [`trim_from_start`](/slides/python-net/hi/aspose.slides/videoframe/trim_from_start/) | ट्रिम प्रारम्भ [ms] |
| [`trim_from_end`](/slides/python-net/hi/aspose.slides/videoframe/trim_from_end/) | ट्रिम अंत [ms] |
| [`caption_tracks`](/slides/python-net/hi/aspose.slides/videoframe/caption_tracks/) | वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है।<br/>             यह प्रॉपर्टी केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक समाहित करने वाला एक [`ICaptionsCollection`](/slides/python-net/hi/aspose.slides/icaptionscollection) लौटाता है। |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_image/#) | आकृति थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकृति थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | आकृति थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/videoframe/write_as_svg/#iorawiobase) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/videoframe/remove_placeholder/#) | दर्शाता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/videoframe/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_base_placeholder/#) | मूल प्लेसहोल्डर आकृति (लेआउट या मास्टर स्लाइड से वह आकृति जिससे वर्तमान आकृति उत्तराधिकार प्राप्त करती है) लौटाता है।<br/>            यदि वर्तमान आकृति उत्तराधिकारित नहीं है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_visual_bounds/#) | रेंडर की गई सामग्री से गणना की गई आकृति की दृश्य बाउंड्स प्राप्त करता है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_geometry_paths/#) | ज्यामिति आकृति के पाथ की कॉपी लौटाता है। निर्देशांक आकृति के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकृति ज्यामिति को अद्यतन करता है। निर्देशांक बाएँ<br/>            ऊपर कोने के सापेक्ष होने चाहिए।<br/>            आकृति के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की array से आकृति ज्यामिति को अद्यतन करता है। निर्देशांक बाएँ<br/>            ऊपर कोने के सापेक्ष होने चाहिए।<br/>            आकृति के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/videoframe/create_shape_elements/#) | आकृति के तत्वों की array बनाता है और लौटाता है। |

### देखें
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)