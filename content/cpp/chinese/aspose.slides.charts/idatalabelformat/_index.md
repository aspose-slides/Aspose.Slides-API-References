---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API 参考
description: 表示 DataLabel 的格式选项。
type: docs
weight: 963
url: /zh/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat 类

表示 [DataLabel](../datalabel/) 的格式选项。

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 表示数据标签的格式。只读 [IFormat](../iformat/)。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 读取 **bool**。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | 表示 DataLabels 对象的格式字符串。读取 [System::String](../../system/string/)。 |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | 表示数据标签的位置。读取 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | 设置或返回表示图表上数据标签使用的分隔符的 Variant。读取 [System::String](../../system/string/)。 |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | 表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | 表示指定图表的数据标签类别名称的显示行为。True 表示在图表上显示类别名称，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | 表示指定图表的数据标签单元格值的显示行为。True 表示显示单元格值，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | 表示指定图表的数据标签引导线的显示行为。True 表示显示引导线，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | 表示指定图表的数据标签图例键的显示行为。True 表示图例键可见。读取 **bool**。 |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | 表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | 返回一个布尔值，指示图表上数据标签的系列名称显示行为。True 表示显示系列名称，False 表示隐藏。读取 **bool**。 |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | 表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 写入 **bool**。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | 表示 DataLabels 对象的格式字符串。写入 [System::String](../../system/string/)。 |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | 表示数据标签的位置。写入 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。写入 [System::String](../../system/string/)。 |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | 表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | 表示指定图表的数据标签类别名称的显示行为。True 表示在图表上显示类别名称，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | 表示指定图表的数据标签单元格值的显示行为。True 表示显示单元格值，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | 表示指定图表的数据标签引导线的显示行为。True 表示显示引导线，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | 表示指定图表的数据标签图例键的显示行为。True 表示图例键可见。写入 **bool**。 |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | 表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | 设置一个布尔值，指示图表上数据标签的系列名称显示行为。True 表示显示系列名称，False 表示隐藏。写入 **bool**。 |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | 表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。写入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IFormattedTextContainer](../iformattedtextcontainer/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)