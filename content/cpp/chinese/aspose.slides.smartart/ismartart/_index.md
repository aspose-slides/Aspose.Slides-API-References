---
title: ISmartArt
second_title: Aspose.Slides for C++ API 参考
description: 表示一个 SmartArt 图表。
type: docs
weight: 1
url: /zh/aspose.slides.smartart/ismartart/
---
## ISmartArt 类


Represents a [SmartArt](../smartart/) diagram.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## 方法

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 如果不存在，则添加一个新的占位符并将占位符属性设置为指定的占位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | 返回 [SmartArt](../smartart/) 对象中所有节点的集合。只读 [ISmartArtNodeCollection](../ismartartnodecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 返回与形状关联的替代文本。只读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 返回与形状关联的替代文本的标题。只读 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 属性指定形状在黑白显示模式下的渲染方式。只读 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | 返回或设置 [SmartArt](../smartart/) 对象的颜色样式。只读 [SmartArtColorType](../smartartcolortype/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 返回形状的连接点数量。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 返回形状的自定义数据。只读 [ICustomData](../../aspose.slides/icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | 返回包含应用于形状的像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 对象。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | 返回包含形状填充格式属性的 [FillFormat](../../aspose.slides/fillformat/) 对象。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 返回形状框架的属性。只读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | 返回形状的锁定状态。只读 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 获取形状的高度（以点为单位）。只读 **float**。 |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 确定形状是否隐藏。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 返回为鼠标点击定义的超链接。只读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 超链接管理器。只读 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回为鼠标悬停定义的超链接。只读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 获取 “标记为装饰性” 选项。读/写 **bool**。 |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 确定形状是否已分组。只读 **bool**。 |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | 返回或设置 [SmartArt](../smartart/) 图表关于 (从左到右) LTR 或 (从右到左) RTL 的状态（如果图表支持反转）。只读 **bool**。 |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 确定形状是否为 TextHolder。只读 **bool**。 |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | 返回或设置 [SmartArt](../smartart/) 对象的布局。只读 [SmartArtLayoutType](../smartartlayouttype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | 返回包含形状线条格式属性的 [LineFormat](../../aspose.slides/lineformat/) 对象。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 返回形状的名称。只读 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | 在指定索引处返回 [SmartArt](../smartart/) 对象根节点集合中的节点。只读 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | 在指定索引处返回 [SmartArt](../smartart/) 对象中所有节点集合的节点。只读 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | 返回 [SmartArt](../smartart/) 对象中根节点的集合。只读 [ISmartArtNodeCollection](../ismartartnodecollection/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 返回一个在幻灯片范围内唯一的标识符，该标识符在形状的生命周期内保持不变，使 PowerPoint 或互操作代码能够从文档的任何位置可靠地引用该形状。只读 **uint32_t**。另请参阅 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 如果形状已分组，则返回父 [GroupShape](../../aspose.slides/groupshape/) 对象。否则返回 null。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 返回形状的占位符。只读 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | 返回或设置 [SmartArt](../smartart/) 对象的快速样式。只读 [SmartArtQuickStyleType](../smartartquickstyletype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 返回原始形状框架的属性。只读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 返回指定形状绕 z 轴旋转的角度（度）。正值表示顺时针旋转；负值表示逆时针旋转。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 返回形状的锁定状态。只读 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | 返回包含形状线条格式属性的 [ThreeDFormat](../../aspose.slides/threedformat/) 对象。只读 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 返回一个内部的、面向演示文稿的标识符，供加载项或其他代码使用。由于该值可能被用户或程序重新分配，不能将其视为持久唯一键。只读 **uint32_t**。另请参阅 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)。 |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 获取形状的宽度（以点为单位）。只读 **float**。 |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 获取形状左上角的 x 坐标（以点为单位）。只读 **float**。 |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 获取形状左上角的 y 坐标（以点为单位）。只读 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | 返回形状在 Z 顺序中的位置。Shapes[0] 返回 Z 顺序最靠后的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 返回一个基本占位符形状（来自布局或母版幻灯片的形状，当前形状继承自该形状）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形状缩略图边界类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 定义此形状不是占位符。 |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | 返回或设置 [SmartArt](../smartart/) 对象的颜色样式。写入 [SmartArtColorType](../smartartcolortype/)。 |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 设置形状的高度（以点为单位）。写入 **float**。 |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 确定形状是否隐藏。写入 **bool**。 |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 设置 “标记为装饰性” 选项。读/写 **bool**。 |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | 返回或设置 [SmartArt](../smartart/) 图表关于 (从左到右) LTR 或 (从右到左) RTL 的状态（如果图表支持反转）。写入 **bool**。 |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | 返回或设置 [SmartArt](../smartart/) 对象的布局。写入 [SmartArtLayoutType](../smartartlayouttype/)。 |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 设置形状的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | 返回或设置 [SmartArt](../smartart/) 对象的快速样式。写入 [SmartArtQuickStyleType](../smartartquickstyletype/)。 |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置原始形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 设置指定形状绕 z 轴旋转的角度。正值表示顺时针旋转；负值表示逆时针旋转。写入 **float**。 |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 设置形状的宽度（以点为单位）。写入 **float**。 |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 设置形状左上角的 x 坐标（以点为单位）。写入 **float**。 |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 设置形状左上角的 y 坐标（以点为单位）。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* 命名空间 [Aspose::Slides::SmartArt](../)
* 库 [Aspose.Slides](../../)