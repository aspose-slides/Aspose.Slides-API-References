---
title: Table
second_title: Aspose.Slides C++ API 参考
description: 表示幻灯片上的表格。
type: docs
weight: 5409
url: /zh/aspose.slides/table/
---
## Table 类

表示幻灯片上的表格。

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## 方法

| Method | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 如果不存在，则添加一个新的占位符并将占位符属性设置为指定的占位符。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 返回与形状关联的替代文本。阅读 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 返回与形状关联的替代文本标题。阅读 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 属性指定形状在黑白显示模式下的渲染方式。阅读 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | 返回指定索引处的列。只读 [Aspose::Slides::IColumn](../icolumn/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | 返回列的集合。只读 [IColumnCollection](../icolumncollection/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 返回形状上的连接点数量。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 返回形状的自定义数据。只读 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 返回包含应用于形状的像素效果的 [EffectFormat](../effectformat/) 对象。注意：对于某些不具有效果属性的形状类型，可能返回 null。只读 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 返回包含 [Table](./) 填充格式的 [TableFormat::get_FillFormat](../tableformat/get_fillformat/) 对象。只读 [IFillFormat](../ifillformat/)。 |
| **bool** [get_FirstCol](./get_firstcol/)() override | 确定表格的第一列是否需要使用特殊格式绘制。读取 **bool**。 |
| **bool** [get_FirstRow](./get_firstrow/)() override | 确定表格的第一行是否需要使用特殊格式绘制。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 返回形状框架的属性。阅读 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | 返回形状的锁。只读 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | 获取形状的高度，单位为点。读取 **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 确定形状是否隐藏。读取 **bool**。 |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | 确定偶数行是否需要使用不同的格式绘制。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 返回为鼠标点击定义的超链接。阅读 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 返回超链接管理器。只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 返回为鼠标悬停定义的超链接。阅读 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 获取 “标记为装饰性” 选项 读/写 **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 确定形状是否被分组。只读 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 确定形状是否为 TextHolder_PPT。只读 **bool**。 |
| **bool** [get_LastCol](./get_lastcol/)() override | 确定表格的最后一列是否需要使用特殊格式绘制。读取 **bool**。 |
| **bool** [get_LastRow](./get_lastrow/)() override | 确定表格的最后一行是否需要使用特殊格式绘制。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 返回包含形状线条格式属性的 [LineFormat](../lineformat/) 对象。注意：对于某些不具备线属性的形状类型，可能返回 null。只读 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 返回形状的名称。必须不为 null。如果需要，可使用空字符串值。阅读 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 返回一个在幻灯片范围内唯一的标识符，在形状生命周期内保持不变，允许 PowerPoint 或互操作代码从文档任何位置可靠地引用该形状。只读 **uint32_t**。另请参见 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 如果形状被分组，返回父级 [GroupShape](../groupshape/) 对象。否则返回 null。只读 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 返回幻灯片的父级演示文稿。只读 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 返回原始形状框架的属性。阅读 [IShapeFrame](../ishapeframe/)。 |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | 确定表格是否采用从右到左的阅读顺序。读取 **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 返回指定形状围绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | 返回指定索引处的行。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | 返回行的集合。只读 [IRowCollection](../irowcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 返回形状的锁。只读 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 返回形状的父幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | 获取内置表格样式。阅读 [TableStylePreset](../tablestylepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | 返回包含此表格格式属性的 [TableFormat](../tableformat/) 对象。只读 [ITableFormat](../itableformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 返回包含形状 3D 效果属性的 [ThreeDFormat](../threedformat/) 对象。注意：对于某些不具备 3D 属性的形状类型，可能返回 null。只读 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 返回内部的、演示文稿范围的标识符，供插件或其他代码使用。由于该值可能被用户或程序重新分配，不能视为持久唯一键。只读 **uint32_t**。另请参见 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | 确定偶数列是否需要使用不同的格式绘制。读取 **bool**。 |
| **float** [get_Width](../shape/get_width/)() override | 获取形状的宽度，单位为点。读取 **float**。 |
| **float** [get_X](../shape/get_x/)() override | 获取形状左上角的 x 坐标，单位为点。读取 **float**。 |
| **float** [get_Y](../shape/get_y/)() override | 获取形状左上角的 y 坐标，单位为点。读取 **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | 返回形状在 z 顺序中的位置。Shapes[0] 返回位于 z 顺序后方的形状，Shapes[Shapes.Count - 1] 返回位于前方的形状。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 返回基本占位符形状（来自布局和/或母版幻灯片，当前形状继承自该形状）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 返回形状缩略图。默认使用 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 形状缩略图边界类型。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 返回形状缩略图。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 获取根据渲染内容计算的形状可视边界。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | 返回指定列和行索引处的单元格。只读 [Cell](../cell/)。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | 合并相邻单元格。 |
|   [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 定义此形状不是占位符。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本。写入 [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 设置与形状关联的替代文本标题。写入 [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 属性指定形状在黑白显示模式下的渲染方式。写入 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | 确定表格的第一列是否需要使用特殊格式绘制。写入 **bool**。 |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | 确定表格的第一行是否需要使用特殊格式绘制。写入 **bool**。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | 设置形状的高度，单位为点。写入 **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 确定形状是否隐藏。写入 **bool**。 |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | 确定偶数行是否需要使用不同的格式绘制。写入 **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置为鼠标点击定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置为鼠标悬停定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 设置 “标记为装饰性” 选项 读/写 **bool**。 |
| void [set_LastCol](./set_lastcol/)(**bool**) override | 确定表格的最后一列是否需要使用特殊格式绘制。写入 **bool**。 |
| void [set_LastRow](./set_lastrow/)(**bool**) override | 确定表格的最后一行是否需要使用特殊格式绘制。写入 **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 设置形状的名称。必须不为 null。如果需要，可使用空字符串值。写入 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 设置原始形状框架的属性。写入 [IShapeFrame](../ishapeframe/)。 |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | 确定表格是否采用从右到左的阅读顺序。写入 **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 设置指定形状围绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。写入 **float**。 |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | 设置内置表格样式。写入 [TableStylePreset](../tablestylepreset/)。 |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | 确定偶数列是否需要使用不同的格式绘制。写入 **bool**。 |
| void [set_Width](../shape/set_width/)(**float**) override | 设置形状的宽度，单位为点。写入 **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | 设置形状左上角的 x 坐标，单位为点。写入 **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | 设置形状左上角的 y 坐标，单位为点。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | 将定义的部分格式属性设置到所有表格单元格的部分。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | 将定义的段落格式属性设置到所有表格单元格的段落。 |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | 将定义的文本框格式属性设置到所有表格单元格的文本框。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | 将 [Shape](../shape/) 内容保存为 SVG 文件。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [GraphicalObject](../graphicalobject/)
* 类 [ITable](../itable/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)