---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API 参考
description: 表示绘制图表的矩形。
type: docs
weight: 248
url: /zh/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea 类

表示绘制图表的矩形。

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C#-style 浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C#-style 浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定图表元素的实际高度。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定图表元素的实际宽度。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定图表元素相对于图表左上角的实际 x 位置（左）。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定图表元素相对于图表左上角的实际顶部位置。请先调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。只读 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). 只读 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 返回绘图区域的格式。只读 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 返回绘图区域边界框的高度，作为图表高度的比例（0 到 1）。读取 **float**。 |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | 定义位置应如何计算：true \\u2013 自动计算；由 X、Y、Width、Height 属性定义。只读 **bool**。 |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | 如果绘图区域布局手动定义，则此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。读取 [LayoutTargetType](../layouttargettype/)。 |
| **float** [get_Right](./get_right/)() override | 右侧。只读 **float**。 |
| **float** [get_Width](./get_width/)() override | 返回绘图区域边界框的宽度，作为图表宽度的比例（0 到 1）。读取 **float**。 |
| **float** [get_X](./get_x/)() override | 返回绘图区域边界框左上角的 x 坐标，作为图表宽度的比例（0 到 1）。读取 **float**。 |
| **float** [get_Y](./get_y/)() override | 返回绘图区域边界框左上角的 y 坐标，作为图表高度的比例（0 到 1）。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上并不复制任何内容，只是初始化新对象并允许子类进行拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并允许子类进行拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Height](./set_height/)(**float**) override | 设置绘图区域边界框的高度，作为图表高度的比例（0 到 1）。写入 **float**。 |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | 如果绘图区域布局手动定义，则此属性指定是按内部布局（不包括坐标轴和坐标轴标签）还是按外部布局（包括坐标轴和坐标轴标签）。写入 [LayoutTargetType](../layouttargettype/)。 |
| void [set_Width](./set_width/)(**float**) override | 设置绘图区域边界框的宽度，作为图表宽度的比例（0 到 1）。写入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 设置绘图区域边界框左上角的 x 坐标，作为图表宽度的比例（0 到 1）。写入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 设置绘图区域边界框左上角的 y 坐标，作为图表高度的比例（0 到 1）。写入 **float**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [DomObject](../../aspose.slides/domobject/)
* 类 [IChartPlotArea](../ichartplotarea/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)