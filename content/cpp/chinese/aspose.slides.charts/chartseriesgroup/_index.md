---
title: ChartSeriesGroup
second_title: Aspose.Slides C++ API 参考
description: 表示系列的组。
type: docs
weight: 300
url: /zh/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 类


Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C#-style 的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C#-style 的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 指定在气泡图上气泡大小值的表示方式。读取 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。读取 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父图表。只读 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | 返回组中指定索引处的图表系列。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 指定环形图中孔的大小（可以在绘图区域大小的 0% 到 90% 之间）。读取 **uint8_t**。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 获取第一个饼图或环形图切片的角度，单位为度（从上方顺时针，从 0 到 360 度）。读取 **uint16_t**。 |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 返回在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读取 **uint16_t**。 |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。读取 **uint16_t**。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 如果图表具有系列线则为 true。适用于堆叠条形图和 OfPie 图表。读取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | 指定 HiLowLines 格式。HiLowLines 与 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型一起使用。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 指定系列中的每个数据标记具有不同的颜色。读取 **bool**。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或柱中包含哪些数据点。读取 [PieSplitType](../piesplittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 自定义拆分信息用于具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表。返回按索引应在第二个饼或柱中绘制的数据点。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 自定义拆分信息用于具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表。包含应在第二个饼或柱中绘制的数据点。只读 [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或柱中包含哪些数据点的值。与 PieSplitBy 属性一起使用。读取 **double**。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 指示此组的系列是否绘制在次坐标轴上。只读 **bool**。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | 指定 pie-of-pie 图表或 bar-of-pie 图表的第二个饼或柱的大小，以第一个饼的大小百分比表示（可以在 5% 到 200% 之间）。读取 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | 返回系列集合。只读 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | 返回此系列组的类型。只读 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | 提供对折线图或股票图的上/下柱的访问。只读 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | 获取指定索引处的元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | 指定在气泡图上气泡大小值的表示方式。写入 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。写入 **int32_t**。 |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | 指定环形图中孔的大小（可以在绘图区域大小的 0% 到 90% 之间）。写入 **uint8_t**。 |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | 设置第一个饼图或环形图切片的角度，单位为度（从上方顺时针，从 0 到 360 度）。写入 **uint16_t**。 |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。写入 **uint16_t**。 |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。写入 **uint16_t**。 |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | 如果图表具有系列线则为 true。适用于堆叠条形图和 OfPie 图表。写入 **bool**。 |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | 指定系列中的每个数据标记具有不同的颜色。写入 **bool**。 |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。 |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或柱中包含哪些数据点。写入 [PieSplitType](../piesplittype/)。 |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或柱中包含哪些数据点的值。与 PieSplitBy 属性一起使用。写入 **double**。 |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | 指定 pie-of-pie 图表或 bar-of-pie 图表的第二个饼或柱的大小，以第一个饼的大小百分比表示（可以在 5% 到 200% 之间）。写入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

1) 请参阅 ChartSeriesGroupCollection 类的摘要和备注，以及 CombinableSeriesTypesGroup 枚举。2) 系列组包含一些对组中每个系列共同的系列属性（“series group properties”）。在 [ChartSeriesGroup](./) 类中，“series group properties” 为读写。在 [ChartSeries](../chartseries/) 类中，每个 “series group properties” 可以有只读的投影。

## 另见

* 类 [IChartSeriesGroup](../ichartseriesgroup/)
* 类 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)