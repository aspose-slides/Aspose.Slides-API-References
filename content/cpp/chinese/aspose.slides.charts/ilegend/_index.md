---
title: ILegend
second_title: Aspose.Slides for C++ API 参考
description: 表示图表的图例属性。
type: docs
weight: 1080
url: /zh/aspose.slides.charts/ilegend/
---
## ILegend 类

表示图表的图例属性。

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定图表元素的实际高度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定图表元素的实际宽度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定图表元素相对于图表左上角的实际 x 位置（左）。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定图表元素相对于图表左上角的实际顶部位置。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 获取图表元素顶部相对于图表高度的比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | 获取图例条目。只读 [ILegendEntryCollection](../ilegendentrycollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | 获取对应于指定索引的图例条目的属性，该条目对应于图表中数据点。对于以下图表类型：条形饼图、爆炸饼图、爆炸饼图 3D、饼图、饼图 3D、饼图-条形图，数据点取自第一系列。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 返回图例的格式。只读 [IFormat](../iformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 指定图表元素高度相对于图表高度的比例。读取 **float**。 |
| virtual **bool** [get_Overlay](./get_overlay/)() | 确定是否允许其他图表元素覆盖图例。读取 **bool**。 |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | 指定图例在图表上的位置。X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。读取 [LegendPositionType](../legendpositiontype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 获取图表元素右侧相对于图表宽度的比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 指定图表元素宽度相对于图表宽度的比例。读取 **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 指定图表元素的 x 位置（左）相对于图表宽度的比例。读取 **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 指定图表元素顶部相对于图表高度的比例。读取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 与 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 指定图表元素高度相对于图表高度的比例。写入 **float**。 |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | 确定是否允许其他图表元素覆盖图例。写入 **bool**。 |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | 指定图例在图表上的位置。X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。写入 [LegendPositionType](../legendpositiontype/)。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 指定图表元素宽度相对于图表宽度的比例。写入 **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 指定图表元素的 x 位置（左）相对于图表宽度的比例。写入 **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 指定图表元素顶部相对于图表高度的比例。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [ILayoutable](../ilayoutable/)
* 类 [IFormattedTextContainer](../iformattedtextcontainer/)
* 类 [IActualLayout](../iactuallayout/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)