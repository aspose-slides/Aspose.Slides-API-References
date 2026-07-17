---
title: ISmartArtShape
second_title: Aspose.Slides for C++ API 参考
description: 表示 SmartArt 图表中的形状
type: docs
weight: 40
url: /zh/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape 类

表示 [SmartArt](../smartart/) 图表中的形状

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | 如果不存在，则添加一个新的占位符并将占位符属性设置为指定的占位符。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | 创建并返回形状元素的数组。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点数比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），但两个 NaN 被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点数比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），但两个 NaN 被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | 返回形状在指定索引处的调整值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | 返回形状调整值的集合。只读 [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | 返回与形状关联的替代文字。读取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | 返回与形状关联的替代文字的标题。读取 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | 属性指定形状在黑白显示模式下的渲染方式。读取 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | 返回形状的连接点数量。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | 返回形状的自定义数据。只读 [ICustomData](../../aspose.slides/icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | 返回包含应用于形状的像素效果的 [EffectFormat](../../aspose.slides/effectformat/) 对象。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | 返回包含形状填充格式属性的 [FillFormat](../../aspose.slides/fillformat/) 对象。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | 返回形状框架的属性。读取 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | 获取形状的高度（以点为单位）。读取 **float**。 |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | 确定形状是否隐藏。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | 返回为鼠标点击定义的超链接。读取 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | 超链接管理器，只读 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回为鼠标悬停定义的超链接。读取 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 获取“标记为装饰性”选项。读/写 **bool**。 |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | 确定形状是否已分组。只读 **bool**。 |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | 确定形状是否为 TextHolder。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | 返回包含形状线条格式属性的 [LineFormat](../../aspose.slides/lineformat/) 对象。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | 返回形状的名称。读取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | 返回在幻灯片范围内唯一标识符，该标识符在形状生命周期内保持不变，并让 PowerPoint 或互操作代码能够可靠地在文档任何位置引用该形状。只读 **uint32_t**。另见 [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | 如果形状已分组，则返回父 [GroupShape](../../aspose.slides/groupshape/) 对象。否则返回 null。只读 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | 返回形状的占位符。只读 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 返回原始形状框架的属性。读取 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 返回指定形状绕 z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | 返回形状的锁定状态。只读 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | 返回形状的样式对象。只读 [IShapeStyle](../../aspose.slides/ishapestyle/)。 |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | 返回几何预设类型。注意：值改变时，所有调整值将重置为默认值。读取 [Slides::ShapeType](../../aspose.slides/shapetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | 返回 [SmartArt](../smartart/) 形状的文本。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | 返回包含形状线条格式属性的 [ThreeDFormat](../../aspose.slides/threedformat/) 对象。只读 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另见 [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)。 |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | 获取形状的宽度（以点为单位）。读取 **float**。 |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | 获取形状左上角的 X 坐标（以点为单位）。读取 **float**。 |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | 获取形状左上角的 Y 坐标（以点为单位）。读取 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | 返回形状在 z 顺序中的位置。Shapes[0] 返回位于 z 顺序最底层的形状，Shapes[Shapes.Count - 1] 返回位于最前面的形状。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 返回基本占位符形状（来自布局和/或母版幻灯片的形状，当前形状从中继承）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | 返回几何形状路径的副本。坐标相对于形状的左上角。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) 形状缩略图边界类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许复制构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | 定义此形状不是占位符。 |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | 设置与形状关联的替代文字。写入 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | 设置与形状关联的替代文字的标题。写入 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | 设置形状的高度（以点为单位）。写入 **float**。 |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | 确定形状是否隐藏。写入 **bool**。 |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 设置“标记为装饰性”选项。读/写 **bool**。 |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | 设置形状的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 设置原始形状框架的属性。写入 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 设置指定形状绕 z 轴旋转的角度（度）。正值表示顺时针旋转，负值表示逆时针旋转。写入 **float**。 |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | 设置几何预设类型。注意：值改变时，所有调整值将重置为默认值。写入 [Slides::ShapeType](../../aspose.slides/shapetype/)。 |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | 设置形状的宽度（以点为单位）。写入 **float**。 |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | 设置形状左上角的 X 坐标（以点为单位）。写入 **float**。 |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | 设置形状左上角的 Y 坐标（以点为单位）。写入 **float**。 |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | 从 [IGeometryPath](../../aspose.slides/igeometrypath/) 对象更新形状几何。坐标必须相对于形状的左上角。将形状类型（[ShapeType](../../aspose.slides/shapetype/)）更改为 [ShapeType::Custom](../../aspose.slides/shapetype/)。 |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | 从 [IGeometryPath](../../aspose.slides/igeometrypath/) 数组更新形状几何。坐标必须相对于形状的左上角。将形状类型（[ShapeType](../../aspose.slides/shapetype/)）更改为 [ShapeType::Custom](../../aspose.slides/shapetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Shape](../../aspose.slides/shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IGeometryShape](../../aspose.slides/igeometryshape/)
* 命名空间 [Aspose::Slides::SmartArt](../)
* 库 [Aspose.Slides](../../)