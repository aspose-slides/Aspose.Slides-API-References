---
title: AudioFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/audioframe/
---
## AudioFrame क्लास

स्लाइड पर एक ऑडियो क्लिप का प्रतिनिधित्व करता है।

**विरासत:**[`AudioFrame`](/slides/python-net/hi/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

AudioFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/audioframe/is_text_holder/) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/audioframe/placeholder/) | एक आकार के लिए स्थानधारक लौटाता है। यदि आकार के पास स्थानधारक नहीं है तो None लौटाता है।<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/audioframe/custom_data/) | आकार के कस्टम डेटा को लौटाता है।<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/audioframe/raw_frame/) | कच्चे आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/audioframe/frame/) | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/audioframe/line_format/) | आकार के लिए रेखा स्वरूपण प्रॉपर्टीज़ को समाहित करने वाले LineFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: उन कुछ प्रकार के आकारों के लिए जो रेखा प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/audioframe/three_d_format/) | आकार के लिए 3डी प्रभाव प्रॉपर्टीज़ को समाहित करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: उन कुछ प्रकार के आकारों के लिए जो 3डी प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/audioframe/effect_format/) | आकार पर लागू पिक्सेल इफ़ेक्ट्स को समाहित करने वाले EffectFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: उन कुछ प्रकार के आकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/audioframe/fill_format/) | आकार के लिए भराई स्वरूपण प्रॉपर्टीज़ को समाहित करने वाले FillFormat ऑब्जेक्ट को लौटाता है।<br/>            ध्यान दें: उन कुछ प्रकार के आकारों के लिए जो भराई प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/audioframe/hyperlink_click/) | माउस क्लिक के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/audioframe/hyperlink_mouse_over/) | माउस ओवर के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/audioframe/hyperlink_manager/) | हाइपरलिंक प्रबंधक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/audioframe/hidden/) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/audioframe/z_order_position/) | आकार की z-क्रम में स्थिति को लौटाता है।<br/>            Shapes[0] z-क्रम के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/audioframe/connection_site_count/) | आकार पर कनेक्शन साइटों की संख्या लौटाता है।<br/>            केवल पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/audioframe/rotation/) | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/audioframe/x/) | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/audioframe/y/) | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/audioframe/width/) | आकार की चौड़ाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/audioframe/height/) | आकार की ऊँचाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/audioframe/black_white_mode/) | गुण यह निर्दिष्ट करता है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे प्रदर्शित होगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/audioframe/unique_id/) | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल पढ़ने योग्य **int**।<br/>            और भी देखें [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/audioframe/office_interop_shape_id/) | स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार का विश्वसनीय रूप से संदर्भित करने देता है।<br/>            केवल पढ़ने योग्य **int**।<br/>            और भी देखें [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/audioframe/alternative_text/) | आकार से जुड़ा वैकल्पिक टेकस्ट को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/audioframe/alternative_text_title/) | आकार से जुड़े वैकल्पिक टेकस्ट के शीर्षक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/audioframe/name/) | आकार के नाम को लौटाता है या सेट करता है। None नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/audioframe/is_decorative/) | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/audioframe/shape_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/audioframe/is_grouped/) | निर्धारित करता है कि आकार समूहित है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/audioframe/parent_group/) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/audioframe/slide/) | आकार की पैरेंट स्लाइड को लौटाता है।<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/audioframe/presentation/) | स्लाइड की पैरेंट प्रेजेंटेशन को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/audioframe/shape_style/) | आकार की स्टाइल ऑब्जेक्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/audioframe/shape_type/) | PictureFrame के लिए AutoShape प्रकार को लौटाता है या सेट करता है। सभी अनुमत वस्तुएँ सेट [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में हैं, सिवाय विभिन्न प्रकार की लाइनों के:<br/><br/>    ShapeType.Line,<br/><br/>    ShapeType.StraightConnector1,<br/><br/>    ShapeType.BentConnector2,<br/><br/>    ShapeType.BentConnector3,<br/><br/>    ShapeType.BentConnector4,<br/><br/>    ShapeType.BentConnector5,<br/><br/>    ShapeType.CurvedConnector2,<br/><br/>    ShapeType.CurvedConnector3,<br/><br/>    ShapeType.CurvedConnector4,<br/><br/>    ShapeType.CurvedConnector5.<br/><br/>            पढ़ने/लिखने योग्य [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/audioframe/adjustments/) | आकार के समायोजन मानों का संग्रह लौटाता है।<br/>            केवल पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`picture_frame_lock`](/slides/python-net/hi/aspose.slides/audioframe/picture_frame_lock/) | आकार के लॉक को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`picture_format`](/slides/python-net/hi/aspose.slides/audioframe/picture_format/) | Picture frame के लिए PictureFillFormat ऑब्जेक्ट को लौटाता है।<br/>            केवल पढ़ने योग्य [`IPictureFillFormat`](/slides/python-net/hi/aspose.slides/ipicturefillformat)। |
| [`relative_scale_height`](/slides/python-net/hi/aspose.slides/audioframe/relative_scale_height/) | Picture frame की ऊँचाई के स्केल (मूल चित्र आकार के सापेक्ष) को लौटाता है या सेट करता है। मान 1.0 100% के बराबर है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`relative_scale_width`](/slides/python-net/hi/aspose.slides/audioframe/relative_scale_width/) | Picture frame की चौड़ाई के स्केल (मूल चित्र आकार के सापेक्ष) को लौटाता है या सेट करता है। मान 1.0 100% के बराबर है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`is_cameo`](/slides/python-net/hi/aspose.slides/audioframe/is_cameo/) | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`audio_cd_start_track`](/slides/python-net/hi/aspose.slides/audioframe/audio_cd_start_track/) | प्रारंभ ट्रैक इंडेक्स को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`audio_cd_start_track_time`](/slides/python-net/hi/aspose.slides/audioframe/audio_cd_start_track_time/) | प्रारंभ ट्रैक समय को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`audio_cd_end_track`](/slides/python-net/hi/aspose.slides/audioframe/audio_cd_end_track/) | अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`audio_cd_end_track_time`](/slides/python-net/hi/aspose.slides/audioframe/audio_cd_end_track_time/) | अंतिम ट्रैक समय को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **int**। |
| [`volume`](/slides/python-net/hi/aspose.slides/audioframe/volume/) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`AudioVolumeMode`](/slides/python-net/hi/aspose.slides/audiovolumemode)। |
| [`play_mode`](/slides/python-net/hi/aspose.slides/audioframe/play_mode/) | ऑडियो प्ले मोड को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`AudioPlayModePreset`](/slides/python-net/hi/aspose.slides/audioplaymodepreset)। |
| [`hide_at_showing`](/slides/python-net/hi/aspose.slides/audioframe/hide_at_showing/) | निर्धारित करता है कि AudioFrame छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`play_loop_mode`](/slides/python-net/hi/aspose.slides/audioframe/play_loop_mode/) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`play_across_slides`](/slides/python-net/hi/aspose.slides/audioframe/play_across_slides/) | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`rewind_audio`](/slides/python-net/hi/aspose.slides/audioframe/rewind_audio/) | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड हो जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`embedded`](/slides/python-net/hi/aspose.slides/audioframe/embedded/) | निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेडेड है या नहीं।<br/>            केवल पढ़ने योग्य **bool**। |
| [`link_path_long`](/slides/python-net/hi/aspose.slides/audioframe/link_path_long/) | AudioFrame से लिंक की गई ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`embedded_audio`](/slides/python-net/hi/aspose.slides/audioframe/embedded_audio/) | एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)। |
| [`fade_in_duration`](/slides/python-net/hi/aspose.slides/audioframe/fade_in_duration/) | मीडिया के प्रारम्भिक फ़ेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`fade_out_duration`](/slides/python-net/hi/aspose.slides/audioframe/fade_out_duration/) | मीडिया के समाप्ति फ़ेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`volume_value`](/slides/python-net/hi/aspose.slides/audioframe/volume_value/) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`trim_from_start`](/slides/python-net/hi/aspose.slides/audioframe/trim_from_start/) | प्ले-बैक के दौरान मीडिया की शुरुआत से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`trim_from_end`](/slides/python-net/hi/aspose.slides/audioframe/trim_from_end/) | प्ले-बैक के दौरान मीडिया के अंत से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`caption_tracks`](/slides/python-net/hi/aspose.slides/audioframe/caption_tracks/) | ऑडियो फ्रेम से जुड़े क्लोज़्ड कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को समाहित करने वाला [`ICaptionsCollection`](/slides/python-net/hi/aspose.slides/icaptionscollection) लौटाता है। |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/audioframe/get_image/#) | आकार थंबनेल को लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | आकार थंबनेल को लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/audioframe/write_as_svg/#iorawiobase) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/audioframe/remove_placeholder/#) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/audioframe/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले में सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/audioframe/get_base_placeholder/#) | बेसिक प्लेसहोल्डर आकार (लेआउट या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है) को लौटाता है।<br/>            यदि वर्तमान आकार विरासत में नहीं मिला है तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/audioframe/get_visual_bounds/#) | आकार के रेंडर किए गए कंटेंट से गणना किए गए दृश्य बाउंड्स को प्राप्त करता है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/audioframe/get_geometry_paths/#) | ज्यामितीय आकार के पथ की कॉपी को लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकार ज्योमेट्री को अपडेट करता है। निर्देशांक बाएँ<br/>            शीर्ष कोने के सापेक्ष होने चाहिए।<br/>            आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) एरे से आकार ज्योमेट्री को अपडेट करता है। निर्देशांक बाएँ<br/>            शीर्ष कोने के सापेक्ष होने चाहिए।<br/>            आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/audioframe/create_shape_elements/#) | आकार के तत्वों की एरे बनाता है और लौटाता है। |

### देखें
* क्लास [`AudioFrame`](/slides/python-net/hi/aspose.slides/audioframe)
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)