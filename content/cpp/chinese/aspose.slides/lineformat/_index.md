---
title: LineFormat
second_title: Aspose.Slides C++ API 参考
description: 表示线的格式。
type: docs
weight: 4382
url: /zh/aspose.slides/lineformat/
---
## LineFormat 类

表示线的格式。

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | 确定两个 [LineFormat](./) 实例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿照 C# 的浮点比较，即使两个 NaN 也被视为相等，尽管 IEC 60559:1989 将 NaN 定义为不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿照 C# 的浮点比较，即使两个 NaN 也被视为相等，尽管 IEC 60559:1989 将 NaN 定义为不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | 返回线对齐方式。读取 [LineAlignment](../linealignment/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | 返回线起始处的箭头长度。读取 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | 返回线起始处的箭头样式。读取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | 返回线起始处的箭头宽度。读取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | 返回线端点样式。读取 [LineCapStyle](../linecapstyle/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | 返回自定义虚线模式。读取 **float**[]。 |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | 返回线虚线样式。读取 [LineDashStyle](../linedashstyle/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | 返回线结束处的箭头长度。读取 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | 返回线结束处的箭头样式。读取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | 返回线结束处的箭头宽度。读取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | 返回线的填充格式。只读 [ILineFillFormat](../ilinefillformat/)。 |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | 如果线格式未定义（刚创建时为默认），返回 true。只读 **bool**。 |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | 返回线的连接样式。读取 [LineJoinStyle](../linejoinstyle/)。 |
| **float** [get_MiterLimit](./get_miterlimit/)() override | 返回线的斜接限制。读取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | 返回线的草图格式。只读 [ILineFillFormat](../ilinefillformat/)。 |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | 返回线样式。读取 [LineStyle](../linestyle/)。 |
| **double** [get_Width](./get_width/)() override | 返回线宽度。读取 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效线格式化数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减小指定值。 |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | 设置线对齐方式。写入 [LineAlignment](../linealignment/)。 |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | 设置线起始处的箭头长度。写入 [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | 设置线起始处的箭头样式。写入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | 设置线起始处的箭头宽度。写入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | 设置线端点样式。写入 [LineCapStyle](../linecapstyle/)。 |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | 设置自定义虚线模式。写入 **float**[]。 |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | 设置线虚线样式。写入 [LineDashStyle](../linedashstyle/)。 |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | 设置线结束处的箭头长度。写入 [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | 设置线结束处的箭头样式。写入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | 设置线结束处的箭头宽度。写入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | 设置线的连接样式。写入 [LineJoinStyle](../linejoinstyle/)。 |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | 设置线的斜接限制。写入 **float**。 |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | 设置线样式。写入 [LineStyle](../linestyle/)。 |
| void [set_Width](./set_width/)(**double**) override | 设置线宽度。写入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 设置第 n 个模板参数为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。允许将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另请参阅

* Class [PVIObject](../pviobject/)
* Class [ILineFormat](../ilineformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)