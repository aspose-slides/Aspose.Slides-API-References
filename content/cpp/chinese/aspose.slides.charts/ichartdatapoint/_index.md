---
title: IChartDataPoint
second_title: Aspose.Slides for C++ API 参考
description: 表示系列数据点。
type: docs
weight: 677
url: /zh/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 类

表示系列数据点。

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C#-style 浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C#-style 浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定图表元素的实际高度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定图表元素的实际宽度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定图表元素相对于图表左上角的实际 x 位置（左）。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定图表元素相对于图表左上角的实际顶部位置。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | 返回图表数据点的气泡大小。只读 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | 返回图表数据点的颜色值。用于 Map 图表。只读 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | 返回指定索引处的数据点级别。用于 Treeamp 和 Sunburst 系列。数据点级别索引从零开始。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | 返回数据点级别的容器。用于 Treeamp 和 Sunburst 系列。数据点级别索引从零开始。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | 表示自定义值类型情况下的系列误差栏值。只读 [IErrorBarsCustomValues](../ierrorbarscustomvalues/)。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 指定数据点应从饼图中心移动的距离。读取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 表示格式属性。读取 [IFormat](../iformat/)。 |
| virtual **uint32_t** [get_Index](./get_index/)() | 确定此数据点适用于父级子集合中的哪一个。读取 **uint32_t**。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 指定如果值为负数，数据点应反转其颜色。读取 **bool**。 |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | 指定气泡具有 3-D 效果。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | 表示图表数据点的标签。只读 [IDataLabel](../idatalabel/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | 指定数据标记。只读 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 对应图例条目的属性，适用于以下图表类型：[ChartType::BarOfPie](../charttype/)、[ChartType::ExplodedPie](../charttype/)、[ChartType::ExplodedPie3D](../charttype/)、[ChartType::Pie](../charttype/)、[ChartType::Pie3D](../charttype/)、[ChartType::PieOfPie](../charttype/)。只读 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | 将数据点设置为总计。仅适用于 Waterfall 系列类型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | 返回图表数据点的大小值。用于 Treemap 和 Sunburst 图表。只读 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | 返回图表数据点的值。只读 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | 返回图表数据点的 x 值。只读 [IStringOrDoubleChartValue](../istringordoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | 返回图表数据点的 y 值。只读 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。类似于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。类似于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 类似于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 对值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 strings 的情况。 |
| virtual void [Remove](./remove/)() | 从图表系列中移除 DataPoint。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 指定数据点应从饼图中心移动的距离。写入 **int32_t**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 表示格式属性。写入 [IFormat](../iformat/)。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 指定如果值为负数，数据点应反转其颜色。写入 **bool**。 |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | 指定气泡具有 3-D 效果。写入 **bool**。 |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | 将数据点设置为总计。仅适用于 Waterfall 系列类型。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 类似于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IActualLayout](../iactuallayout/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)