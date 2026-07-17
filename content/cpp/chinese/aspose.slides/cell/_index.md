---
title: Cell
second_title: Aspose.Slides for C++ API 参考
description: 表示表格中的一个单元格。
type: docs
weight: 300
url: /zh/aspose.slides/cell/
---
## Cell 类

表示表格中的一个单元格。

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | 确定文本框是否居中于单元格内部。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | 返回包含此单元格格式属性的 [CellFormat](../cellformat/) 对象。只读 [ICellFormat](../icellformat/)。 |
| **int32_t** [get_ColSpan](./get_colspan/)() override | 返回父表格网格中当前单元格跨越的网格列数。此属性使单元格看起来被合并，因为它跨越表中其他单元格的垂直边界。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | 获取单元格的第一列。只读 [IColumn](../icolumn/)。 |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | 返回单元格覆盖的第一列的索引。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | 获取单元格的第一行。只读 [IRow](../irow/)。 |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | 返回单元格覆盖的第一行的索引。只读 **int32_t**。 |
| **double** [get_Height](./get_height/)() override | 返回单元格的高度。只读 **double**。 |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | 如果单元格与任何已调整的单元格合并则返回 true，否则返回 false。只读 **bool**。 |
| **double** [get_MarginBottom](./get_marginbottom/)() override | 返回 [TextFrame](../textframe/) 中的底部边距。读取 **double**。 |
| **double** [get_MarginLeft](./get_marginleft/)() override | 返回 [TextFrame](../textframe/) 中的左侧边距。读取 **double**。 |
| **double** [get_MarginRight](./get_marginright/)() override | 返回 [TextFrame](../textframe/) 中的右侧边距。读取 **double**。 |
| **double** [get_MarginTop](./get_margintop/)() override | 返回 [TextFrame](../textframe/) 中的顶部边距。读取 **double**。 |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | 返回单元格的最小高度。这是单元格覆盖的所有行的最小高度之和。只读 **double**。 |
| **double** [get_OffsetX](./get_offsetx/)() override | 返回表左侧到单元格左侧的距离。只读 **double**。 |
| **double** [get_OffsetY](./get_offsety/)() override | 返回表顶部到单元格顶部的距离。只读 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | 返回单元格的父演示文稿。只读 [IPresentation](../ipresentation/)。 |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | 返回合并单元格跨越的行数。此属性与其他单元格的 vMerge 属性结合使用，以指定水平合并的起始单元格。只读 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | 返回单元格的父幻灯片。只读 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | 返回单元格的父 [Table](../table/) 对象。只读 [ITable](../itable/)。 |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | 返回文本锚点类型。读取 [Slides::TextAnchorType](../textanchortype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | 返回单元格的文本框架。只读 [ITextFrame](../itextframe/)。 |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 返回垂直文本的类型。读取 [Slides::TextVerticalType](../textverticaltype/)。 |
| **double** [get_Width](./get_width/)() override | 返回单元格的宽度。只读 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | 确定文本框是否居中于单元格内部。写入 **bool**。 |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | 设置 [TextFrame](../textframe/) 中的底部边距。写入 **double**。 |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | 设置 [TextFrame](../textframe/) 中的左侧边距。写入 **double**。 |
| void [set_MarginRight](./set_marginright/)(**double**) override | 设置 [TextFrame](../textframe/) 中的右侧边距。写入 **double**。 |
| void [set_MarginTop](./set_margintop/)(**double**) override | 设置 [TextFrame](../textframe/) 中的顶部边距。写入 **double**。 |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | 设置文本锚点类型。写入 [Slides::TextAnchorType](../textanchortype/)。 |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 设置垂直文本的类型。写入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | 按列索引将单元格拆分为两个单元格。 |
| void [SplitByHeight](./splitbyheight/)(**double**) override | 按高度拆分单元格。 |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | 按行索引将单元格拆分为两个单元格。 |
| void [SplitByWidth](./splitbywidth/)(**double**) override | 按宽度拆分单元格。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [IDOMObject](../idomobject/)
* 类 [ICell](../icell/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)