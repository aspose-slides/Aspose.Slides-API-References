---
title: IShapeCollection class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/
---
## IShapeCollection कक्षा

आकारों के संग्रह का प्रतिनिधित्व करता है।

The IShapeCollection type exposes the following members:

## गुण

| गुण | वर्णन |
| :- | :- |
| [`parent_group`](/slides/python-net/hi/aspose.slides/ishapecollection/parent_group/) | शेप्स संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है।<br/>            Read-only [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।            Read-only [`IShape`](/slides/python-net/hi/aspose.slides/ishape).

## इंडेक्सर

| नाम | वर्णन |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides/ishapecollection/__getitem__/) |  |

## विधियां

| विधि | वर्णन |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारंभ करता है, और इसे<br/>            आकार संग्रह के अंत में जोड़ता है। |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारंभ करता है, और इसे<br/>            आकार संग्रह के अंत में जोड़ता है। |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारंभ करता है,<br/>            और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में सम्मिलित करता है। |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारंभ करता है,<br/>            और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में सम्मिलित करता है। |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में सम्मिलित करता है। |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में सम्मिलित करता है। |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | एक नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में सम्मिलित करता है। |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | एक पूर्वनिर्धारित छवि के साथ नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह में<br/>            निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | एक पूर्वनिर्धारित छवि के साथ नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह में<br/>            निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | एक पूर्वनिर्धारित छवि के साथ नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह में<br/>            निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है। |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | एक नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, Presentation.Audios सूची में मौजूद ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे आकार<br/>            संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios<br/>            संग्रह में जोड़ा जाता है। |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | एक नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर<br/>            सम्मिलित करता है, Presentation.Audios सूची में मौजूद ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [`to_array(self)`](/slides/python-net/hi/aspose.slides/ishapecollection/to_array/#) | सभी आकारों को शामिल करने वाला एक एरे बनाता है और लौटाता है। |
| [`to_array(self, start_index, count)`](/slides/python-net/hi/aspose.slides/ishapecollection/to_array/#int-int) | निर्दिष्ट सीमा में सभी आकारों को शामिल करने वाला एक एरे बनाता है और लौटाता है। |
| [`reorder(self, index, shape)`](/slides/python-net/hi/aspose.slides/ishapecollection/reorder/#int-ishape) | निर्दिष्ट आकार को आकार संग्रह के भीतर नई स्थिति में ले जाता है। |
| [`reorder(self, index, shapes)`](/slides/python-net/hi/aspose.slides/ishapecollection/reorder/#int-listishape) | निर्दिष्ट आकारों को आकार संग्रह के भीतर स्थानांतरित करता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है। |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ नया ऑटो शेप बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | एक नया ऑटो शेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग से प्रारंभ करता है। |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | एक नया ऑटो शेप बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है,<br/>            डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है। |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | एक नया ऑटो शेप बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है,<br/>            वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट स्टाइलिंग से प्रारंभ करता है। |
| [`add_group_shape(self)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_group_shape/#) | एक नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।<br/>            समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गए आकार को फिट करने के लिए समायोजित होगा। |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | एक नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकार में परिवर्तित करता है,<br/>            और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है। |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है,<br/>            वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है,<br/>            डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है,<br/>            वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।<br/>            नई आकार `source_shape` की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [`add_clone(self, source_shape)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_clone/#ishape) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।<br/>            क्लोन किया हुआ आकार मूल की स्थिति और आकार को बनाए रखता है। |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।<br/>            नई आकार `source_shape` की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_clone/#int-ishape) | निर्दिष्ट आकार की एक प्रति बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।<br/>            क्लोन किया हुआ आकार मूल की स्थिति और आकार को बनाए रखता है। |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | एक SmartArt आरेख बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | एक नया समरी ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | एक नया समरी ज़ूम फ्रेम बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | एक CD ट्रैक से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | एक CD ट्रैक से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह में<br/>            निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | एक बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | एक बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार<br/>            संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`index_of(self, shape)`](/slides/python-net/hi/aspose.slides/ishapecollection/index_of/#ishape) | संग्रह में निर्दिष्ट आकार की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | गणितीय सामग्री रखने के लिए नया आयताकार ऑटो शेप बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`insert_group_shape(self, index)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_group_shape/#int) | एक नया खाली समूह आकार बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है।<br/>            समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गए आकार को फिट करने के लिए समायोजित होगा। |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | निर्दिष्ट छवि को शामिल करने वाला नया चित्र फ्रेम बनाता है और इसे आकार संग्रह के<br/>            अंत में जोड़ता है। |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | निर्दिष्ट छवि को शामिल करने वाला नया चित्र फ्रेम बनाता है और इसे आकार<br/>            संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/hi/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | एक नई तालिका बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/hi/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | एक नई तालिका बनाता है और इसे आकार संग्रह में निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/ishapecollection/remove_at/#int) | निर्दिष्ट सूचकांक पर आकार को आकार संग्रह से हटाता है। |
| [`remove(self, shape)`](/slides/python-net/hi/aspose.slides/ishapecollection/remove/#ishape) | निर्दिष्ट आकार की पहली उपस्थिति को आकार संग्रह से हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides/ishapecollection/clear/#) | सभी आकारों को आकार संग्रह से हटाता है। |


### संबंधित देखें
* कक्षा [`IShape`](/slides/python-net/hi/aspose.slides/ishape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)