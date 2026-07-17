---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for C++ API 参考
description: 不可变对象，包含有效的线条格式属性。
type: docs
weight: 2770
url: /zh/aspose.slides/ilineformateffectivedata/
---
## ILineFormatEffectiveData 类

不可变对象，包含有效的线条格式属性。

```cpp
class ILineFormatEffectiveData : public Aspose::Slides::ILineParamSource
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](./)\>) | 确定两个 [ILineFormatEffectiveData](./) 实例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，在此比较中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，在此比较中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | 返回线条对齐方式。只读 [LineAlignment](../linealignment/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | 返回线条起始处的箭头长度。只读 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | 返回线条起始处的箭头样式。只读 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | 返回线条起始处的箭头宽度。只读 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | 返回线帽样式。只读 [LineCapStyle](../linecapstyle/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | 返回自定义虚线模式。只读 **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | 返回线条虚线样式。只读 [LineDashStyle](../linedashstyle/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | 返回线条末端的箭头长度。只读 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | 返回线条末端的箭头样式。只读 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | 返回线条末端的箭头宽度。只读 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormatEffectiveData](../ilinefillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | 返回线条的填充格式。只读 [ILineFillFormatEffectiveData](../ilinefillformateffectivedata/)。 |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | 返回线条连接样式。只读 [LineJoinStyle](../linejoinstyle/)。 |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | 返回线条的斜接限制。只读 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormatEffectiveData](../isketchformateffectivedata/)\> [get_SketchFormat](./get_sketchformat/)() | 返回线条的草图格式。只读 [ISketchFormatEffectiveData](../isketchformateffectivedata/)。 |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | 返回线条样式。只读 [LineStyle](../linestyle/)。 |
| virtual **double** [get_Width](./get_width/)() | 返回线条宽度。只读 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行哈希处理。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守护对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并支持子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 守护对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

此接口与 [ILineFormat](../ilineformat/) 接口一起使用，以返回应用继承后的有效格式化值。

## 另请参阅

* 类 [ILineParamSource](../ilineparamsource/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)