---
title: AudioFrame class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/audioframe/
---
## AudioFrame 类

表示幻灯片上的音频剪辑。

**继承:**[`AudioFrame`](/slides/python-net/zh/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/zh/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/zh/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

AudioFrame 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/audioframe/is_text_holder/) | 确定形状是否为 TextHolder_PPT。<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/audioframe/placeholder/) | 返回形状的占位符。如果形状没有占位符，则返回 None。<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/audioframe/custom_data/) | 返回形状的自定义数据。<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/audioframe/raw_frame/) | 返回或设置原始形状框架的属性。<br/>            可读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/audioframe/frame/) | 返回或设置形状框架的属性。<br/>            可读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/audioframe/line_format/) | 返回包含形状线条格式属性的 LineFormat 对象。<br/>            注意：对某些没有线条属性的形状类型可能返回 None。<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/audioframe/three_d_format/) | 返回包含形状 3D 效果属性的 ThreeDFormat 对象。<br/>            注意：对某些没有 3D 属性的形状类型可能返回 None。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/audioframe/effect_format/) | 返回包含形状像素效果的 EffectFormat 对象。<br/>            注意：对某些没有效果属性的形状类型可能返回 None。<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/audioframe/fill_format/) | 返回包含形状填充格式属性的 FillFormat 对象。<br/>            注意：对某些没有填充属性的形状类型可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/audioframe/hyperlink_click/) | 返回或设置鼠标点击时定义的超链接。<br/>            可读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/audioframe/hyperlink_mouse_over/) | 返回或设置鼠标悬停时定义的超链接。<br/>            可读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/audioframe/hyperlink_manager/) | 返回超链接管理器。<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides/audioframe/hidden/) | 确定形状是否隐藏。<br/>            可读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/audioframe/z_order_position/) | 返回形状在 Z 顺序中的位置。<br/>            Shapes[0] 返回位于 Z 顺序后端的形状，<br/>            而 Shapes[Shapes.Count - 1] 返回位于 Z 顺序前端的形状。<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/audioframe/connection_site_count/) | 返回形状的连接点数量。<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/audioframe/rotation/) | 返回或设置指定形状围绕 z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。<br/>            可读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/audioframe/x/) | 获取或设置形状左上角的 x 坐标，以点为单位。<br/>            可读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/audioframe/y/) | 获取或设置形状左上角的 y 坐标，以点为单位。<br/>            可读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/audioframe/width/) | 获取或设置形状的宽度，以点为单位。<br/>            可读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/audioframe/height/) | 获取或设置形状的高度，以点为单位。<br/>            可读写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/audioframe/black_white_mode/) | 属性指定形状在黑白显示模式下的渲染方式。<br/>            可读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/audioframe/unique_id/) | 返回内部的、面向演示文稿范围的标识符，供加载项或其他代码使用。<br/>            由于该值可以被用户或程序重新分配，不能将其视为持久唯一键。<br/>            只读 **int**。<br/>            另见 [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/audioframe/office_interop_shape_id/) | 返回幻灯片范围的唯一标识符，该标识符在形状生命周期内保持不变，PowerPoint 或互操作代码可可靠地从文档任何位置引用该形状。<br/>            只读 **int**。<br/>            另见 [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/audioframe/alternative_text/) | 返回或设置与形状关联的替代文本。<br/>            可读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/audioframe/alternative_text_title/) | 返回或设置与形状关联的替代文本的标题。<br/>            可读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/audioframe/name/) | 返回或设置形状的名称。<br/>            必须非 None。如有需要请使用空字符串。<br/>            可读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/audioframe/is_decorative/) | 获取或设置“标记为装饰”选项<br/>            可读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/audioframe/shape_lock/) | 返回形状的锁定状态。<br/>            只读 [`IPictureFrameLock`](/slides/python-net/zh/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/audioframe/is_grouped/) | 确定形状是否已分组。<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides/audioframe/parent_group/) | 如果形状已分组，返回父 GroupShape 对象；否则返回 None。<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/audioframe/slide/) | 返回形状所属的父幻灯片。<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides/audioframe/presentation/) | 返回幻灯片所属的父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/zh/aspose.slides/audioframe/shape_style/) | 返回形状的样式对象。<br/>            只读 [`IShapeStyle`](/slides/python-net/zh/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/zh/aspose.slides/audioframe/shape_type/) | 返回或设置 PictureFrame 的 AutoShape 类型。<br/>            允许的所有项目属于集合 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype)，<br/>            除了所有线条类型：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            可读写 [`ShapeType`](/slides/python-net/zh/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/zh/aspose.slides/audioframe/adjustments/) | 返回形状的调整值集合。<br/>            只读 [`IAdjustValueCollection`](/slides/python-net/zh/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/zh/aspose.slides/audioframe/picture_frame_lock/) | 返回形状的锁定状态。<br/>            只读 [`IPictureFrameLock`](/slides/python-net/zh/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/zh/aspose.slides/audioframe/picture_format/) | 返回图片框的 PictureFillFormat 对象。<br/>            只读 [`IPictureFillFormat`](/slides/python-net/zh/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/zh/aspose.slides/audioframe/relative_scale_height/) | 返回或设置图片框高度的比例（相对于原始图片大小）。值 1.0 对应 100%。<br/>            可读写 **float**. |
| [`relative_scale_width`](/slides/python-net/zh/aspose.slides/audioframe/relative_scale_width/) | 返回或设置图片框宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。<br/>            可读写 **float**. |
| [`is_cameo`](/slides/python-net/zh/aspose.slides/audioframe/is_cameo/) | 确定 PictureFrame 是否为 Cameo 对象。<br/>            只读 **bool**. |
| [`audio_cd_start_track`](/slides/python-net/zh/aspose.slides/audioframe/audio_cd_start_track/) | 返回或设置起始轨道索引。<br/>            可读写 **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/zh/aspose.slides/audioframe/audio_cd_start_track_time/) | 返回或设置起始轨道时间。<br/>            可读写 **int**. |
| [`audio_cd_end_track`](/slides/python-net/zh/aspose.slides/audioframe/audio_cd_end_track/) | 返回或设置最后轨道索引<br/>            可读写 **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/zh/aspose.slides/audioframe/audio_cd_end_track_time/) | 返回或设置最后轨道时间。<br/>            可读写 **int**. |
| [`volume`](/slides/python-net/zh/aspose.slides/audioframe/volume/) | 返回或设置音频音量。<br/>            可读写 [`AudioVolumeMode`](/slides/python-net/zh/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/zh/aspose.slides/audioframe/play_mode/) | 返回或设置音频播放模式。<br/>            可读写 [`AudioPlayModePreset`](/slides/python-net/zh/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/zh/aspose.slides/audioframe/hide_at_showing/) | 确定 AudioFrame 是否隐藏。<br/>            可读写 **bool**. |
| [`play_loop_mode`](/slides/python-net/zh/aspose.slides/audioframe/play_loop_mode/) | 确定音频是否循环播放。<br/>            可读写 **bool**. |
| [`play_across_slides`](/slides/python-net/zh/aspose.slides/audioframe/play_across_slides/) | 确定音频是否跨幻灯片播放。<br/>             可读写 **bool**. |
| [`rewind_audio`](/slides/python-net/zh/aspose.slides/audioframe/rewind_audio/) | 确定音频在播放后是否自动倒回到开头。<br/>             可读写 **bool**. |
| [`embedded`](/slides/python-net/zh/aspose.slides/audioframe/embedded/) | 确定声音是否嵌入到演示文稿中。<br/>            只读 **bool**. |
| [`link_path_long`](/slides/python-net/zh/aspose.slides/audioframe/link_path_long/) | 返回或设置链接到 AudioFrame 的音频文件名称。<br/>            可读写 **str**. |
| [`embedded_audio`](/slides/python-net/zh/aspose.slides/audioframe/embedded_audio/) | 返回或设置嵌入的音频对象。<br/>            可读写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/zh/aspose.slides/audioframe/fade_in_duration/) | 指定媒体初始淡入的时间持续量（毫秒）。<br/>             可读写 **float**. |
| [`fade_out_duration`](/slides/python-net/zh/aspose.slides/audioframe/fade_out_duration/) | 指定媒体结束淡出的时间持续量（毫秒）。<br/>             可读写 **float**. |
| [`volume_value`](/slides/python-net/zh/aspose.slides/audioframe/volume_value/) | 返回或设置音频音量（百分比）。<br/>             可读写 **float**. |
| [`trim_from_start`](/slides/python-net/zh/aspose.slides/audioframe/trim_from_start/) | 指定在播放期间从媒体开头删除的时间持续量（毫秒）。<br/>            可读写 **float**. |
| [`trim_from_end`](/slides/python-net/zh/aspose.slides/audioframe/trim_from_end/) | 指定在播放期间从媒体结尾删除的时间持续量（毫秒）。<br/>            可读写 **float**. |
| [`caption_tracks`](/slides/python-net/zh/aspose.slides/audioframe/caption_tracks/) | 获取与音频帧关联的闭字幕集合。<br/>            此属性为只读，返回包含所有字幕轨道的 [`ICaptionsCollection`](/slides/python-net/zh/aspose.slides/icaptionscollection)。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/audioframe/get_image/#) | 返回形状缩略图。<br/>            默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | 返回形状缩略图。 |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/audioframe/write_as_svg/#iorawiobase) | 将形状内容保存为 SVG 文件。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 将形状内容保存为 SVG 文件。 |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/audioframe/remove_placeholder/#) | 定义此形状不是占位符。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/audioframe/add_placeholder/#iplaceholder) | 如果不存在，则添加新占位符并将占位符属性设置为指定的属性。 |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/audioframe/get_base_placeholder/#) | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从其继承）。<br/>            如果当前形状未继承，则返回 None。 |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/audioframe/get_visual_bounds/#) | 获取根据渲染内容计算得到的形状可视边界。 |
| [`get_geometry_paths(self)`](/slides/python-net/zh/aspose.slides/audioframe/get_geometry_paths/#) | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/zh/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | 从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。<br/>             将形状类型 ([`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/zh/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | 从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。<br/>             将形状类型 ([`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。 |
| [`create_shape_elements(self)`](/slides/python-net/zh/aspose.slides/audioframe/create_shape_elements/#) | 创建并返回形状元素的数组。 |

### 另请参阅
* 类 [`AudioFrame`](/slides/python-net/zh/aspose.slides/audioframe)
* 类 [`GeometryShape`](/slides/python-net/zh/aspose.slides/geometryshape)
* 类 [`PictureFrame`](/slides/python-net/zh/aspose.slides/pictureframe)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)