---
title: Trendline
second_title: Aspose.Slides for C++ API 参考
description: 类表示图表系列的趋势线
type: docs
weight: 1366
url: /zh/aspose.slides.charts/trendline/
---
## 趋势线 类

类表示图表系列的趋势线

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 使用参数 “text” 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **double** [get_Backward](./get_backward/)() override | 指定趋势线在所趋势系列的数据之前延伸的分类数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父图表。只读 [IChart](../ichart/)。 |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | 指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。读取 **bool**。 |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | 指定在图表上显示趋势线的 R 平方值（与方程同一标签）。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 表示趋势线的格式。读取 [IFormat](../iformat/)。 |
| **double** [get_Forward](./get_forward/)() override | 指定趋势线在所趋势系列的数据之后延伸的分类数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读取 **double**。 |
| **double** [get_Intercept](./get_intercept/)() override | 指定趋势线与 y 轴相交的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读取 **double**。 |
| **uint8_t** [get_Order](./get_order/)() override | 指定多项式趋势线的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。读取 **uint8_t**。 |
| **uint8_t** [get_Period](./get_period/)() override | 指定移动平均趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。读取 **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 表示与此趋势线相关的图例条目。只读 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 返回文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 可以包含富格式文本。如果此属性不为 null，则此格式化文本值会覆盖数据标签的自动生成文本。数据标签的自动生成文本是指由 ShowSeriesName、ShowValue 等属性管理且使用 TextFormatManager.TextFormat 属性格式化的文本。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | 获取趋势线的名称。读取 [System::String](../../system/string/)。 |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | 获取趋势线的类型。读取 [Charts::TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价物。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。C# [System.Object.GetType()](../../system/object/gettype/) 调用的等价物。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型描述的实例。C# ‘is’ 操作符的等价物。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价物。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用 nullptr 对值类型对象进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Backward](./set_backward/)(**double**) override | 指定趋势线在所趋势系列的数据之前延伸的分类数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。写入 **double**。 |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | 指定在图表上显示趋势线的方程（与 Rsquaredvalue 同一标签）。写入 **bool**。 |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | 指定在图表上显示趋势线的 R 平方值（与方程同一标签）。写入 **bool**。 |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | 表示趋势线的格式。写入 [IFormat](../iformat/)。 |
| void [set_Forward](./set_forward/)(**double**) override | 指定趋势线在所趋势系列的数据之后延伸的分类数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。写入 **double**。 |
| void [set_Intercept](./set_intercept/)(**double**) override | 指定趋势线与 y 轴相交的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。写入 **double**。 |
| void [set_Order](./set_order/)(**uint8_t**) override | 指定多项式趋势线的阶数。对其他趋势线类型忽略。值必须在 2 到 6 之间。写入 **uint8_t**。 |
| void [set_Period](./set_period/)(**uint8_t**) override | 指定移动平均趋势线的周期。对其他趋势线变体忽略。值必须在 2 到 255 之间。写入 **uint8_t**。 |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | 设置趋势线的名称。写入 [System::String](../../system/string/)。 |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | 设置趋势线的类型。写入 [Charts::TrendlineType](../trendlinetype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价物。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [DomObject](../../aspose.slides/domobject/)
* 类 [ITrendline](../itrendline/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)