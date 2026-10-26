---
title: ICell
second_title: Aspose.Slides for C++ API 参考
description: 表示表格中的单元格。
type: docs
weight: 1639
url: /zh/aspose.slides/icell/
---
## ICell 类

表示表格中的单元格。

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | 确定文本框是否居中于单元格内。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | 返回 [CellFormat](../cellformat/) 对象，包含此单元格的格式属性。只读 [ICellFormat](../icellformat/)。 |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | 返回父表格的表格网格中当前单元格将跨越的列数。此属性使单元格看起来像已合并，因为它们跨越表格中其他单元格的垂直边界。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | 获取单元格的第一列。只读 [IColumn](../icolumn/)。 |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | 返回单元格覆盖的第一列的索引。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | 获取单元格的第一行。只读 [IRow](../irow/)。 |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | 返回单元格覆盖的第一行的索引。只读 **int32_t**。 |
| virtual **double** [get_Height](./get_height/)() | 返回单元格的高度。只读 **double**。 |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | 如果单元格与任何已调整的单元格合并则返回 true，否则返回 false。只读 **bool**。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 返回 [TextFrame](../textframe/) 中的底部边距。读取 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 返回 [TextFrame](../textframe/) 中的左侧边距。读取 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 返回 [TextFrame](../textframe/) 中的右侧边距。读取 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 返回 [TextFrame](../textframe/) 中的顶部边距。读取 **double**。 |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | 返回单元格的最小高度。这是所有被单元格覆盖的行的最小高度之和。只读 **double**。 |
| virtual **double** [get_OffsetX](./get_offsetx/)() | 返回表格左侧到单元格左侧的距离。只读 **double**。 |
| virtual **double** [get_OffsetY](./get_offsety/)() | 返回表格顶部到单元格顶部的距离。只读 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../ipresentation/)。 |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | 返回合并单元格跨越的行数。此属性与其他单元格的 vMerge 属性结合使用，以指定水平合并的起始单元格。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | 返回单元格的父级 [Table](../table/) 对象。只读 [ITable](../itable/)。 |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | 返回文本锚点类型。读取 [Slides::TextAnchorType](../textanchortype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | 返回单元格的文本框架。只读 [ITextFrame](../itextframe/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 返回垂直文本的类型。读取 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual **double** [get_Width](./get_width/)() | 返回单元格的宽度。只读 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类似实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类似实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | 确定文本框是否居中于单元格内。写入 **bool**。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 设置 [TextFrame](../textframe/) 中的底部边距。写入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 设置 [TextFrame](../textframe/) 中的左侧边距。写入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 设置 [TextFrame](../textframe/) 中的右侧边距。写入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 设置 [TextFrame](../textframe/) 中的顶部边距。写入 **double**。 |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | 设置文本锚点类型。写入 [Slides::TextAnchorType](../textanchortype/)。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 设置垂直文本的类型。写入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | 按列索引将单元格拆分为两个单元格。 |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | 按高度拆分单元格。 |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | 按行索引将单元格拆分为两个单元格。 |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | 按宽度拆分单元格。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [ISlideComponent](../islidecomponent/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)