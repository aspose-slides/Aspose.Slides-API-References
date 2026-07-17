---
title: InkActions
second_title: Aspose.Slides for C++ API 参考
description: 表示墨水操作的根。
type: docs
weight: 66
url: /zh/aspose.slides.ink/inkactions/
---
## InkActions 类


Represents the root of ink actions.

```cpp
class InkActions : public Aspose::Slides::GraphicalObject,
                   public Aspose::Slides::Ink::IInkActions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | 如果不存在，则添加一个新的占位符，并将占位符属性设置为指定的占位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | 返回与形状关联的替代文本。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | 返回与形状关联的替代文本标题。阅读 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | 属性指定形状在黑白显示模式下的渲染方式。阅读 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | 返回形状上的连接点数量。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | 返回形状的自定义数据。只读 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | 返回包含应用于形状的像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 对象。注意：对于某些没有效果属性的形状类型，可能返回 null。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | 返回包含形状填充格式属性的 [FillFormat](../../aspose.slides/fillformat/) 对象。注意：对于某些没有填充属性的形状类型，可能返回 null。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | 返回形状框架的属性。阅读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | 返回形状的锁定状态。只读 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | 获取形状的高度，单位为点。只读 **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | 确定形状是否隐藏。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | 返回为鼠标点击定义的超链接。阅读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | 返回超链接管理器。只读 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | 返回为鼠标悬停定义的超链接。阅读 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 获取“标记为装饰”选项。读/写 **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | 确定形状是否已分组。只读 **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | 确定形状是否为 TextHolder_PPT。只读 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | 返回包含形状线条格式属性的 [LineFormat](../../aspose.slides/lineformat/) 对象。注意：对于某些没有线条属性的形状类型，可能返回 null。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | 返回形状的名称。必须非空。如有需要使用空字符串。阅读 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | 返回在幻灯片范围内唯一的标识符，该标识符在形状生命周期内保持不变，并允许 PowerPoint 或互操作代码在文档任何位置可靠地引用该形状。只读 **uint32_t**。另见 [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | 如果形状已分组，则返回父级 [GroupShape](../../aspose.slides/groupshape/) 对象；否则返回 null。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | 返回幻灯片的父演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 返回原始形状框架的属性。阅读 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 返回指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。只读 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | 返回形状的锁定状态。只读 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | 返回形状的父幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | 返回包含形状 3D 效果属性的 [ThreeDFormat](../../aspose.slides/threedformat/) 对象。注意：对于某些没有 3D 属性的形状类型，可能返回 null。只读 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另见 [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | 获取形状的宽度，单位为点。只读 **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | 获取形状左上角的 x 坐标，单位为点。只读 **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | 获取形状左上角的 y 坐标，单位为点。只读 **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | 返回形状在 Z 顺序中的位置。Shapes[0] 返回位于 Z 顺序最底层的形状，Shapes[Shapes.Count - 1] 返回位于最前面的形状。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状继承自该形状）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形状缩略图边界类型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | 获取根据渲染内容计算的形状可视边界。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | 定义此形状不是占位符。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 设置形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | 设置形状的高度，单位为点。写入 **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | 确定形状是否隐藏。写入 **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 设置“标记为装饰”选项。读/写 **bool**。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | 设置形状的名称。必须非空。如有需要使用空字符串。写入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 设置原始形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。写入 **float**。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | 设置形状的宽度，单位为点。写入 **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | 设置形状左上角的 x 坐标，单位为点。写入 **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | 设置形状左上角的 y 坐标，单位为点。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [GraphicalObject](../../aspose.slides/graphicalobject/)
* 类 [IInkActions](../iinkactions/)
* 命名空间 [Aspose::Slides::Ink](../)
* 库 [Aspose.Slides](../../)