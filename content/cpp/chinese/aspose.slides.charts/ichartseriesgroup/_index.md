---
title: IChartSeriesGroup
second_title: Aspose.Slides C++ API 参考
description: 表示系列的组。
type: docs
weight: 846
url: /zh/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 类

表示系列的组。

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比较对象，使用 C# [Object.Equals](../../system/object/equals/) 语义。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 指定在气泡图中气泡大小值的表示方式。读取 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。读取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 返回组中指定索引处的图表系列。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 指定环形图中孔的大小（可以在绘图区域大小的 10% 到 90% 之间）。读取 **uint8_t**。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 获取第一个饼图或环形图切片的角度，以度数表示（从上方顺时针，0 到 360 度）。读取 **uint16_t**。 |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 返回 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读取 **uint16_t**。 |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。读取 **uint16_t**。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 如果图表具有系列线则为 true。适用于堆叠条形图和 OfPie 图表。读取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | 指定 HiLowLines 格式。HiLowLines 与 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型一起使用。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 指定系列中的每个数据标记具有不同的颜色。读取 **bool**。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 指定条形和柱形在二维图表上的重叠程度，以百分比表示（从 -100% 到 100%）。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | 指定如何确定哪些数据点位于饼中饼或条形中条的第二个饼或条中。读取 [PieSplitType](../piesplittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 自定义拆分信息用于具有自定义拆分的饼中饼或条形中条图表。返回应按索引绘制在第二个饼或条中的数据点。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 自定义拆分信息用于具有自定义拆分的饼中饼或条形中条图表。包含应在第二个饼或条中绘制的数据点。只读 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 指定用于确定哪些数据点位于饼中饼或条形中条的第二个饼或条的值。与 PieSplitBy 属性一起使用。读取 **double**。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 指示此组的系列是否绘制在次坐标轴上。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 指定饼中饼图或条形中条图的第二个饼或条的大小，以第一个饼的大小百分比表示（可以在 5% 到 200% 之间）。读取 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | 返回图表系列的只读集合。只读 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | 返回此系列组的类型。只读 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | 提供对折线图或股票图的上/下柱的访问。只读 [IUpDownBarsManager](../iupdownbarsmanager/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | 获取指定索引处的元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 对 string 和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | 指定在气泡图中气泡大小值的表示方式。写入 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)。 |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。写入 **int32_t**。 |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | 指定环形图中孔的大小（可以在绘图区域大小的 10% 到 90% 之间）。写入 **uint8_t**。 |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | 设置第一个饼图或环形图切片的角度（从上方顺时针，0 到 360 度）。写入 **uint16_t**。 |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。写入 **uint16_t**。 |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。写入 **uint16_t**。 |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | 如果图表具有系列线则为 true。适用于堆叠条形图和 OfPie 图表。写入 **bool**。 |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | 指定系列中的每个数据标记具有不同的颜色。写入 **bool**。 |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 指定条形和柱形在二维图表上的重叠程度，以百分比表示（从 -100% 到 100%）。 |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | 指定如何确定哪些数据点位于饼中饼或条形中条的第二个饼或条中。写入 [PieSplitType](../piesplittype/)。 |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | 指定用于确定哪些数据点位于饼中饼或条形中条的第二个饼或条的值。与 PieSplitBy 属性一起使用。写入 **double**。 |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | 指定饼中饼或条形中条图的第二个饼或条的大小，以第一个饼的大小百分比表示（可以在 5% 到 200% 之间）。写入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。2) 系列组包含一些对组中每个系列都通用的系列属性（“系列组属性”）。[ChartSeriesGroup](../chartseriesgroup/) 类中的“系列组属性”是读写的。每个“系列组属性”在 [ChartSeries](../chartseries/) 类中可以有只读的投影。

## 参见

* 类 [IChartComponent](../ichartcomponent/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)