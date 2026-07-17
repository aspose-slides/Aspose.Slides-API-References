---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API 参考
description: 智能指针类，用于跟踪存储对象的模板参数的指针模式，并在每次赋值后更新它们。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。
type: docs
weight: 781
url: /zh/system/dynamicweakptr/
---
## DynamicWeakPtr 类

智能指针类，可追踪存储对象的模板参数的指针模式，并在每次赋值后更新它们。此类型是用于管理其他对象删除的指针。它应分配在栈上，并通过值或 const 引用传递给函数。

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Pointee | 类型。 |
| trunkMode | 智能指针本身的模式，共享或弱引用。 |
| weakLeafs | 存储类型的模板参数索引，应设置为弱指针模式。 |

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 访问底层集合的 [begin()](../smartptr/begin/) 方法的访问器。仅当 SmartPtr_ 为具有 [begin()](../smartptr/begin/) 方法的特化类型时才会编译。 |
| auto [begin](../smartptr/begin/)() const | 访问底层集合的 [begin()](../smartptr/begin/) 方法的访问器。仅当 SmartPtr_ 为具有 [begin()](../smartptr/begin/) 方法的特化类型时才会编译。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 将指针强制转换为其自身类型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 static_cast 将指针转换为基类型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| auto [cbegin](../smartptr/cbegin/)() const | 访问底层集合的 [cbegin()](../smartptr/cbegin/) 方法的访问器。仅当 SmartPtr_ 为具有 [cbegin()](../smartptr/cbegin/) 方法的特化类型时才会编译。 |
| auto [cend](../smartptr/cend/)() const | 访问底层集合的 [cend()](../smartptr/cend/) 方法的访问器。仅当 SmartPtr_ 为具有 [cend()](../smartptr/cend/) 方法的特化类型时才会编译。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 使用 const_cast 对所指对象进行类型转换。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 对所指对象进行类型转换。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | 创建空智能指针。 |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | 创建指向给定对象的智能指针。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | 拷贝构造智能指针。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 拷贝构造智能指针。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | 拷贝构造智能指针。 |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | 移动构造智能指针。 |
| auto [end](../smartptr/end/)() | 访问底层集合的 [end()](../smartptr/end/) 方法的访问器。仅当 SmartPtr_ 为具有 [end()](../smartptr/end/) 方法的特化类型时才会编译。 |
| auto [end](../smartptr/end/)() const | 访问底层集合的 [end()](../smartptr/end/) 方法的访问器。仅当 SmartPtr_ 为具有 [end()](../smartptr/end/) 方法的特化类型时才会编译。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 获取所指对象。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 获取指针模式。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 获取所指对象，但断言指针处于共享模式。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 获取引用对象上存在的共享指针数量（包括当前指针），并断言当前指针为共享模式。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 对所指对象调用 [GetHashCode()](../smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 获取当前引用的对象（若存在），否则抛出异常。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 获取所指对象（若存在），否则返回 nullptr。等同于 [get()](../smartptr/get/)。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 获取引用的对象。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 获取所指对象（若存在），否则返回 nullptr。等同于 [get()](../smartptr/get/)。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 检查所指对象是否为特定类型或其子类型，遵循 C# 的 'is' 语义。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 检查指针是否指向除拥有对象之外的其他对象（由别名构造函数创建）。 |
| **bool** [IsShared](../smartptr/isshared/)() const | 检查指针是否处于共享模式。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | 检查指针是否处于弱模式。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | 检查指针是否非空。 |
| **bool** [operator!](../smartptr/operator_not/)() const | 检查指针是否为空。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 获取所指对象的引用，断言指针非空。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 允许访问引用对象的成员。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | 为 [SmartPtr](../smartptr/) 类提供 less 比较语义。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | 为 [SmartPtr](../smartptr/) 类提供 less 比较语义。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | 移动赋值智能指针。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | 拷贝赋值智能指针。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 拷贝赋值智能指针。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | 赋值智能指针。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | 将智能指针设为 null。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 检查智能指针是否为空。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 移除指针的别名（由别名构造函数创建），并确保其（若为共享）管理或（若为弱）跟踪相同的指向对象。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 设置所指对象。 |
| void [reset](../smartptr/reset/)() | 让指针指向 nullptr。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 设置指针模式。可能会改变被引用对象的引用计数。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 对所指对象（若存在）调用 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 创建所需模式的 [SmartPtr](../smartptr/) 对象。 |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 创建所需模式的空指针 [SmartPtr](../smartptr/) 对象。 |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 创建指向指定对象的 [SmartPtr](../smartptr/)，或将原始指针转换为 [SmartPtr](../smartptr/)。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造 [SmartPtr](../smartptr/) 对象。两指针随后指向同一对象。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造 [SmartPtr](../smartptr/) 对象。两指针随后指向同一对象。若允许，则执行类型转换。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | 移动构造 [SmartPtr](../smartptr/) 对象。实际上，如果两者模式相同，则交换两个指针。调用后 x 可能不可用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 通过创建不同类型的新数组来转换引用数组的类型。如果在 C# 中存在 C++ 不支持的数组类型转换，则此方法有用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 初始化空数组。用于转译某些 C# 代码结构。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 构造一个 [SmartPtr](../smartptr/)，其共享 ptr 的所有权信息，但持有一个无关且未管理的指针 p。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 使用 static_cast 对所指对象进行类型转换。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 将任意指针类型转换为指向 [Object](../object/) 的指针。无需 Pointee_ 类型完整。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | 获取 Pointee_ 类型的 [System::TypeInfo](../typeinfo/) 对象的快捷方式。 |
|  [~SmartPtr](../smartptr/~smartptr/)() | 销毁 [SmartPtr](../smartptr/) 对象。如有必要，降低所指对象的引用计数并删除对象。 |

## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) 基类别名。 |
| [DynamicWeakPtr_](./dynamicweakptr_/) | 自身类型别名。 |
| [Pointee_](./pointee_/) | 指向的类型。 |

## See Also

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)