---
title: IChartData
second_title: Aspose.Slides C++ API 参考
description: 表示用于图表绘制的数据。
type: docs
weight: 651
url: /zh/aspose.slides.charts/ichartdata/
---
## IChartData 类

表示用于图表绘制的数据。

```cpp
class IChartData : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | 获取主类别（如果 [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) 设置为 false，则获取主类别和次要类别）。只读 [IChartCategoryCollection](../ichartcategorycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | 返回指定索引处的主类别。如果 [get_UseSecondaryCategories](./get_usesecondarycategories/) 为 false，则在所有类别中获取。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | 获取用于创建图表系列或类别的单元格的工厂。只读 [IChartDataWorkbook](../ichartdataworkbook/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 返回指定索引处的系列。 |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | 表示图表的数据源。 |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | 获取嵌入工作簿的类型。如果 [IChartData::get_DataSourceType](./get_datasourcetype/) 为 [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/)，则返回 [WorkbookType::NotDefined](../workbooktype/)。只读 [WorkbookType](../workbooktype/)。 |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | 如果数据源是外部的，则表示外部工作簿路径；否则为 null。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | 如果 [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) 为 true，则获取次要类别。只读 [IChartCategoryCollection](../ichartcategorycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | 返回指定索引处的次要类别。如果 [get_UseSecondaryCategories](./get_usesecondarycategories/) 为 false，则 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 为 null。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | 获取系列。只读 [IChartSeriesCollection](../ichartseriescollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | 返回指定索引处的系列组。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | 获取系列组。只读 [IChartSeriesGroupCollection](../ichartseriesgroupcollection/)。 |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | 如果设置为 false，则 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 返回 null，[IChartData::get_Categories](./get_categories/) 中的数据同时用于主系列和次要系列。如果设置为 true，则 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 中的数据用于次要系列，[IChartData::get_Categories](./get_categories/) 中的数据用于主系列。读取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | 获取图表数据范围。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的拷贝构造。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | 将内部包含的 [Excel](../../aspose.slides.excel/) 工作簿写入内存流中。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 按引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | 如果设置为 false，则 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 返回 null，[IChartData::get_Categories](./get_categories/) 中的数据同时用于主系列和次要系列。如果设置为 true，则 [IChartData::get_SecondaryCategories](./get_secondarycategories/) 中的数据用于次要系列，[IChartData::get_Categories](./get_categories/) 中的数据用于主系列。写入 **bool**。 |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | 将外部工作簿设置为图表的数据源。[Chart](../chart/) 数据将从目标工作簿更新。 |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | 将外部工作簿设置为图表的数据源。 |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | 设置图表数据范围。系列和类别将根据新的数据范围进行更新。如果数据范围中的系列数量大于图表数据中的系列数量，则会在集合末尾添加与当前集合中最后一个系列相同类型的额外系列。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | 交换轴上的数据。X 轴上的数据将移动到 Y 轴，反之亦然。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | 使用用户指定的值初始化内部包含的 [Excel](../../aspose.slides.excel/) 工作簿。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参阅

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)