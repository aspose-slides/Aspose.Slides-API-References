---
title: IAudioFrame class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iaudioframe/
---
## IAudioFrame वर्ग

एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।

IAudioFrame प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/hi/aspose.slides/iaudioframe/audio_cd_start_track/) | प्रारंभ ट्रैक अनुक्रमांक को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/hi/aspose.slides/iaudioframe/audio_cd_start_track_time/) | प्रारंभ ट्रैक समय को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`audio_cd_end_track`](/slides/python-net/hi/aspose.slides/iaudioframe/audio_cd_end_track/) | अंतिम ट्रैक अनुक्रमांक को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/hi/aspose.slides/iaudioframe/audio_cd_end_track_time/) | अंतिम ट्रैक समय को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`volume`](/slides/python-net/hi/aspose.slides/iaudioframe/volume/) | ऑडियो वॉल्यूम को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`AudioVolumeMode`](/slides/python-net/hi/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/hi/aspose.slides/iaudioframe/play_mode/) | ऑडियो प्ले मोड को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`AudioPlayModePreset`](/slides/python-net/hi/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/hi/aspose.slides/iaudioframe/hide_at_showing/) | निर्धारित करता है कि AudioFrame छिपा है या नहीं।<br/>            पढ़ें/लिखें **bool**. |
| [`play_loop_mode`](/slides/python-net/hi/aspose.slides/iaudioframe/play_loop_mode/) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं।<br/>            पढ़ें/लिखें **bool**. |
| [`play_across_slides`](/slides/python-net/hi/aspose.slides/iaudioframe/play_across_slides/) | निर्धारित करता है कि ऑडियो स्लाइडों में एक साथ चल रहा है या नहीं।<br/>             पढ़ें/लिखें **bool**. |
| [`rewind_audio`](/slides/python-net/hi/aspose.slides/iaudioframe/rewind_audio/) | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रीवाइंड किया जाता है या नहीं।<br/>             पढ़ें/लिखें **bool**. |
| [`embedded`](/slides/python-net/hi/aspose.slides/iaudioframe/embedded/) | निर्धारित करता है कि साउंड प्रस्तुति में एम्बेडेड है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`link_path_long`](/slides/python-net/hi/aspose.slides/iaudioframe/link_path_long/) | AudioFrame से लिंक किए गए ऑडियो फ़ाइल का नाम लौटाता या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`embedded_audio`](/slides/python-net/hi/aspose.slides/iaudioframe/embedded_audio/) | एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/hi/aspose.slides/iaudioframe/fade_in_duration/) | मीडिया के प्रारंभिक फेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>             पढ़ें/लिखें **float**. |
| [`fade_out_duration`](/slides/python-net/hi/aspose.slides/iaudioframe/fade_out_duration/) | मीडिया के समाप्ति फेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>             पढ़ें/लिखें **float**. |
| [`volume_value`](/slides/python-net/hi/aspose.slides/iaudioframe/volume_value/) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता या सेट करता है।<br/>             पढ़ें/लिखें **float**. |
| [`trim_from_start`](/slides/python-net/hi/aspose.slides/iaudioframe/trim_from_start/) | प्लेबैक के दौरान मीडिया की शुरुआत से हटाई जाने वाली समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`trim_from_end`](/slides/python-net/hi/aspose.slides/iaudioframe/trim_from_end/) | प्लेबैक के दौरान मीडिया के अंत से हटाई जाने वाली समय अवधि को मिलीसेकंड में निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **float**. |
| [`caption_tracks`](/slides/python-net/hi/aspose.slides/iaudioframe/caption_tracks/) | ऑडियो फ्रेम से जुड़े क्लोज़्ड कैप्शन संग्रह को प्राप्त करता है।<br/>            यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक को सम्मिलित एक [`ICaptionsCollection`](/slides/python-net/hi/aspose.slides/icaptionscollection) लौटाती है। |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/hi/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/hi/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/hi/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/hi/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/hi/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/hi/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/hi/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hi/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/hi/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/hi/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/hi/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hi/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/hi/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/hi/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hi/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/hi/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/hi/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/hi/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/hi/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/hi/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/hi/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hi/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## विधियाँ

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)