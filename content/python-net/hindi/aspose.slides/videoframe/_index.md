---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videoframe/
---
## VideoFrame क्लास

स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।

**विरासत:**[`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

VideoFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/videoframe/is_text_holder/) | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`placeholder`](/slides/python-net/hi/aspose.slides/videoframe/placeholder/) | एक शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder)। |
| [`custom_data`](/slides/python-net/hi/aspose.slides/videoframe/custom_data/) | शेप के कस्टम डेटा को लौटाता है।<br/>            केवल-पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata)। |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/videoframe/raw_frame/) | कच्चे शेप फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`frame`](/slides/python-net/hi/aspose.slides/videoframe/frame/) | शेप फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe)। |
| [`line_format`](/slides/python-net/hi/aspose.slides/videoframe/line_format/) | ऐसे शेप के लिए रेखा फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले LineFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ ऐसे शेप प्रकारों के लिए जो रेखा प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat)। |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/videoframe/three_d_format/) | एक शेप के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ वाला ThreeDFormat ऑब्जेक्ट लौटाता है।<br/>            नोट: कुछ ऐसे शेप प्रकारों के लिए जो 3D प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat)। |
| [`effect_format`](/slides/python-net/hi/aspose.slides/videoframe/effect_format/) | शेप पर लागू पिक्सेल इफ़ेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ ऐसे शेप प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat)। |
| [`fill_format`](/slides/python-net/hi/aspose.slides/videoframe/fill_format/) | शेप के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले FillFormat ऑब्जेक्ट को लौटाता है।<br/>            नोट: कुछ ऐसे शेप प्रकारों के लिए जो फ़िल प्रॉपर्टीज़ नहीं रखते, None लौटाया जा सकता है।<br/>            केवल-पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat)। |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_click/) | माउस क्लिक के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_mouse_over/) | माउस ओवर के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink)। |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/videoframe/hyperlink_manager/) | हाइपरलिंक मैनेजर को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager)। |
| [`hidden`](/slides/python-net/hi/aspose.slides/videoframe/hidden/) | निर्धारित करता है कि शेप छिपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/videoframe/z_order_position/) | ज़-ऑर्डर में शेप की स्थिति को लौटाता है।<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            केवल-पढ़ने योग्य **int**। |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/videoframe/connection_site_count/) | शेप पर कनेक्शन साइटों की संख्या को लौटाता है।<br/>            केवल-पढ़ने योग्य **int**। |
| [`rotation`](/slides/python-net/hi/aspose.slides/videoframe/rotation/) | निर्दिष्ट शेप के z-अक्ष के autour घुमाव के डिग्री संख्या को लौटाता है या सेट करता है।<br/>            धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान<br/>            प्रतिगामी घुमाव दर्शाता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`x`](/slides/python-net/hi/aspose.slides/videoframe/x/) | शेप के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`y`](/slides/python-net/hi/aspose.slides/videoframe/y/) | शेप के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`width`](/slides/python-net/hi/aspose.slides/videoframe/width/) | शेप की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`height`](/slides/python-net/hi/aspose.slides/videoframe/height/) | शेप की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/videoframe/black_white_mode/) | यह प्रॉपर्टी निर्धारित करती है कि शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे दिखेगा।<br/>            पढ़ने/लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode)। |
| [`unique_id`](/slides/python-net/hi/aspose.slides/videoframe/unique_id/) | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है।<br/>            क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए।<br/>            केवल-पढ़ने योग्य **int**।<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id)। |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/videoframe/office_interop_shape_id/) | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शेप के जीवनकाल के दौरान स्थिर रहता है और दस्तावेज़ में कहीं से भी PowerPoint या इंटरऑप कोड को शेप को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है।<br/>            केवल-पढ़ने योग्य **int**।<br/>            See also [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id)। |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/videoframe/alternative_text/) | शेप से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/videoframe/alternative_text_title/) | शेप से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`name`](/slides/python-net/hi/aspose.slides/videoframe/name/) | शेप का नाम लौटाता है या सेट करता है।<br/>            None नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान उपयोग करें।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/videoframe/is_decorative/) | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है<br/>            Reed/write **bool**। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/videoframe/shape_lock/) | शेप के लॉक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/videoframe/is_grouped/) | निर्धारित करता है कि शेप समूहित है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`parent_group`](/slides/python-net/hi/aspose.slides/videoframe/parent_group/) | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा None लौटाता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)। |
| [`slide`](/slides/python-net/hi/aspose.slides/videoframe/slide/) | शेप की पैरेंट स्लाइड लौटाता है।<br/>            केवल-पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)। |
| [`presentation`](/slides/python-net/hi/aspose.slides/videoframe/presentation/) | स्लाइड की पैरेंट प्रस्तुति लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)। |
| [`shape_style`](/slides/python-net/hi/aspose.slides/videoframe/shape_style/) | शेप के शैली ऑब्जेक्ट को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/videoframe/shape_type/) | PictureFrame के लिए AutoShape प्रकार लौटाता है या सेट करता है।<br/>            सेट [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) के सभी आइटम अनुमत हैं, <br/>            सिवाय सभी प्रकार की लाइनों के:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            पढ़ने/लिखने योग्य [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/videoframe/adjustments/) | शेप के समायोजन मानों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`picture_frame_lock`](/slides/python-net/hi/aspose.slides/videoframe/picture_frame_lock/) | शेप के लॉक लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPictureFrameLock`](/slides/python-net/hi/aspose.slides/ipictureframelock)। |
| [`picture_format`](/slides/python-net/hi/aspose.slides/videoframe/picture_format/) | PictureFrame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है।<br/>            केवल-पढ़ने योग्य [`IPictureFillFormat`](/slides/python-net/hi/aspose.slides/ipicturefillformat)। |
| [`relative_scale_height`](/slides/python-net/hi/aspose.slides/videoframe/relative_scale_height/) | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 का मतलब 100% है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`relative_scale_width`](/slides/python-net/hi/aspose.slides/videoframe/relative_scale_width/) | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 का मतलब 100% है।<br/>            पढ़ने/लिखने योग्य **float**। |
| [`is_cameo`](/slides/python-net/hi/aspose.slides/videoframe/is_cameo/) | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`rewind_video`](/slides/python-net/hi/aspose.slides/videoframe/rewind_video/) | निर्धारित करता है कि वीडियो को फ़िल्म समाप्त होते ही स्वचालित रूप से शुरू से रीवाइंड किया जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`play_loop_mode`](/slides/python-net/hi/aspose.slides/videoframe/play_loop_mode/) | निर्धारित करता है कि वीडियो लूप किया जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`hide_at_showing`](/slides/python-net/hi/aspose.slides/videoframe/hide_at_showing/) | निर्धारित करता है कि VideoFrame छुपा हुआ है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`volume`](/slides/python-net/hi/aspose.slides/videoframe/volume/) | ऑडियो वॉल्यूम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`AudioVolumeMode`](/slides/python-net/hi/aspose.slides/audiovolumemode)। |
| [`play_mode`](/slides/python-net/hi/aspose.slides/videoframe/play_mode/) | वीडियो प्ले मोड लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`VideoPlayModePreset`](/slides/python-net/hi/aspose.slides/videoplaymodepreset)। |
| [`full_screen_mode`](/slides/python-net/hi/aspose.slides/videoframe/full_screen_mode/) | निर्धारित करता है कि वीडियो फुल स्क्रीन मोड में दिखाया जाता है या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`link_path_long`](/slides/python-net/hi/aspose.slides/videoframe/link_path_long/) | VideoFrame से जुड़ी वीडियो फ़ाइल का नाम लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`embedded_video`](/slides/python-net/hi/aspose.slides/videoframe/embedded_video/) | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है।<br/>            पढ़ने/लिखने योग्य [`IVideo`](/slides/python-net/hi/aspose.slides/ivideo)। |
| [`trim_from_start`](/slides/python-net/hi/aspose.slides/videoframe/trim_from_start/) | ट्रिम प्रारंभ [ms] |
| [`trim_from_end`](/slides/python-net/hi/aspose.slides/videoframe/trim_from_end/) | ट्रिम समाप्ति [ms] |
| [`caption_tracks`](/slides/python-net/hi/aspose.slides/videoframe/caption_tracks/) | वीडियो फ्रेम से जुड़ी क्लोज़्ड कैप्शन का संग्रह प्राप्त करता है।<br/>             यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक वाले [`ICaptionsCollection`](/slides/python-net/hi/aspose.slides/icaptionscollection) को लौटाती है। |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_image/#) | शेप थंबनेल लौटाता है।<br/>            डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | शेप थंबनेल लौटाता है। |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/videoframe/remove_placeholder/#) | निर्धारित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/videoframe/add_placeholder/#iplaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर प्रॉपर्टीज़ सेट करता है। |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_base_placeholder/#) | मौजूदा लेआउट या मास्टर स्लाइड से मूल प्लेसहोल्डर शेप लौटाता है (वर्तमान शेप की विरासत वाली शेप)।<br/>            यदि वर्तमान शेप विरासत में नहीं मिला तो None लौटाया जाता है। |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_visual_bounds/#) | शेप की दृश्य सीमाओं को उसके रेंडर की गई सामग्री से गणना करके प्राप्त करता है। |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/videoframe/get_geometry_paths/#) | ज्योमेट्री शेप के पाथ की कॉपी लौटाता है। निर्देशांक शेप के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से शेप ज्योमेट्री को अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             शेप के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की सरणी से शेप ज्योमेट्री को अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             शेप के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/videoframe/create_shape_elements/#) | शेप के तत्वों की सरणी बनाता है और लौटाता है। |

### देखें
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)