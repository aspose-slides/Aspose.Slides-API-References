---
title: IShapeCollection class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/
---
## الفئة IShapeCollection

يمثل مجموعة من الأشكال.

يعرض نوع IShapeCollection الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`parent_group`](/slides/python-net/ar/aspose.slides/ishapecollection/parent_group/) | يحصل على كائن مجموعة الشكل الأب لمجموعة الأشكال.<br/>            للقراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |

## الفهرس

| الاسم | الوصف |
| :- | :- |
| [`[index]`](/slides/python-net/ar/aspose.slides/ishapecollection/__getitem__/) | يحصل على العنصر عند الفهرس المحدد.<br/>            للقراءة فقط [`IShape`](/slides/python-net/ar/aspose.slides/ishape). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه<br/>            إلى نهاية مجموعة الأشكال. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه<br/>            إلى نهاية مجموعة الأشكال. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينة وإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | ينشئ إطار Zoom جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | ينشئ إطار Zoom جديد مع صورة محددة مسبقًا ويُدرجه في مجموعة الأشكال<br/>            عند الفهرس المحدد. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | ينشئ إطار Section Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | ينشئ إطار Section Zoom جديد مع صورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | ينشئ إطار Section Zoom جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | ينشئ إطار Section Zoom جديد مع صورة محددة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | ينشئ إطار صوتي جديد مع ملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال.<br/>            يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | ينشئ إطار صوتي جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | ينشئ إطار صوتي جديد مع ملف WAV مدمج ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.<br/>            يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | ينشئ إطار صوتي جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/ar/aspose.slides/ishapecollection/to_array/#) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [`to_array(self, start_index, count)`](/slides/python-net/ar/aspose.slides/ishapecollection/to_array/#int-int) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |
| [`reorder(self, index, shape)`](/slides/python-net/ar/aspose.slides/ishapecollection/reorder/#int-ishape) | ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال. |
| [`reorder(self, index, shapes)`](/slides/python-net/ar/aspose.slides/ishapecollection/reorder/#int-listishape) | ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المعطى. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع تهيئته بتنسيق القالب الافتراضي. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تهيئته بتنسيق القالب الافتراضي. |
| [`add_group_shape(self)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_group_shape/#) | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال.<br/>            سيتعدل إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | ينشئ مجموعة أشكال جديدة، يحول الصورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | ينشئ شكل موصل جديد بتنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع تطبيق تنسيق القالب الافتراضي. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي اختيارياً. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.<br/>            يحتفظ الشكل الجديد بعرض وارتفاع `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_clone/#ishape) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.<br/>            يحتفظ الشكل المستنسخ بموقع وحجم الأصلي. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.<br/>            يحتفظ الشكل الجديد بعرض وارتفاع `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_clone/#int-ishape) | ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.<br/>            يحتفظ الشكل المستنسخ بموقع وحجم الأصلي. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | ينشئ إطار Summary Zoom جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | ينشئ إطار صوتي جديد مرتبط بمسار CD ويُدرجه في مجموعة الأشكال<br/>            عند الفهرس المحدد. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | ينشئ إطار صوتي جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`index_of(self, shape)`](/slides/python-net/ar/aspose.slides/ishapecollection/index_of/#ishape) | يعيد الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | ينشئ شكلًا تلقائيًا مستطيلًا جديدًا لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_group_shape(self, index)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_group_shape/#int) | ينشئ مجموعة أشكال فارغة جديدة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.<br/>            سيتعدل إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/ar/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/ar/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. |
| [`remove_at(self, index)`](/slides/python-net/ar/aspose.slides/ishapecollection/remove_at/#int) | يزيل الشكل عند الفهرس المحدد من مجموعة الأشكال. |
| [`remove(self, shape)`](/slides/python-net/ar/aspose.slides/ishapecollection/remove/#ishape) | يزيل الظهور الأول للشكل المحدد من مجموعة الأشكال. |
| [`clear(self)`](/slides/python-net/ar/aspose.slides/ishapecollection/clear/#) | يزيل جميع الأشكال من مجموعة الأشكال. |

### انظر أيضًا
* الفئة [`IShape`](/slides/python-net/ar/aspose.slides/ishape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)