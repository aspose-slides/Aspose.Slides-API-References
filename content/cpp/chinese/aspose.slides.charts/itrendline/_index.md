---
title: ITrendline
second_title: Aspose.Slides for C++ API 参考
description: 类表示图表系列的趋势线
type: docs
weight: 1223
url: /zh/aspose.slides.charts/itrendline/
---
## ITrendline 类

类表示图表系列的趋势线。

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用参数 \"text\" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **double** [get_Backward](./get_backward/)() | 指定趋势线在系列数据之前延伸的分类数量（或散点图上的单位）。在散点图和非散点图中，该值必须为非负值。读取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | 指定在图表上显示趋势线方程（与 Rsquaredvalue 在同一标签中）。读取 **bool**。 |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | 指定在图表上显示趋势线的 R 平方值（与方程在同一标签中）。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 表示趋势线的格式。读取 [IFormat](../iformat/)。 |
| virtual **double** [get_Forward](./get_forward/)() | 指定趋势线在系列数据之后延伸的分类数量（或散点图上的单位）。在散点图和非散点图中，该值必须为非负值。读取 **double**。 |
| virtual **double** [get_Intercept](./get_intercept/)() | 指定趋势线与 y 轴相交的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读取 **double**。 |
| virtual **uint8_t** [get_Order](./get_order/)() | 指定多项式趋势线的阶数。对其他趋势线类型此属性被忽略。值必须在 2 到 6 之间。读取 **uint8_t**。 |
| virtual **uint8_t** [get_Period](./get_period/)() | 指定移动平均趋势线的周期。对其他趋势线变体此属性被忽略。值必须在 2 到 255 之间。读取 **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 表示与此趋势线相关的图例条目。只读 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文字格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可以包含富格式文本。如果此属性不为 null，则此格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、数值轴的显示单位标签、坐标轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 属性进行格式化。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | 获取趋势线的名称。读取 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | 获取趋势线的类型。读取 [TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Backward](./set_backward/)(**double**) | 指定趋势线在系列数据之前延伸的分类数量（或散点图上的单位）。在散点图和非散点图中，该值必须为非负值。写入 **double**。 |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | 指定在图表上显示趋势线方程（与 Rsquaredvalue 在同一标签中）。写入 **bool**。 |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | 指定在图表上显示趋势线的 R 平方值（与方程在同一标签中）。写入 **bool**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 表示趋势线的格式。写入 [IFormat](../iformat/)。 |
| virtual void [set_Forward](./set_forward/)(**double**) | 指定趋势线在系列数据之后延伸的分类数量（或散点图上的单位）。在散点图和非散点图中，该值必须为非负值。写入 **double**。 |
| virtual void [set_Intercept](./set_intercept/)(**double**) | 指定趋势线与 y 轴相交的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。写入 **double**。 |
| virtual void [set_Order](./set_order/)(**uint8_t**) | 指定多项式趋势线的阶数。对其他趋势线类型此属性被忽略。值必须在 2 到 6 之间。写入 **uint8_t**。 |
| virtual void [set_Period](./set_period/)(**uint8_t**) | 指定移动平均趋势线的周期。对其他趋势线变体此属性被忽略。值必须在 2 到 255 之间。写入 **uint8_t**。 |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | 设置趋势线的名称。写入 [System::String](../../system/string/)。 |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | 设置趋势线的类型。写入 [TrendlineType](../trendlinetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [IOverridableText](../ioverridabletext/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)