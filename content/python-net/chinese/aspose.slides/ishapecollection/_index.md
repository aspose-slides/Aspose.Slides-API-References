---
title: IShapeCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/
---
## IShapeCollection 类

表示形状的集合。

IShapeCollection 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`parent_group`](/slides/python-net/zh/aspose.slides/ishapecollection/parent_group/) | 获取形状集合的父组形状对象。<br/>只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。 |

获取指定索引处的元素。  
只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。

## Indexer

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/ishapecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 创建一个新图表，使用示例系列数据和设置进行初始化，<br/>并将其插入到形状集合的指定索引处。 |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 创建一个新图表，使用示例系列数据和设置进行初始化，<br/>并将其插入到形状集合的指定索引处。 |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 创建一个新的 OLE 对象框架并将其插入到形状集合的指定索引处。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 创建一个新的 OLE 对象框架并将其插入到形状集合的指定索引处。 |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | 创建一个新的缩放框架并将其添加到形状集合的末尾。 |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 创建一个新的缩放框架并将其添加到形状集合的末尾。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 创建一个新的缩放框架并将其插入到形状集合的指定索引处。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 创建一个带预定义图像的缩放框架，并将其插入到形状集合的<br/>指定索引处。 |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 创建一个新的章节缩放框架并将其添加到形状集合的末尾。 |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 创建一个带预定义图像的章节缩放框架并将其添加到形状集合的<br/>末尾。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 创建一个新的章节缩放框架并将其插入到形状集合的<br/>指定索引处。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 创建一个带预定义图像的章节缩放框架并将其插入到形状集合的<br/>指定索引处。 |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | 创建一个新的视频框架并将其添加到形状集合的末尾。 |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | 创建一个新的视频框架并将其添加到形状集合的末尾。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 创建一个带嵌入 WAV 文件的音频框架并将其添加到形状集合的<br/>末尾。嵌入的音频会添加到 Presentation.Audios 集合中。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 使用 Presentation.Audios 列表中的现有音频对象，创建一个新音频框架并将其添加到形状集合的末尾。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 创建一个带嵌入 WAV 文件的音频框架，并将其插入到形状集合的<br/>指定索引处。嵌入的音频会添加到 Presentation.Audios<br/>集合中。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 使用 Presentation.Audios 列表中的现有音频对象，创建一个音频框架并将其插入到形状集合的指定索引处。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/ishapecollection/to_array/#) | 创建并返回包含所有形状的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/ishapecollection/to_array/#int-int) | 创建并返回包含指定范围内所有形状的数组。 |
| [`reorder(self, index, shape)`](/slides/python-net/zh/aspose.slides/ishapecollection/reorder/#int-ishape) | 将指定形状移动到形状集合中的新位置。 |
| [`reorder(self, index, shapes)`](/slides/python-net/zh/aspose.slides/ishapecollection/reorder/#int-listishape) | 将指定形状在形状集合中移动，按给定索引开始放置。 |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | 创建一个带默认格式的自动形状并将其添加到形状集合的末尾。 |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 创建一个新的自动形状并将其添加到形状集合的末尾，可选地使用默认模板格式进行初始化。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 创建一个新的自动形状并将其插入到形状集合的指定索引处，<br/>应用默认模板格式。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 创建一个新的自动形状并将其插入到形状集合的指定索引处，<br/>可选地使用默认模板样式进行初始化。 |
| [`add_group_shape(self)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_group_shape/#) | 创建一个新的空组形状并将其添加到形状集合的末尾。<br/>组的框架将自动调整以适应添加的任何形状。 |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | 创建一个新的组形状，将指定的 SVG 图像转换为单个形状，<br/>并将生成的组添加到形状集合的末尾。 |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | 创建一个带默认模板样式的连接器形状并将其添加到形状集合的末尾。 |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | 创建一个新的连接器形状并将其添加到形状集合的末尾，<br/>可选地应用默认模板样式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | 创建一个新的连接器形状并将其插入到形状集合的指定索引处，<br/>应用默认模板样式。 |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 创建一个新的连接器形状并将其插入到形状集合的指定索引处，<br/>可选地应用默认模板样式。 |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | 创建指定形状的副本并将其添加到形状集合的末尾。<br/>新形状保留 `source_shape` 的宽度和高度。 |
| [`add_clone(self, source_shape)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_clone/#ishape) | 创建指定形状的副本并将其添加到形状集合的末尾。<br/>克隆形状保留原始的位置信息和大小。 |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | 创建指定形状的副本并将其插入到形状集合的指定索引处。 |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | 创建指定形状的副本并将其插入到形状集合的指定索引处。<br/>新形状保留 `source_shape` 的宽度和高度。 |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_clone/#int-ishape) | 创建指定形状的副本并将其插入到形状集合的指定索引处。<br/>克隆形状保留原始的位置信息和大小。 |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | 创建一个 SmartArt 图表并将其添加到形状集合的末尾。 |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | 创建一个新的摘要缩放框架并将其添加到形状集合的末尾。 |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 创建一个新的摘要缩放框架并将其插入到形状集合的指定索引处。 |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | 创建一个新的视频框架并将其插入到形状集合的指定索引处。 |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | 创建一个链接到 CD 曲目的音频框架并将其添加到形状集合的末尾。 |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | 创建一个链接到 CD 曲目的音频框架并将其插入到形状集合的<br/>指定索引处。 |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | 创建一个链接到外部音频文件的音频框架并将其添加到形状集合的<br/>末尾。 |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 创建一个链接到外部音频文件的音频框架并将其插入到形状集合的<br/>指定索引处。 |
| [`index_of(self, shape)`](/slides/python-net/zh/aspose.slides/ishapecollection/index_of/#ishape) | 返回集合中首次出现指定形状的零基索引。 |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | 创建一个新的矩形自动形状以容纳数学内容，并将其添加到形状集合的<br/>末尾。 |
| [`insert_group_shape(self, index)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_group_shape/#int) | 创建一个新的空组形状并将其插入到形状集合的指定索引处。<br/>组的框架将自动调整以适应添加的任何形状。 |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 创建一个包含指定图像的图片框架并将其添加到形状集合的末尾。 |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 创建一个包含指定图像的图片框架并将其插入到形状集合的指定索引处。 |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/zh/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/zh/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | 创建一个新表格并将其插入到形状集合的指定索引处。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/ishapecollection/remove_at/#int) | 删除指定索引处的形状。 |
| [`remove(self, shape)`](/slides/python-net/zh/aspose.slides/ishapecollection/remove/#ishape) | 删除集合中首次出现的指定形状。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/ishapecollection/clear/#) | 删除形状集合中的所有形状。 |

### 参见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)