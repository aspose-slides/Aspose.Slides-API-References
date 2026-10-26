---
title: SmartPtr
second_title: Aspose.Slides for C++ API 参考
description: "指针类用于包装在堆上分配的类型。将其用于管理继承 Object 的类的内存。此指针类型遵循侵入式指针语义。引用计数器要么存储在 Object 本身，要么存储在与 Object 实例紧密绑定的计数结构中。无论如何，所有 SmartPtr 实例都会形成单一所有权组，无论它们是如何创建的，这与 std::shared_ptr 类的行为不同。将原始指针转换为 SmartPtr 是安全的，前提是还有其他 SmartPtr 实例持有对同一对象的共享引用。SmartPtr 类实例可以处于两种状态：共享指针和弱指针。为保持对象存活，需要使共享引用计数为正。弱指针和共享指针都可用于访问指向的对象（调用方法、读取或写入字段等），但弱指针不参与共享指针的引用计数。当最后一个‘shared’ SmartPtr 指针被销毁时，对象会被删除。因此，请确保在对象不存在其他共享 SmartPtr 指针时不会发生此情况，例如在对象构造或析构期间。使用 System::Object::ThisProtector 哨兵对象（在 C++ 代码中）或 CppCTORSelfReference 或 CppSelfReference 属性（在正在翻译的 C# 代码中）来解决此问题。类似地，请确保通过使用 System::WeakPtr 指针类或 System::SmartPtrMode::Weak 指针模式（在 C++ 代码中）或 CppWeakPtr 属性（在正在翻译的 C# 代码中）来打破循环引用。如果两个或更多对象使用‘shared’指针相互引用，它们将永远不会被删除。如果需要在运行时切换指针类型（弱或共享），请使用 System::SmartPtr<T>::set_Mode() 方法或 System::DynamicWeakPtr 类。SmartPtr 类不包含任何虚方法。只有在您自行创建内存管理策略时才应继承它。此类型是用于管理其他对象删除的指针。它应在栈上分配，并以值或 const 引用传递给函数。"
type: docs
weight: 1210
url: /zh/system/smartptr/
---
## SmartPtr 类

指针类用于包装分配在堆上的类型。将其用于管理继承 [Object](../object/) 的类的内存。此指针类型遵循侵入式指针语义。引用计数器要么存储在 [Object](../object/) 本身，要么存储在与 [Object](../object/) 实例紧密绑定的计数结构中。无论如何，所有 [SmartPtr](./) 实例都会形成单一所有权组，无论它们是如何创建的，这与 std::shared_ptr 类的行为不同。将原始指针转换为 [SmartPtr](./) 是安全的，前提是还有其他 [SmartPtr](./) 实例持有对同一对象的共享引用。[SmartPtr](./) 类的实例可以处于两种状态之一：共享指针和弱指针。为了保持对象存活，必须使对它的共享引用计数为正。弱指针和共享指针都可以用于访问指向的对象（调用方法、读取或写入字段等），但弱指针不参与共享指针的引用计数。[Object](../object/) 在最后一个指向它的‘shared’ [SmartPtr](./) 指针被销毁时被删除。因此，请确保在对象不存在其他共享 [SmartPtr](./) 指针的情况下不会发生此情况，例如在对象构造或析构期间。使用 System::Object::ThisProtector 哨兵对象（在 C++ 代码中）或 CppCTORSelfReference 或 CppSelfReference 属性（在正在翻译的 C# 代码中）来解决此问题。类似地，请确保通过使用 [System::WeakPtr](../weakptr/) 指针类或 [System::SmartPtrMode::Weak](../smartptrmode/) 指针模式（在 C++ 代码中）或 CppWeakPtr 属性（在正在翻译的 C# 代码中）来打破循环引用。如果两个或更多对象使用‘shared’指针相互引用，它们将永远不会被删除。如果需要在运行时切换指针类型（弱或共享），请使用 [System::SmartPtr<T>::set_Mode()](./set_mode/) 方法或 [System::DynamicWeakPtr](../dynamicweakptr/) 类。[SmartPtr](./) 类不包含任何虚方法。只有在您自行创建内存管理策略时才应继承它。此类型是用于管理其他对象销毁的指针。它应当在栈上分配，并以值传递或 const 引用传递给函数。

```cpp
template<class T>class SmartPtr
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 指向对象的类型。必须是 [System::Object](../object/) 或其子类。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| auto [begin](./begin/)() | 用于底层集合的 [begin()](./begin/) 方法的访问器。仅当 SmartPtr_ 为具有 [begin()](./begin/) 方法的特化类型时才编译。 |
| auto [begin](./begin/)() const | 用于底层集合的 [begin()](./begin/) 方法的访问器。仅当 SmartPtr_ 为具有 [begin()](./begin/) 方法的特化类型时才编译。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | 将指针转换为其自身类型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | 使用 static_cast 将指针转换为基类类型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| auto [cbegin](./cbegin/)() const | 用于底层集合的 [cbegin()](./cbegin/) 方法的访问器。仅当 SmartPtr_ 为具有 [cbegin()](./cbegin/) 方法的特化类型时才编译。 |
| auto [cend](./cend/)() const | 用于底层集合的 [cend()](./cend/) 方法的访问器。仅当 SmartPtr_ 为具有 [cend()](./cend/) 方法的特化类型时才编译。 |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | 对指向的对象使用 const_cast 将指针转换为不同类型。 |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | 对指向的对象使用 dynamic_cast 将指针转换为不同类型。 |
| auto [end](./end/)() | 用于底层集合的 [end()](./end/) 方法的访问器。仅当 SmartPtr_ 为具有 [end()](./end/) 方法的特化类型时才编译。 |
| auto [end](./end/)() const | 用于底层集合的 [end()](./end/) 方法的访问器。仅当 SmartPtr_ 为具有 [end()](./end/) 方法的特化类型时才编译。 |
| [Pointee_](./pointee_/) * [get](./get/)() const | 获取指向的对象。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | 获取指针模式。 |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | 获取指向的对象，但断言指针处于共享模式。 |
| int [get_shared_count](./get_shared_count/)() const | 获取引用对象上存在的共享指针数量，包括当前指针。断言当前指针处于共享模式。 |
| int [GetHashCode](./gethashcode/)() const | 对指向的对象调用 [GetHashCode()](./gethashcode/)。 |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | 获取当前引用的对象（若有），否则抛出异常。 |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | 获取指向的对象（若有），否则返回 nullptr。与 [get()](./get/) 相同。 |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | 获取引用的对象。 |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | 获取指向的对象（若有），否则返回 nullptr。与 [get()](./get/) 相同。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 检查指向的对象是否为特定类型或其子类型。遵循 C# 的 'is' 语义。 |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | 检查指针是否指向与拥有对象不同的对象（由别名构造函数创建）。 |
| **bool** [IsShared](./isshared/)() const | 检查指针是否处于共享模式。 |
| **bool** [IsWeak](./isweak/)() const | 检查指针是否处于弱模式。 |
| explicit  [operator bool](./operator_bool/)() const | 检查指针是否非空。 |
| **bool** [operator!](./operator_not/)() const | 检查指针是否为空。 |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | 获取指向对象的引用。断言指针非空。 |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | 允许访问引用对象的成员。 |
| **bool** [operator<](./operator_less/)(Y *) const | 为 [SmartPtr](./) 类提供小于比较语义。 |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | 为 [SmartPtr](./) 类提供小于比较语义。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | 对 [SmartPtr](./) 对象进行移动赋值。x 将不可用。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | 对 [SmartPtr](./) 对象进行拷贝赋值。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | 对 [SmartPtr](./) 对象进行拷贝赋值。执行所需的类型转换。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | 将原始指针赋给 [SmartPtr](./) 对象。 |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | 将指针值设为 nullptr。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 检查指针是否指向 nullptr。 |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | 从指针中移除别名（由别名构造函数创建），确保它（若为共享）管理或（若为弱）跟踪同一指向对象。 |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | 设置指向的对象。 |
| void [reset](./reset/)() | 使指针指向 nullptr。 |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | 设置指针模式。可能改变引用对象的引用计数。 |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | 对指向的对象（若有）调用 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | 创建所需模式的 [SmartPtr](./) 对象。 |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 创建所需模式的空指针 [SmartPtr](./) 对象。 |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 创建指向指定对象的 [SmartPtr](./)，或将原始指针转换为 [SmartPtr](./)。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造 [SmartPtr](./) 对象。两指针随后指向同一对象。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造 [SmartPtr](./) 对象。两指针随后指向同一对象。如允许则执行类型转换。 |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | 移动构造 [SmartPtr](./) 对象。实质上交换两个指针（若模式相同），调用后 x 可能不可用。 |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 通过创建不同类型的新数组来转换引用数组的类型。如果在 C# 中有不受 C++ 支持的数组类型强制转换，则此方法有用。 |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | 初始化空数组。用于翻译某些 C# 代码结构。 |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 构造一个 [SmartPtr](./)，该对象与 ptr 的初始值共享所有权信息，但持有一个不相关且未管理的指针 p。 |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | 对指向的对象使用 static_cast 将指针转换为不同类型。 |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | 将任意指针类型转换为指向 [Object](../object/) 的指针。不要求 Pointee_ 类型完整。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | 获取 Pointee_ 类型的 [System::TypeInfo](../typeinfo/) 对象的快捷方式。 |
|  [~SmartPtr](./~smartptr/)() | 销毁 [SmartPtr](./) 对象。如有需要，减少指向对象的引用计数并删除该对象。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Pointee_](./pointee_/) | 指向的类型。 |
| [SmartPtr_](./smartptr_/) | 特化的智能指针类型。 |
| [ArrayType](./arraytype/) | 如果是 [System::Array](../array/) 的特化，则与 Pointee_ 相同，否则为 void。 |
| [ValueType](./valuetype/) | 指向数组的存储类型。仅当 T 为 [System::Array](../array/) 的特化时有意义。 |

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)