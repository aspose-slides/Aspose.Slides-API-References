---
title: WeakPtr
second_title: Aspose.Slides for C++ API 参考
description: "System::SmartPtr 的子类，在构造时将自身设置为弱模式。请注意，由于 set_Mode() 仍可访问，此类并不能保证其实例始终保持在弱模式。此类型是用于管理其他对象删除的指针。它应在栈上分配，并通过值或 const 引用传递给函数。"
type: docs
weight: 1470
url: /zh/system/weakptr/
---
## WeakPtr 类

Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | 被指向类型。 |
## 方法

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 访问底层集合的[begin()](../smartptr/begin/)方法。仅在SmartPtr_为具有[begin()](../smartptr/begin/)方法的特化类型时编译。 |
| auto [begin](../smartptr/begin/)() const | 访问底层集合的[begin()](../smartptr/begin/)方法。仅在SmartPtr_为具有[begin()](../smartptr/begin/)方法的特化类型时编译。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 将指针转换为其自身类型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用static_cast将指针转换为基类类型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用dynamic_cast将指针转换为派生类型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用dynamic_cast将指针转换为派生类型。 |
| auto [cbegin](../smartptr/cbegin/)() const | 访问底层集合的[cbegin()](../smartptr/cbegin/)方法。仅在SmartPtr_为具有[cbegin()](../smartptr/cbegin/)方法的特化类型时编译。 |
| auto [cend](../smartptr/cend/)() const | 访问底层集合的[cend()](../smartptr/cend/)方法。仅在SmartPtr_为具有[cend()](../smartptr/cend/)方法的特化类型时编译。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 使用const_cast对指向对象进行类型转换。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 使用dynamic_cast对指向对象进行类型转换。 |
| auto [end](../smartptr/end/)() | 访问底层集合的[end()](../smartptr/end/)方法。仅在SmartPtr_为具有[end()](../smartptr/end/)方法的特化类型时编译。 |
| auto [end](../smartptr/end/)() const | 访问底层集合的[end()](../smartptr/end/)方法。仅在SmartPtr_为具有[end()](../smartptr/end/)方法的特化类型时编译。 |
| **bool** [expired](./expired/)() const | 检查引用的对象是否已被删除。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 获取指向的对象。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 获取指针模式。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 获取指向的对象，但断言指针处于共享模式。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 获取指向对象的共享指针数量（包括当前指针），并断言当前指针处于共享模式。 |
| [Object](../object/) * [get_weak](./get_weak/)() const | 获取引用的对象，并断言指针处于弱模式。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 对指向的对象调用[GetHashCode()](../smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 获取当前引用的对象（如果存在），否则抛出异常。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 获取指向的对象（如果存在），否则返回nullptr。等同于[get()](../smartptr/get/)。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 获取引用的对象。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 获取指向的对象（如果存在），否则返回nullptr。等同于[get()](../smartptr/get/)。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 检查指向的对象是否是特定类型或其子类型，遵循C#的`is`语义。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 检查指针是否指向与拥有者不同的对象（由别名构造函数创建）。 |
| **bool** [IsShared](../smartptr/isshared/)() const | 检查指针是否处于共享模式。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | 检查指针是否处于弱模式。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | 检查指针是否非空。 |
| **bool** [operator!](../smartptr/operator_not/)() const | 检查指针是否为空。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 获取指向对象的引用，并断言指针非空。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 允许访问引用对象的成员。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | 为[SmartPtr](../smartptr/)类提供小于比较语义。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | 为[SmartPtr](../smartptr/)类提供小于比较语义。 |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | 为弱指针赋值。调用SmartPtr_的特定赋值运算符。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 对[SmartPtr](../smartptr/)对象进行移动赋值，x变为不可使用。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | 对[SmartPtr](../smartptr/)对象进行拷贝赋值。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 对[SmartPtr](../smartptr/)对象进行拷贝赋值，执行必要的类型转换。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | 将原始指针赋给[SmartPtr](../smartptr/)对象。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | 将指针值设为nullptr。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 检查弱指针是否为空。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 移除别名构造函数创建的别名，使指针（若为共享）管理或（若为弱）跟踪相同的对象。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 设置指向的对象。 |
| void [reset](../smartptr/reset/)() | 使指针指向nullptr。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 设置指针模式，可能会更改引用对象的引用计数。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 对指向的对象（如果有）调用SetTemplateWeakPtr()方法。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 创建所需模式的[SmartPtr](../smartptr/)对象。 |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 创建空指针[SmartPtr](../smartptr/)对象，使用所需模式。 |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 创建指向指定对象的[SmartPtr](../smartptr/)，或将原始指针转换为[SmartPtr](../smartptr/)。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造[SmartPtr](../smartptr/)对象，两个指针随后指向同一对象。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | 拷贝构造[SmartPtr](../smartptr/)对象，两个指针随后指向同一对象。若允许则执行类型转换。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | 移动构造[SmartPtr](../smartptr/)对象。实质上交换两个指针（若模式相同），调用后x可能不可使用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 通过创建不同类型的新数组来转换引用数组的类型。用于在C#中存在但C++不支持的数组类型转换。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 初始化空数组。用于翻译某些C#代码结构。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 构造一个[SmartPtr](../smartptr/)，它共享ptr的所有权信息，但持有一个不相关且未管理的指针p。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 使用static_cast对指向对象进行类型转换。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 将任意指针类型转换为指向[Object](../object/)的指针。无需Pointee_类型完整。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | 获取Pointee_类型的[System::TypeInfo](../typeinfo/)对象的快捷方式。 |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | 创建空指针。 |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | 为给定对象创建弱指针。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | 创建引用相同ptr指向对象的弱指针。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 创建引用相同x指向对象的弱指针。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | 拷贝构造弱指针。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | 拷贝构造弱指针。 |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 移动构造弱指针。 |
|  [~SmartPtr](../smartptr/~smartptr/)() | 销毁[SmartPtr](../smartptr/)对象。如有必要，减小指向对象的引用计数并删除对象。 |
## 类型别名

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | 对应[SmartPtr](../smartptr/)类的别名。 |
| [WeakPtr_](./weakptr_/) | 本身类型的别名。 |
| [Pointee_](./pointee_/) | 被指向的类型。 |
## 另请参阅

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)