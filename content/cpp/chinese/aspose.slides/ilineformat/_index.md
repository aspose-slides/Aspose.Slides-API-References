---
title: ILineFormat
second_title: Aspose.Slides for C++ API 参考
description: 表示线的格式。
type: docs
weight: 2757
url: /zh/aspose.slides/ilineformat/
---
## ILineFormat 类

表示线的格式。

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | 确定两个 [LineFormat](../lineformat/) 实例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 也视为相等，尽管 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 也视为相等，尽管 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | 返回线对齐方式。读取 [LineAlignment](../linealignment/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | 返回线起始处的箭头长度。读取 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | 返回线起始处的箭头样式。读取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | 返回线起始处的箭头宽度。读取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | 返回线端帽样式。读取 [LineCapStyle](../linecapstyle/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | 返回自定义虚线模式。读取 **float**[]。 |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | 返回线虚线样式。读取 [LineDashStyle](../linedashstyle/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | 返回线末端的箭头长度。读取 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | 返回线末端的箭头样式。读取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | 返回线末端的箭头宽度。读取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | 返回线的填充格式。只读 [ILineFillFormat](../ilinefillformat/)。 |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | 如果线格式未定义（刚创建，默认），返回 true。只读 **bool**。 |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | 返回线连接样式。读取 [LineJoinStyle](../linejoinstyle/)。 |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | 返回线的斜接限制。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | 返回线的草图格式。只读 [ISketchFormat](../isketchformat/)。 |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | 返回线样式。读取 [LineStyle](../linestyle/)。 |
| virtual **double** [get_Width](./get_width/)() | 返回线的宽度。读取 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取已应用继承的有效线格式数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。实现自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# ‘is’ 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。实现自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | 设置线对齐方式。写入 [LineAlignment](../linealignment/)。 |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 设置线起始处的箭头长度。写入 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 设置线起始处的箭头样式。写入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 设置线起始处的箭头宽度。写入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | 设置线端帽样式。写入 [LineCapStyle](../linecapstyle/)。 |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | 设置自定义虚线模式。写入 **float**[]。 |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | 设置线虚线样式。写入 [LineDashStyle](../linedashstyle/)。 |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 设置线末端的箭头长度。写入 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 设置线末端的箭头样式。写入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 设置线末端的箭头宽度。写入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | 设置线连接样式。写入 [LineJoinStyle](../linejoinstyle/)。 |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | 设置线的斜接限制。写入 **float**。 |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | 设置线样式。写入 [LineStyle](../linestyle/)。 |
| virtual void [set_Width](./set_width/)(**double**) | 设置线的宽度。写入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非 shared）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。实现将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [ILineParamSource](../ilineparamsource/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)