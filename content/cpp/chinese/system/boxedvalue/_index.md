---
title: BoxedValue
second_title: Aspose.Slides for C++ API 参考
description: "表示一个装箱值。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这将导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 105
url: /zh/system/boxedvalue/
---
## BoxedValue 类

表示一个装箱值。此类的对象应仅使用 [System::MakeObject()](../makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这将导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Type of the boxed value represented by the class |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | 构造一个表示指定装箱值的对象。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 确定当前对象和指定对象所表示的装箱值的相等性。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| int [GetHashCode](./gethashcode/)() const override | 返回当前对象的哈希码。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 获取对象的实际类型。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | 返回表示当前对象所表示的装箱值类型的值。 |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | 如果可以转换，则返回装箱对象的数值，否则返回零。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| **bool** [is](./is/)() const | 确定当前对象所表示的装箱值的类型是否为 **V**。 |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | 确定当前对象是否表示枚举类型的装箱值。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 复制构造函数。实际上并不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 将指定枚举中具有指定名称的枚举常量的值装箱。参数用于指定在解释指定枚举常量名称的字符串时是否忽略大小写。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | 将指定枚举中具有指定名称的枚举常量的值装箱。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 在字符串和 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 将当前对象所表示的装箱值转换为字符串。 |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | 使用指定的格式字符串将装箱对象转换为字符串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| const T\& [unbox](./unbox/)() const | 解箱当前对象所表示的值。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [BoxedValueBase](../boxedvaluebase/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)