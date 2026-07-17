---
title: IChartDataCell
second_title: Aspose.Slides for C++ API 参考
description: 表示图表数据的单元格。
type: docs
weight: 664
url: /zh/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell 类

表示图表数据的单元格。

```cpp
class IChartDataCell : public virtual System::Object
```

## 方法

| 方法 | 说明 |
| --- | --- |
| virtual void [Calculate](./calculate/)(**bool**) | 如果单元格包含公式，值将根据该公式进行更新。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里仍将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），这里仍将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() | 获取工作表。只读 [IChartDataWorksheet](../ichartdataworksheet/)。 |
| virtual **int32_t** [get_Column](./get_column/)() | 返回单元格所在工作表列的索引。只读 **int32_t**。 |
| virtual [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() | 获取数字和日期的自定义显示格式。如果值为空，将使用 PresetNumberFormat 值。只读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | 获取 A1 样式的公式。 |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | 确定单元格是否隐藏。只读 **bool**。 |
| virtual **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() | 获取数字和日期的内置显示格式。预设编号必须在 [0..22] 或 [37..49] 范围内。只读 **uint8_t**。 |
| virtual [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() | 获取 R1C1 样式的公式。 |
| virtual **int32_t** [get_Row](./get_row/)() | 返回单元格所在工作表行的索引。只读 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | 获取单元格的值。只读 [System::Object](../../system/object/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) | 设置数字和日期的自定义显示格式。如果值为空，将使用 PresetNumberFormat 值。写入 [System::String](../../system/string/)。 |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | 设置 A1 样式的公式。 |
| virtual void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) | 设置数字和日期的内置显示格式。预设编号必须在 [0..22] 或 [37..49] 范围内。写入 **uint8_t**。 |
| virtual void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) | 设置 R1C1 样式的公式。 |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 设置单元格的值。写入 [System::Object](../../system/object/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非 shared）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)