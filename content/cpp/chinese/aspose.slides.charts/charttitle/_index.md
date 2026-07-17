---
title: ChartTitle
second_title: Aspose.Slides for C++ API 参考
description: 表示图表标题属性。
type: docs
weight: 326
url: /zh/aspose.slides.charts/charttitle/
---
## ChartTitle 类

Represents chart title properties.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## 方法

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 使用参数 \"text\" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，但两个 NaN 被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，但两个 NaN 被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定图表元素的实际高度。在获取实际值之前调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。读取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定图表元素的实际宽度。在获取实际值之前调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。读取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定图表元素相对于图表左上角的实际 x 位置（左）。在获取实际值之前调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。读取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。读取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。只读 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父图表。只读 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 返回标题的填充、线条、效果样式。只读 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 返回标题高度占图表高度的比例。读取 **float**。 |
| **bool** [get_Overlay](./get_overlay/)() override | 确定是否允许其他图表元素覆盖标题。读取 **bool**。 |
| **float** [get_Right](./get_right/)() override | 右侧。只读 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 返回文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、值轴显示单位标签、轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 属性进行格式化。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| **float** [get_Width](./get_width/)() override | 返回标题宽度占图表宽度的比例。读取 **float**。 |
| **float** [get_X](./get_x/)() override | 返回标题 x 坐标占图表宽度的比例。读取 **float**。 |
| **float** [get_Y](./get_y/)() override | 返回标题 y 坐标占图表高度的比例。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数降低指定值。 |
| void [set_Height](./set_height/)(**float**) override | 设置标题高度占图表高度的比例。写入 **float**。 |
| void [set_Overlay](./set_overlay/)(**bool**) override | 确定是否允许其他图表元素覆盖标题。写入 **bool**。 |
| void [set_Width](./set_width/)(**float**) override | 设置标题宽度占图表宽度的比例。写入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 设置标题 x 坐标占图表宽度的比例。写入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 设置标题 y 坐标占图表高度的比例。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [IChartTitle](../icharttitle/)
* 类 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)