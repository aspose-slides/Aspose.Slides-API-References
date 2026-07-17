---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API 参考
description: 表示 DataLabel 的格式选项。
type: docs
weight: 391
url: /zh/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 类


表示 [DataLabel](../datalabel/) 的格式选项。

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使 IEC 60559:1989 中 NaN 不等于任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使 IEC 60559:1989 中 NaN 不等于任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回图表。只读 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 表示数据标签的格式。只读 [IFormat](../iformat/)。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 读取 **bool**。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | 表示 DataLabels 对象的格式字符串。读取 [System::String](../../system/string/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。只读 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | 表示数据标签的位置。读取 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | 设置或返回表示图表上数据标签分隔符的 Variant。读取 [System::String](../../system/string/)。 |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | 表示指定图表的数据标签气泡大小值显示行为。True 显示气泡大小值，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | 表示指定图表的数据标签类别名称显示行为。True 显示类别名称，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | 表示指定图表的数据标签单元格值显示行为。True 显示单元格值，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | 表示指定图表的数据标签引线显示行为。True 显示引线，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | 表示指定图表的数据标签图例键显示行为。True 表示图例键可见。读取 **bool**。 |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | 表示指定图表的数据标签百分比值显示行为。True 显示百分比值，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | 返回布尔值指示图表上数据标签的系列名称显示行为。True 显示系列名称，False 隐藏。读取 **bool**。 |
| **bool** [get_ShowValue](./get_showvalue/)() override | 表示指定图表的数据标签百分比值显示行为。True 显示百分比值，False 隐藏。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# ‘is’ 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 写入 **bool**。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | 表示 DataLabels 对象的格式字符串。写入 [System::String](../../system/string/)。 |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | 表示数据标签的位置。写入 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | 设置或返回表示图表上数据标签分隔符的 Variant。写入 [System::String](../../system/string/)。 |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | 表示指定图表的数据标签气泡大小值显示行为。True 显示气泡大小值，False 隐藏。写入 **bool**。 |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | 表示指定图表的数据标签类别名称显示行为。True 显示类别名称，False 隐藏。写入 **bool**。 |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | 表示指定图表的数据标签单元格值显示行为。True 显示单元格值，False 隐藏。写入 **bool**。 |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | 表示指定图表的数据标签引线显示行为。True 显示引线，False 隐藏。写入 **bool**。 |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | 表示指定图表的数据标签图例键显示行为。True 表示图例键可见。写入 **bool**。 |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | 表示指定图表的数据标签百分比值显示行为。True 显示百分比值，False 隐藏。写入 **bool**。 |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | 设置布尔值指示图表上数据标签的系列名称显示行为。True 显示系列名称，False 隐藏。写入 **bool**。 |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | 表示指定图表的数据标签百分比值显示行为。True 显示百分比值，False 隐藏。写入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 为第 n 个模板参数设置弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另请参阅

* Class [PVIObject](../../aspose.slides/pviobject/)
* Class [IDataLabelFormat](../idatalabelformat/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)