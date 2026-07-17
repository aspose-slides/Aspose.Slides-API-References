---
title: AudioFrame
second_title: Aspose.Slides C++ API 参考
description: 表示幻灯片上的音频剪辑。
type: docs
weight: 53
url: /zh/aspose.slides/audioframe/
---
## AudioFrame 类


表示幻灯片上的音频剪辑。

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在则添加新的占位符，并将占位符属性设置为指定的占位符。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | 创建并返回 shape 的元素数组。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿照 C# 的浮点比较，即使两个 NaN 按 IEC 60559:1989 标准本应不相等，也视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿照 C# 的浮点比较，即使两个 NaN 按 IEC 60559:1989 标准本应不相等，也视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 返回指定索引处 shape 的调整值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | 返回 shape 的调整值集合。只读 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 返回与 shape 关联的替代文本。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 返回与 shape 关联的替代文本标题。读取 [System::String](../../system/string/)。 |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | 返回最后一个轨道索引。读取 **int32_t**。 |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | 返回最后一个轨道时间。读取 **int32_t**。 |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | 返回起始轨道索引。读取 **int32_t**。 |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | 返回起始轨道时间。读取 **int32_t**。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 属性指定 shape 在黑白显示模式下的渲染方式。读取 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | 获取与音频帧关联的闭路字幕集合。此属性为只读，返回包含所有字幕轨道的 [ICaptionsCollection](../icaptionscollection/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 返回 shape 的连接点数量。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 返回 shape 的自定义数据。只读 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 返回包含 shape 像素效果的 [EffectFormat](../effectformat/) 对象。注意：对于某些没有效果属性的 shape，可能返回 null。只读 [IEffectFormat](../ieffectformat/)。 |
| **bool** [get_Embedded](./get_embedded/)() override | 确定演示文稿中是否嵌入了声音。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | 返回嵌入的音频对象。读取 [IAudio](../iaudio/)。 |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | 指定媒体初始淡入的时间持续量（毫秒）。读取 **float**。 |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | 指定媒体结束淡出的时间持续量（毫秒）。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 返回包含 shape 填充格式属性的 [FillFormat](../fillformat/) 对象。注意：对于某些没有填充属性的 shape，可能返回 null。只读 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 返回 shape 框架的属性。读取 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Height](../shape/get_height/)() override | 获取 shape 的高度（以点为单位）。读取 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 确定 shape 是否隐藏。读取 **bool**。 |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | 确定 [AudioFrame](./) 是否隐藏。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 返回鼠标单击时定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 返回超链接管理器。只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 返回鼠标悬停时定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | 确定 [PictureFrame](../pictureframe/) 是否为 Cameo 对象。只读 **bool**。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 获取 “标记为装饰性” 选项。读/写 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 确定 shape 是否已分组。只读 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 确定 shape 是否为 TextHolder_PPT。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 返回包含 shape 线条格式属性的 [LineFormat](../lineformat/) 对象。注意：对于某些没有线条属性的 shape，可能返回 null。只读 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | 返回链接到 [AudioFrame](./) 的音频文件名称。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 返回 shape 的名称。不能为空。如有需要使用空字符串。读取 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 返回在幻灯片范围内唯一且在 shape 生命周期内保持不变的标识符，供 PowerPoint 或互操作代码可靠引用。只读 **uint32_t**。另见 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果 shape 已分组，返回父 [GroupShape](../groupshape/) 对象；否则返回 null。只读 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | 返回图片框的 [PictureFillFormat](../picturefillformat/) 对象。只读 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | 返回 shape 的锁定状态。只读 [IPictureFrameLock](../ipictureframelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 返回 shape 的占位符。如果 shape 没有占位符，则返回 null。只读 [IPlaceholder](../iplaceholder/)。 |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | 确定音频是否跨幻灯片播放。读取 **bool**。 |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | 确定音频是否循环播放。读取 **bool**。 |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | 返回音频播放模式。读取 [AudioPlayModePreset](../audioplaymodepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 返回幻灯片的父演示文稿。只读 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 返回原始 shape 框架属性。读取 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | 返回图片框高度相对于原始图片尺寸的比例。值 1.0 对应 100%。读取 **float**。 |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | 返回图片框宽度相对于原始图片尺寸的比例。值 1.0 对应 100%。读取 **float**。 |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | 确定音频在播放结束后是否自动倒回起始位置。读取 **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 返回指定 shape 绕 Z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 返回 shape 的锁定状态。只读 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | 返回 shape 的样式对象。只读 [IShapeStyle](../ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 返回 shape 所在的父幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 返回 shape 的 3D 效果属性对象 [ThreeDFormat](../threedformat/)。注意：对于某些没有 3D 属性的 shape，可能返回 null。只读 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | 指定在播放期间从媒体末尾移除的时间持续量（毫秒）。读取 **float**。 |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | 指定在播放期间从媒体开头移除的时间持续量（毫秒）。读取 **float**。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 返回供插件或其他代码使用的内部演示文稿作用域标识符。由于此值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另见 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | 返回音频音量。读取 [AudioVolumeMode](../audiovolumemode/)。 |
| **float** [get_VolumeValue](./get_volumevalue/)() override | 以百分比返回音频音量。读取 **float**。 |
| **float** [get_Width](../shape/get_width/)() override | 获取 shape 的宽度（以点为单位）。读取 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 获取 shape 左上角的 X 坐标（以点为单位）。读取 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 获取 shape 左上角的 Y 坐标（以点为单位）。读取 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 返回 shape 在 Z 顺序中的位置。Shapes[0] 为 Z 顺序最靠后，Shapes[Shapes.Count - 1] 为最前面。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 返回基本占位符 shape（来自布局或母版幻灯片的 shape，当前 shape 继承自该 shape）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | 返回几何 shape 路径的副本。坐标相对于 shape 左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。支持自定义对象的哈希。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 返回 shape 缩略图。默认使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape 缩略图边界类型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 返回 shape 缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 获取基于渲染内容计算的 shape 可视边界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# ‘is’ 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 用 nullptr 与值类型对象进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定义此 shape 不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 设置 shape 关联的替代文本。写入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 设置 shape 关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | 设置最后一个轨道索引。写入 **int32_t**。 |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | 设置最后一个轨道时间。写入 **int32_t**。 |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | 设置起始轨道索引。写入 **int32_t**。 |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | 设置起始轨道时间。写入 **int32_t**。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 属性指定 shape 在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 设置嵌入的音频对象。写入 [IAudio](../iaudio/)。 |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | 指定媒体初始淡入的时间持续量（毫秒）。写入 **float**。 |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | 指定媒体结束淡出的时间持续量（毫秒）。写入 **float**。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置 shape 框架属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 设置 shape 的高度（以点为单位）。写入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 设置 shape 是否隐藏。写入 **bool**。 |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | 设置 [AudioFrame](./) 是否隐藏。写入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置鼠标单击时的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置鼠标悬停时的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 设置 “标记为装饰性” 选项 读/写 **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | 设置链接到 [AudioFrame](./) 的音频文件名称。写入 [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 设置 shape 的名称。不能为空。必要时使用空字符串。写入 [System::String](../../system/string/)。 |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | 设置音频是否跨幻灯片播放。写入 **bool**。 |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | 设置音频是否循环播放。写入 **bool**。 |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | 设置音频播放模式。写入 [AudioPlayModePreset](../audioplaymodepreset/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置原始 shape 框架属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | 设置图片框高度相对于原始图片尺寸的比例。值 1.0 对应 100%。写入 **float**。 |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | 设置图片框宽度相对于原始图片尺寸的比例。值 1.0 对应 100%。写入 **float**。 |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | 设置音频在播放结束后是否自动倒回起始位置。写入 **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 设置指定 shape 绕 Z 轴旋转的角度（度）。正值表示顺时针，负值表示逆时针。写入 **float**。 |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | 指定在播放期间从媒体末尾移除的时间持续量（毫秒）。写入 **float**。 |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | 指定在播放期间从媒体开头移除的时间持续量（毫秒）。写入 **float**。 |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | 设置音频音量。写入 [AudioVolumeMode](../audiovolumemode/)。 |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | 设置音频音量（百分比）。写入 **float**。 |
| void [set_Width](../shape/set_width/)(**float**) override | 设置 shape 的宽度（以点为单位）。写入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 设置 shape 左上角的 X 坐标（以点为单位）。写入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 设置 shape 左上角的 Y 坐标（以点为单位）。写入 **float**。 |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | 根据 [IGeometryPath](../igeometrypath/) 对象更新 shape 几何。坐标必须相对于 shape 左上角。将 shape 类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | 根据 [IGeometryPath](../igeometrypath/) 数组更新 shape 几何。坐标必须相对于 shape 左上角。将 shape 类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 备注


以下示例展示了如何更改 [Audio](../audio/) 播放选项。 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [PictureFrame](../pictureframe/)
* 类 [IAudioFrame](../iaudioframe/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)