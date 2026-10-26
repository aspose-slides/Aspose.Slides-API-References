---
title: IChartParagraphFormat
second_title: Aspose.Slides C++ API 参考
description: 表示图表的段落格式属性。
type: docs
weight: 781
url: /zh/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat 类

表示图表的段落格式属性。

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | 返回段落中的文本对齐方式。阅读 [TextAlignment](../../aspose.slides/textalignment/)。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 返回默认制表大小。阅读 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 确定段落中是否使用东亚换行。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 返回段落中的字体对齐方式。阅读 [Slides::FontAlignment](../../aspose.slides/fontalignment/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 确定段落中是否使用悬挂标点。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_Indent](./get_indent/)() | 返回段落的首行缩进/悬挂缩进。悬挂缩进可以使用负值定义。阅读 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 确定段落中是否使用拉丁换行。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 返回段落的左边距。阅读 **float**。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 返回段落的右边距。阅读 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 确定段落中是否使用从右到左书写。阅读 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 返回段落最后一行之后的空间量。阅读 **float**。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 返回段落第一行之前的空间量。阅读 **float**。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 返回段落基线之间的空间量。阅读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 返回段落在指定索引处的制表符。只读 [Aspose::Slides::ITab](../../aspose.slides/itab/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | 返回段落的制表符。只读 [ITabCollection](../../aspose.slides/itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的情况，[Object::ReferenceEquals](../../system/object/referenceequals/) 的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的情况，[Object::ReferenceEquals](../../system/object/referenceequals/) 的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | 设置段落中的文本对齐方式。写入 [TextAlignment](../../aspose.slides/textalignment/)。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 设置默认制表大小。写入 **float**。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定段落中是否使用东亚换行。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | 设置段落中的字体对齐方式。写入 [Slides::FontAlignment](../../aspose.slides/fontalignment/)。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定段落中是否使用悬挂标点。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 设置段落的首行缩进/悬挂缩进。悬挂缩进可以使用负值定义。写入 **float**。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定段落中是否使用拉丁换行。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 设置段落的左边距。写入 **float**。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 设置段落的右边距。写入 **float**。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定段落中是否使用从右到左书写。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 设置段落最后一行之后的空间量。写入 **float**。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 设置段落第一行之前的空间量。写入 **float**。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 设置段落基线之间的空间量。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)