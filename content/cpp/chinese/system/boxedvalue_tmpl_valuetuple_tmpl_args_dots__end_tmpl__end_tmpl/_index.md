---
title: BoxedValue< ValueTuple< Args... > >
second_title: Aspose.Slides for C++ API 参考
description: 值元组的装箱版本。
type: docs
weight: 118
url: /zh/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > 类

值元组的装箱版本。

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| 名称 | Args 元组元素类型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | 构造一个表示指定装箱值的 [BoxedValue](../boxedvalue/) 对象。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 确定当前对象和指定对象所表示的装箱值的相等性。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 仿真 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 仿真 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| int [GetHashCode](./gethashcode/)() const override | 返回当前对象的哈希码。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 获取对象的实际类型。 |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | 返回索引位置的元素。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| **bool** [is](./is/)() const | 确定当前对象所表示的装箱值的类型是否为 **V**。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于 strings 的情况。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 返回装箱值的字符串表示。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | 解除装箱值。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [ITuple](../../system.runtime.compilerservices/ituple/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)