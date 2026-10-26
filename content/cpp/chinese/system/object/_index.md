---
title: Object
second_title: Aspose.Slides C++ API 参考
description: 基类，使得可以在 C# 中使用 System.Object 类提供的方法。所有在翻译环境中使用的非平凡类都应继承它。
type: docs
weight: 1119
url: /zh/system/object/
---
## 对象类

Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | 使用 C# [Object.Equals](./equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | 比较引用类型对象，遵循 C# 风格。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | 比较值类型对象，遵循 C# 风格。 |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使两个 NaN 被视为相等，尽管根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | 相当于 C# [Object.GetHashCode()](./gethashcode/) 方法。实现自定义对象的哈希。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](./gettype/) 调用。 |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](./lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](./memberwiseclone/) 方法。实现自定义类型的克隆。 |
|  [Object](./object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](./object/)([Object](./) const\&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](./sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../string/) [ToString](./tostring/)() const | 相当于 C# [Object.ToString()](./tostring/) 方法。实现自定义对象到字符串的转换。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 实现 C# typeof([System.Object](./)) 构造。 |
| void [Unlock](./unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](./weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](./~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [ptr](./ptr/) | 智能指针类型的别名。 |

## 备注

除了 C# [System.Object](./) 类可用的方法外，它还支持翻译代码环境中特定的一些概念。这包括智能指针类（[System::SmartPtr](../smartptr/)、[System::WeakPtr](../weakptr/)、[System::DynamicWeakPtr](../dynamicweakptr/)）使用的引用计数以及其他与内存管理、调试等相关的服务。

每个 [Object](./) 有两个引用计数器：共享引用计数器和弱引用计数器。弱引用计数器始终存储在独立的数据结构中，而不是存放在 [Object](./) 本身中，这允许弱指针在被引用对象被释放后仍然存在。智能引用计数器根据 ENABLE_EXTERNAL_REFCOUNT 宏的状态，存储在对象本身或同一独立结构中。默认情况下，在调试构建中启用，发布构建中禁用。如果智能指针计数器存储在对象本身，则仅在存在指向该对象的弱指针时才创建独立的数据结构。否则，会与对象本身一起创建。

所有智能指针使用这两个引用计数器，并贡献于同一个唯一的所有权组。

如果在栈上创建 [Object](./) 子类，则不能创建指向它的智能指针，否则会出现栈删除问题。

此类型既可以作为值类型在栈上分配，也可以使用 [System::MakeObject()](../makeobject/) 函数在堆上分配。对象分配后，切勿混用这两种情况：严格禁止将 [SmartPtr](../smartptr/) 指针指向栈分配的对象。

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)