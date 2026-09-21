---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/
---
## ShapeCollection क्लास

आकृतियों के संग्रह का प्रतिनिधित्व करता है।

ShapeCollection प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/hi/aspose.slides/shapecollection/parent_group/) | आकृतियों के संग्रह के लिए पैरेंट ग्रुप शेप ऑब्जेक्ट प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
|  | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।<br/>            केवल-पढ़ने योग्य [`IShape`](/slides/python-net/hi/aspose.slides/ishape). |

## इंडेक्सर

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides/shapecollection/__getitem__/) |  |

## मेथड्स

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | एक नया चार्ट बनाता है, नमूना सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/hi/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | एक नया चार्ट बनाता है, नमूना सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | एक नया चार्ट बनाता है, नमूना सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है,<br/>            और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | एक नया चार्ट बनाता है, नमूना सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है,<br/>            और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/hi/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | एक नया ज़ूम फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/hi/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | एक नया ज़ूम फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | एक नया ज़ूम फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | एक पूर्वनिर्धारित छवि वाले नए ज़ूम फ़्रेम को बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/hi/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | एक नया सेक्शन ज़ूम फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/hi/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | एक पूर्वनिर्धारित छवि वाले नए सेक्शन ज़ूम फ़्रेम को बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | एक नया सेक्शन ज़ूम फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | एक पूर्वनिर्धारित छवि वाले नए सेक्शन ज़ूम फ़्रेम को बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/hi/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | एक नया OLE ऑब्जेक्ट फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/hi/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | एक नया OLE ऑब्जेक्ट फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | एक नया OLE ऑब्जेक्ट फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | एक नया OLE ऑब्जेक्ट फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | एक नया वीडियो फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/hi/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | एक नया वीडियो फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/hi/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | अंतर्निहित WAV फ़ाइल के साथ एक नया ऑडियो फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है। |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/hi/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | एक नया ऑडियो फ़्रेम बनाता है और इसे Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके शेप संग्रह के अंत में जोड़ता है। |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | अंतर्निहित WAV फ़ाइल के साथ एक नया ऑडियो फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है। |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | एक नया ऑडियो फ़्रेम बनाता है और इसे Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके निर्धारित सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`to_array(self)`](/slides/python-net/hi/aspose.slides/shapecollection/to_array/#) | सभी शेप्स को शामिल करने वाला एक array बनाता है और लौटाता है। |
| [`to_array(self, start_index, count)`](/slides/python-net/hi/aspose.slides/shapecollection/to_array/#int-int) | निर्दिष्ट सीमा में सभी शेप्स को शामिल करने वाला एक array बनाता है और लौटाता है। |
| [`reorder(self, index, shape)`](/slides/python-net/hi/aspose.slides/shapecollection/reorder/#int-ishape) | निर्दिष्ट शेप को शेप संग्रह के भीतर नई स्थिति में ले जाता है। |
| [`reorder(self, index, shapes)`](/slides/python-net/hi/aspose.slides/shapecollection/reorder/#int-listishape) | निर्दिष्ट शेप्स को शेप संग्रह के भीतर ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है। |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | एक नया ऑटो शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है। |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है,<br/>            डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है। |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है,<br/>            वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ प्रारंभ करता है। |
| [`add_group_shape(self)`](/slides/python-net/hi/aspose.slides/shapecollection/add_group_shape/#) | एक नया खाली ग्रुप शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।<br/>            समूह का फ्रेम स्वचालित रूप से किसी भी शेप को जोड़ने के लिए समायोजित हो जाएगा। |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | एक नया ग्रुप शेप बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत शेप्स में बदलता है,<br/>            और परिणामी ग्रुप को शेप संग्रह के अंत में जोड़ता है। |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ एक नया कनेक्टर शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | एक नया कनेक्टर शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है,<br/>            वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है,<br/>            डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है,<br/>            वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/hi/aspose.slides/shapecollection/add_clone/#ishape-float-float) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।<br/>            नया शेप `source_shape` की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [`add_clone(self, source_shape)`](/slides/python-net/hi/aspose.slides/shapecollection/add_clone/#ishape) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।<br/>            क्लोन किया गया शेप मूल की स्थिति और आकार को बरकरार रखता है। |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है.<br/>            नया शेप `source_shape` की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_clone/#int-ishape) | निर्दिष्ट शेप की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है.<br/>            क्लोन किया गया शेप मूल की स्थिति और आकार को बरकरार रखता है। |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/hi/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | एक SmartArt डायग्राम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | एक नया समरी ज़ूम फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | एक नया समरी ज़ूम फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | एक नया वीडियो फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | CD ट्रैक से जुड़ा नया ऑडियो फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD ट्रैक से जुड़ा नया ऑडियो फ़्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है। |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ़्रेम बनाता है और इसे शेप संग्रह के निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`index_of(self, shape)`](/slides/python-net/hi/aspose.slides/shapecollection/index_of/#ishape) | संग्रह में निर्दिष्ट शेप की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/hi/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | गणितीय सामग्री होस्ट करने के लिए नया आयताकार ऑटो शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_group_shape(self, index)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_group_shape/#int) | एक नया खाली ग्रुप शेप बनाता है और इसे निर्दिष्ट सूचकांक पर शेप संग्रह में सम्मिलित करता है।<br/>            समूह का फ्रेम स्वचालित रूप से किसी भी शेप को जोड़ने के लिए समायोजित हो जाएगा। |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/hi/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | निर्दिष्ट छवि को शामिल करने वाला नया पिक्चर फ़्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | निर्दिष्ट छवि को शामिल करने वाला नया पिक्चर फ़्रेम बनाता है और इसे शेप संग्रह के निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/hi/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | एक नया टेबल बनाता है और इसे शेप संग्रह के अंत में जोड़ता है। |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/hi/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | एक नया टेबल बनाता है और इसे शेप संग्रह के निर्दिष्ट सूचकांक पर सम्मिलित करता है। |
| [`remove_at(self, index)`](/slides/python-net/hi/aspose.slides/shapecollection/remove_at/#int) | निर्दिष्ट सूचकांक पर शेप को शेप संग्रह से हटाता है। |
| [`remove(self, shape)`](/slides/python-net/hi/aspose.slides/shapecollection/remove/#ishape) | शेप संग्रह से निर्दिष्ट शेप की पहली उपस्थिति को हटाता है। |
| [`clear(self)`](/slides/python-net/hi/aspose.slides/shapecollection/clear/#) | शेप संग्रह से सभी शेप्स को हटाता है। |

### संबंधित देखें
* क्लास [`IShape`](/slides/python-net/hi/aspose.slides/ishape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)