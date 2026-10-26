---
title: VideoFrame
second_title: Aspose.Slides C++ API 参考
description: 表示幻灯片上的视频剪辑。
type: docs
weight: 5552
url: /zh/aspose.slides/videoframe/
---
## VideoFrame 类

表示幻灯片上的视频剪辑。

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在，则添加一个新占位符并将占位符属性设置为指定的占位符。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | 创建并返回形状元素的数组。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 返回形状在指定索引处的调整值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | 返回形状的调整值集合。只读 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 返回与形状关联的替代文本。只读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 返回与形状关联的替代文本的标题。只读 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 属性指定形状在黑白显示模式下的渲染方式。只读 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | 获取与视频帧关联的隐藏字幕集合。此属性为只读，并返回包含所有字幕轨道的 [ICaptionsCollection](../icaptionscollection/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 返回形状的连接点数量。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 返回形状的自定义数据。只读 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 返回包含形状像素效果的 [EffectFormat](../effectformat/) 对象。注意：对于没有效果属性的某些形状类型，可能返回 null。只读 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | 返回嵌入的视频对象。只读 [IVideo](../ivideo/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 返回包含形状填充格式属性的 [FillFormat](../fillformat/) 对象。注意：对于没有填充属性的某些形状类型，可能返回 null。只读 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 返回形状框架的属性。只读 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | 确定视频是否以全屏模式显示。只读 **bool**。 |
| **float** [get_Height](../shape/get_height/)() override | 获取形状的高度，单位为点。只读 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 确定形状是否隐藏。只读 **bool**。 |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | 确定 [VideoFrame](./) 是否隐藏。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 返回为鼠标点击定义的超链接。只读 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 返回超链接管理器。只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 返回为鼠标悬停定义的超链接。只读 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | 确定 [PictureFrame](../pictureframe/) 是否为 Cameo 对象。只读 **bool**。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 获取‘标记为装饰’选项，读/写 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 确定形状是否已分组。只读 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 确定形状是否为 TextHolder_PPT。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 返回包含形状线条格式属性的 [LineFormat](../lineformat/) 对象。注意：对于没有线条属性的某些形状类型，可能返回 null。只读 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | 返回链接到 [VideoFrame](./) 的视频文件名。只读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 返回形状的名称。不能为空。如有需要可使用空字符串。只读 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 返回在幻灯片范围内唯一的标识符，该标识符在形状的整个生命周期保持不变，可用于 PowerPoint 或互操作代码可靠地从文档任意位置引用该形状。只读 **uint32_t**。另见 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果形状已分组，返回父 [GroupShape](../groupshape/) 对象。否则返回 null。只读 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | 返回图片框架的 [PictureFillFormat](../picturefillformat/) 对象。只读 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | 返回形状的锁定状态。只读 [IPictureFrameLock](../ipictureframelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../iplaceholder/)。 |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | 确定视频是否循环播放。只读 **bool**。 |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | 返回视频播放模式。只读 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 返回幻灯片的父演示文稿。只读 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 返回原始形状框架的属性。只读 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | 返回图片框架高度的比例（相对于原始图片大小）。值 1.0 对应 100%。只读 **float**。 |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | 返回图片框架宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。只读 **float**。 |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | 确定视频是否在播放结束后自动倒回到开始。只读 **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 返回指定形状绕 z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。只读 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 返回形状的锁定状态。只读 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | 返回形状的样式对象。只读 [IShapeStyle](../ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 返回形状的父幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 返回包含形状 3D 效果属性的 [ThreeDFormat](../threedformat/) 对象。注意：对于没有 3D 属性的某些形状类型，可能返回 null。只读 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | 修剪结束 [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | 修剪开始 [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 返回内部的、面向演示文稿的标识符，供加载项或其他代码使用。由于此值可以被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另见 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | 返回音频音量。只读 [AudioVolumeMode](../audiovolumemode/)。 |
| **float** [get_Width](../shape/get_width/)() override | 获取形状的宽度，单位为点。只读 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 获取形状左上角的 x 坐标，单位为点。只读 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 获取形状左上角的 y 坐标，单位为点。只读 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最靠后的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从中继承）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | 返回几何形状路径的副本。坐标相对于形状左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于自定义对象的散列。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形状缩略图边界类型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 获取根据渲染内容计算的形状可视边界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 所描述类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。用于克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定义此形状不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | 设置嵌入的视频对象。写入 [IVideo](../ivideo/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | 确定视频是否以全屏模式显示。写入 **bool**。 |
| void [set_Height](../shape/set_height/)(**float**) override | 设置形状的高度，单位为点。写入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 确定形状是否隐藏。写入 **bool**。 |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | 确定 [VideoFrame](./) 是否隐藏。写入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 设置‘标记为装饰’选项，读/写 **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | 设置链接到 [VideoFrame](./) 的视频文件名。写入 [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 设置形状的名称。不能为空。如有需要可使用空字符串。写入 [System::String](../../system/string/)。 |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | 确定视频是否循环播放。写入 **bool**。 |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | 设置视频播放模式。写入 [VideoPlayModePreset](../videoplaymodepreset/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置原始形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | 设置图片框架高度的比例（相对于原始图片大小）。值 1.0 对应 100%。写入 **float**。 |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | 设置图片框架宽度的比例（相对于原始图片大小）。值 1.0 对应 100%。写入 **float**。 |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | 确定视频是否在播放结束后自动倒回到开始。写入 **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 设置指定形状绕 z 轴旋转的角度（度），正值顺时针，负值逆时针。写入 **float**。 |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | 修剪结束 [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | 修剪开始 [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | 设置音频音量。写入 [AudioVolumeMode](../audiovolumemode/)。 |
| void [set_Width](../shape/set_width/)(**float**) override | 设置形状的宽度，单位为点。写入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 设置形状左上角的 x 坐标，单位为点。写入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 设置形状左上角的 y 坐标，单位为点。写入 **float**。 |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | 从 [IGeometryPath](../igeometrypath/) 对象更新形状几何。坐标必须相对于形状左上角。将形状类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | 从 [IGeometryPath](../igeometrypath/) 数组更新形状几何。坐标必须相对于形状左上角。将形状类型（[ShapeType](../shapetype/)）更改为 [ShapeType::Custom](../shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。用于将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 将 [Shape](../shape/) 的内容保存为 SVG 文件。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 将 [Shape](../shape/) 的内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [PictureFrame](../pictureframe/)
* 类 [IVideoFrame](../ivideoframe/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)