---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/
---
## ShapeCollection 类

表示形状的集合。

ShapeCollection 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/zh/aspose.slides/shapecollection/parent_group/) | 获取形状集合的父级组形状对象。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |

获取指定索引处的元素。
            只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape).

## 索引器

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/shapecollection/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 创建一个新图表，使用示例系列数据和设置进行初始化，并添加<br/>            它到形状集合的末尾。 |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/zh/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并添加<br/>            它到形状集合的末尾。 |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 创建一个新图表，使用示例系列数据和设置进行初始化，<br/>            并将其插入到指定索引处的形状集合中。 |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，<br/>            并将其插入到指定索引处的形状集合中。 |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/zh/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | 创建一个新的 Zoom 帧并将其添加到形状集合的末尾。 |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/zh/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 创建一个新的 Zoom 帧并将其添加到形状集合的末尾。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 创建一个新的 Zoom 帧并将其插入到指定索引处的形状集合中。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 创建一个带有预定义图像的 Zoom 帧，并将其插入到形状集合的指定索引处<br/>            。 |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/zh/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 创建一个新的 Section Zoom 帧并将其添加到形状集合的末尾。 |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/zh/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 创建一个带有预定义图像的 Section Zoom 帧并将其添加到形状集合的末尾。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 创建一个新的 Section Zoom 帧并将其插入到形状集合的指定索引处。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 创建一个带有预定义图像的 Section Zoom 帧，并将其插入到形状<br/>            集合的指定索引处。 |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/zh/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 创建一个新的 OLE 对象帧并将其添加到形状集合的末尾。 |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/zh/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 创建一个新的 OLE 对象帧并将其添加到形状集合的末尾。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 创建一个新的 OLE 对象帧并将其插入到指定索引处的形状集合中。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 创建一个新的 OLE 对象帧并将其插入到指定索引处的形状集合中。 |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | 创建一个新的视频帧并将其添加到形状集合的末尾。 |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/zh/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | 创建一个新的视频帧并将其添加到形状集合的末尾。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/zh/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 创建一个带有嵌入式 WAV 文件的音频帧并将其添加到形状集合的末尾<br/>            。嵌入的音频将被添加到 Presentation.Audios 集合中。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/zh/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其添加到形状集合的末尾。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 创建一个带有嵌入式 WAV 文件的音频帧，并将其插入到指定索引处的形状<br/>            集合中。嵌入的音频将被添加到 Presentation.Audios<br/>            集合中。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其插入到指定索引处的形状集合中。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/shapecollection/to_array/#) | 创建并返回包含所有形状的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/shapecollection/to_array/#int-int) | 创建并返回包含指定范围内所有形状的数组。 |
| [`reorder(self, index, shape)`](/slides/python-net/zh/aspose.slides/shapecollection/reorder/#int-ishape) | 将指定的形状移动到形状集合中的新位置。 |
| [`reorder(self, index, shapes)`](/slides/python-net/zh/aspose.slides/shapecollection/reorder/#int-listishape) | 在形状集合中移动指定的形状，从给定索引开始放置它们。 |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | 创建一个具有默认格式的新自动形状并将其添加到形状集合的末尾<br/>            。 |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 创建一个新自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 创建一个新自动形状并将其插入到指定索引处的形状集合中，<br/>            应用默认模板格式。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 创建一个新自动形状并将其插入到指定索引处的形状集合中，<br/>            可选择使用默认模板样式进行初始化。 |
| [`add_group_shape(self)`](/slides/python-net/zh/aspose.slides/shapecollection/add_group_shape/#) | 创建一个新的空组形状并将其添加到形状集合的末尾。<br/>            组的框架将自动调整以适应添加的任何形状。 |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | 创建一个新组形状，将指定的 SVG 图像转换为单独的形状，<br/>            并将生成的组添加到形状集合的末尾。 |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | 创建一个具有默认模板样式的新连接器形状并将其添加到形状集合的末尾<br/>            。 |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | 创建一个新连接器形状并将其添加到形状集合的末尾，<br/>            可选择应用默认模板样式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | 创建一个新连接器形状并将其插入到指定索引处的形状集合中，<br/>            应用默认模板样式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 创建一个新连接器形状并将其插入到指定索引处的形状集合中，<br/>            可选择应用默认模板样式。 |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/zh/aspose.slides/shapecollection/add_clone/#ishape-float-float) | 创建指定形状的副本并将其添加到形状集合的末尾。<br/>            新形状保留 `source_shape` 的宽度和高度。 |
| [`add_clone(self, source_shape)`](/slides/python-net/zh/aspose.slides/shapecollection/add_clone/#ishape) | 创建指定形状的副本并将其添加到形状集合的末尾。<br/>            克隆的形状保留原始形状的位置和尺寸。 |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | 创建指定形状的副本并将其插入到形状集合的指定索引处。 |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | 创建指定形状的副本并将其插入到形状集合的指定索引处。<br/>            新形状保留 `source_shape` 的宽度和高度。 |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_clone/#int-ishape) | 创建指定形状的副本并将其插入到形状集合的指定索引处。<br/>            克隆的形状保留原始形状的位置和尺寸。 |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/zh/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | 创建一个新的 Summary Zoom 帧并将其添加到形状集合的末尾。 |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 创建一个新的 Summary Zoom 帧并将其插入到形状集合的指定索引处。 |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | 创建一个新视频帧并将其插入到形状集合的指定索引处。 |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | 创建一个链接到 CD 曲目的新音频帧并将其添加到形状集合的末尾。 |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | 创建一个链接到 CD 曲目的新音频帧，并将其插入到形状集合的指定索引处<br/>            。 |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | 创建一个链接到外部音频文件的新音频帧并将其添加到形状集合的末尾<br/>            。 |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 创建一个链接到外部音频文件的新音频帧，并将其插入到形状集合的指定索引处<br/>            。 |
| [`index_of(self, shape)`](/slides/python-net/zh/aspose.slides/shapecollection/index_of/#ishape) | 返回集合中指定形状首次出现的从零开始的索引。 |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | 创建一个用于容纳数学内容的矩形自动形状并将其添加到形状集合的末尾<br/>            。 |
| [`insert_group_shape(self, index)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_group_shape/#int) | 创建一个新的空组形状并将其插入到形状集合的指定索引处。<br/>            组的框架将自动调整以适应添加的任何形状。 |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/zh/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 创建一个包含指定图像的新图片框并将其添加到形状集合的末尾<br/>            。 |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 创建一个包含指定图像的新图片框，并将其插入到形状集合的指定索引处<br/>            。 |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/zh/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/zh/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | 创建一个新表格并将其插入到形状集合的指定索引处。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/shapecollection/remove_at/#int) | 从形状集合中移除指定索引处的形状。 |
| [`remove(self, shape)`](/slides/python-net/zh/aspose.slides/shapecollection/remove/#ishape) | 从形状集合中移除指定形状的首次出现。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/shapecollection/clear/#) | 从形状集合中移除所有形状。 |

### 参见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)