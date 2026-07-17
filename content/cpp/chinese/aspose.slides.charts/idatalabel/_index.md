---
title: IDataLabel
second_title: Aspose.Slides C++ API 参考
description: 表示系列标签。
type: docs
weight: 937
url: /zh/aspose.slides.charts/idatalabel/
---
## IDataLabel 类

Represents a series labels.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用参数 \"text\" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准 NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定图表元素的实际高度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定图表元素的实际宽度。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定图表元素相对于图表左上角的实际 x 位置（左）。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定图表元素相对于图表左上角的实际顶部。调用方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以获取实际值。读取 **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 获取图表元素相对于图表高度的顶部比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回图表。只读 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | 返回数据标签的格式。只读 [IDataLabelFormat](../idatalabelformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 指定图表元素相对于图表高度的高度比例。读取 **float**。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False 表示数据标签不可见（因此所有 Show* 标志（如 ShowValue 等）均为 false）。只读 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回演示文稿。只读 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 获取图表元素相对于图表宽度的右侧比例。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基础幻灯片。只读 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 返回图表文本格式。只读 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、数值轴的显示单位标签、坐标轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 属性进行格式化。只读 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | 获取工作簿数据单元格。如果 IDataLabelFormat::get(set)_ShowLabelValueFromCell 属性为 true，则适用。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 指定图表元素相对于图表宽度的宽度比例。读取 **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 指定图表元素相对于图表宽度的 x 位置（左）比例。读取 **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 指定图表元素相对于图表高度的顶部比例。读取 **float**。 |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | 根据 [DataLabelFormat](../datalabelformat/) 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual void [Hide](./hide/)() | 通过将所有 Show* 标志（ShowValue 等）设置为 false 来隐藏数据标签。执行后 IsVisible 将为 false。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的实例类型。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 指定图表元素相对于图表高度的高度比例。写入 **float**。 |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | 设置工作簿数据单元格。如果 IDataLabelFormat::get(set)_ShowLabelValueFromCell 属性为 true，则适用。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 指定图表元素相对于图表宽度的宽度比例。写入 **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 指定图表元素相对于图表宽度的 x 位置（左）比例。写入 **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 指定图表元素相对于图表高度的顶部比例。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [ILayoutable](../ilayoutable/)
* 类 [IOverridableText](../ioverridabletext/)
* 类 [IActualLayout](../iactuallayout/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)