---
title: IVideoFrame
second_title: Aspose.Slides C++ API 参考
description: 表示幻灯片上的视频剪辑。
type: docs
weight: 4226
url: /zh/aspose.slides/ivideoframe/
---
## IVideoFrame 类


表示幻灯片上的视频剪辑。

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## 方法

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | 如果不存在，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | 创建并返回形状元素的数组。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | 返回形状在指定索引处的调整值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | 返回形状调整值的集合。只读 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | 返回与形状关联的替代文本。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | 返回与形状关联的替代文本的标题。读取 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | 属性指定形状在黑白显示模式下的渲染方式。读取 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | 获取与音频帧关联的隐藏字幕集合。此属性为只读，返回包含所有字幕轨道的 [ICaptionsCollection](../icaptionscollection/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | 返回形状上的连接点数量。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | 返回形状的自定义数据。只读 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | 返回包含应用于形状的像素效果的 [EffectFormat](../effectformat/) 对象。只读 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | 返回嵌入的视频对象。读取 [IVideo](../ivideo/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | 返回包含形状填充格式属性的 [FillFormat](../fillformat/) 对象。只读 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | 返回形状框架的属性。读取 [IShapeFrame](../ishapeframe/)。 |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | 确定视频是否以全屏模式显示。读取 **bool**。 |
| virtual **float** [get_Height](../ishape/get_height/)() | 获取形状的高度，单位为点。读取 **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | 确定形状是否隐藏。读取 **bool**。 |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | 确定 [VideoFrame](../videoframe/) 是否隐藏。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 返回为鼠标点击定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超链接管理器只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回为鼠标悬停定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 获取 ‘标记为装饰性’ 选项 读/写 **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | 确定形状是否已分组。只读 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | 确定形状是否为 TextHolder。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | 返回包含形状线条格式属性的 [LineFormat](../lineformat/) 对象。只读 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | 返回链接到 [VideoFrame](../videoframe/) 的视频文件名称。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | 返回形状的名称。读取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | 返回在幻灯片范围内唯一的标识符，在形状的整个生命周期保持不变，允许 PowerPoint 或互操作代码在文档任何位置可靠地引用该形状。只读 **uint32_t**。另请参阅 [IShape::get_UniqueId](../ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | 如果形状已分组，则返回父 [GroupShape](../groupshape/) 对象。否则返回 null。只读 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | 返回图片框架的 [PictureFillFormat](../picturefillformat/) 对象。只读 [IPictureFillFormat](../ipicturefillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | 返回 [PictureFrame](../pictureframe/) 的锁。只读 [IPictureFrameLock](../ipictureframelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | 返回形状的占位符。只读 [IPlaceholder](../iplaceholder/)。 |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | 确定视频是否循环播放。读取 **bool**。 |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | 返回视频播放模式。读取 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 返回原始形状框架的属性。读取 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | 返回图片框架高度的比例（相对于原始图片大小）。值 1.0 对应 100%。读取 **float**。 |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | 返回图片框架宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。读取 **float**。 |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | 确定视频在播放结束后是否自动倒回到起始位置。读取 **bool**。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 返回指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | 返回形状的锁。只读 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | 返回形状的样式对象。只读 [IShapeStyle](../ishapestyle/)。 |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | 返回几何预设类型。注意：值更改时，所有调整值将重置为默认值。读取 [Slides::ShapeType](../shapetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | 返回包含形状线条格式属性的 [ThreeDFormat](../threedformat/) 对象。只读 [IThreeDFormat](../ithreedformat/)。 |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | 修剪结束 [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | 修剪开始 [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于此值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另请参阅 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)。 |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | 返回音频音量。读取 [AudioVolumeMode](../audiovolumemode/)。 |
| virtual **float** [get_Width](../ishape/get_width/)() | 获取形状的宽度，单位为点。读取 **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | 获取形状左上角的 X 坐标，单位为点。读取 **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | 获取形状左上角的 Y 坐标，单位为点。读取 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | 返回形状在 Z 顺序中的位置。Shapes[0] 返回位于 Z 顺序后面的形状，Shapes[Shapes.Count - 1] 返回位于前面的形状。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状继承自该形状）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形状缩略图边界类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际并不拷贝任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际并不拷贝任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | 定义此形状不是占位符。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | 设置嵌入的视频对象。写入 [IVideo](../ivideo/)。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 设置形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | 确定视频是否以全屏模式显示。写入 **bool**。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | 设置形状的高度，单位为点。写入 **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | 确定形状是否隐藏。写入 **bool**。 |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | 确定 [VideoFrame](../videoframe/) 是否隐藏。写入 **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 设置 ‘标记为装饰性’ 选项 读/写 **bool**。 |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | 设置链接到 [VideoFrame](../videoframe/) 的视频文件名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | 设置形状的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | 确定视频是否循环。写入 **bool**。 |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | 设置视频播放模式。写入 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 设置原始形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | 设置图片框架高度的比例（相对于原始图片大小）。值 1.0 对应 100%。写入 **float**。 |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | 设置图片框架宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。写入 **float**。 |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | 确定视频在播放结束后是否自动倒回到起始位置。写入 **bool**。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。写入 **float**。 |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | 设置几何预设类型。注意：值更改时，所有调整值将重置为默认值。写入 [Slides::ShapeType](../shapetype/)。 |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | 修剪结束 [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | 修剪开始 [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | 设置音频音量。写入 [AudioVolumeMode](../audiovolumemode/)。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | 设置形状的宽度，单位为点。写入 **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | 设置形状左上角的 X 坐标，单位为点。写入 **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | 设置形状左上角的 Y 坐标，单位为点。写入 **float**。 |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | 从 [IGeometryPath](../igeometrypath/) 对象更新形状几何。坐标必须相对于形状的左上角。将形状类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | 从 [IGeometryPath](../igeometrypath/) 数组更新形状几何。坐标必须相对于形状的左上角。将形状类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [IPictureFrame](../ipictureframe/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)