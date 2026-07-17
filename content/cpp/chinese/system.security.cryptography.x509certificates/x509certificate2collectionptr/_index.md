---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides C++ API 参考
description: 指向 X509 证书集合的指针。此类型是用于管理其他对象删除的指针。它应分配在栈上，并以值或 const 引用方式传递给函数。
type: docs
weight: 66
url: /zh/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr 类

Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## 方法

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 对底层集合的 [begin()](../../system/smartptr/begin/) 方法的访问器。仅在 SmartPtr_ 为带有 [begin()](../../system/smartptr/begin/) 方法的特化类型时编译。 |
| auto [begin](../../system/smartptr/begin/)() const | 对底层集合的 [begin()](../../system/smartptr/begin/) 方法的访问器。仅在 SmartPtr_ 为带有 [begin()](../../system/smartptr/begin/) 方法的特化类型时编译。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 将指针转换为其自身类型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 static_cast 将指针转换为基类类型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 将指针转换为派生类型。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 对底层集合的 [cbegin()](../../system/smartptr/cbegin/) 方法的访问器。仅在 SmartPtr_ 为带有 [cbegin()](../../system/smartptr/cbegin/) 方法的特化类型时编译。 |
| auto [cend](../../system/smartptr/cend/)() const | 对底层集合的 [cend()](../../system/smartptr/cend/) 方法的访问器。仅在 SmartPtr_ 为带有 [cend()](../../system/smartptr/cend/) 方法的特化类型时编译。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 使用 const_cast 对指向的对象进行不同类型的转换。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 对指向的对象进行不同类型的转换。 |
| auto [end](../../system/smartptr/end/)() | 对底层集合的 [end()](../../system/smartptr/end/) 方法的访问器。仅在 SmartPtr_ 为带有 [end()](../../system/smartptr/end/) 方法的特化类型时编译。 |
| auto [end](../../system/smartptr/end/)() const | 对底层集合的 [end()](../../system/smartptr/end/) 方法的访问器。仅在 SmartPtr_ 为带有 [end()](../../system/smartptr/end/) 方法的特化类型时编译。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 获取指向的对象。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 获取指针模式。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 获取指向的对象，但断言指针处于共享模式。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 获取引用对象上存在的共享指针数量（包括当前指针），并断言当前指针处于共享模式。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 在指向的对象上调用 [GetHashCode()](../../system/smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 获取当前引用的对象（如果有），否则抛出异常。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 获取指向的对象（如果有），否则返回 nullptr。等同于 [get()](../../system/smartptr/get/)。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 获取引用的对象。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 获取指向的对象（如果有），否则返回 nullptr。等同于 [get()](../../system/smartptr/get/)。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 检查指向的对象是否为特定类型或其子类型。遵循 C# 的 `is` 语义。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 检查指针是否指向除拥有对象之外的其他对象（由别名构造函数创建）。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 检查指针是否处于共享模式。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 检查指针是否处于弱引用模式。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 检查指针是否非空。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 检查指针是否为空。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 获取指向对象的引用。断言指针非空。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 允许访问引用对象的成员。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | 为 [SmartPtr](../../system/smartptr/) 类提供小于比较语义。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | 为 [SmartPtr](../../system/smartptr/) 类提供小于比较语义。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | 对 [SmartPtr](../../system/smartptr/) 对象进行移动赋值。x 将不可用。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | 对 [SmartPtr](../../system/smartptr/) 对象进行拷贝赋值。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | 对 [SmartPtr](../../system/smartptr/) 对象进行拷贝赋值。执行所需的类型转换。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 将原始指针分配给 [SmartPtr](../../system/smartptr/) 对象。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 将指针值设为 nullptr。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 检查指针是否指向 nullptr。 |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | 访问器。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 移除指针的别名（由别名构造函数创建），并确保其在共享或弱引用模式下仍管理/跟踪同一对象。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 设置指向的对象。 |
| void [reset](../../system/smartptr/reset/)() | 使指针指向 nullptr。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 设置指针模式。可能会改变引用对象的引用计数。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 在指向的对象（如果有）上调用 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 创建所需模式的 [SmartPtr](../../system/smartptr/) 对象。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 创建所需模式的空指针 [SmartPtr](../../system/smartptr/) 对象。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 创建指向指定对象的 [SmartPtr](../../system/smartptr/)，或将原始指针转换为 [SmartPtr](../../system/smartptr/)。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | 拷贝构造 [SmartPtr](../../system/smartptr/) 对象。两指针随后指向同一对象。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 拷贝构造 [SmartPtr](../../system/smartptr/) 对象。两指针随后指向同一对象。若允许则执行类型转换。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | 移动构造 [SmartPtr](../../system/smartptr/) 对象。若两指针模式相同则交换它们，调用后 x 可能不可用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 通过创建不同类型的新数组，将引用数组的类型转换为另一种类型。适用于 C# 中不支持的数组类型转换。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 初始化空数组。用于翻译某些 C# 代码构造。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 构造一个 [SmartPtr](../../system/smartptr/)，其共享 ptr 的所有权信息，但持有一个不相关且未管理的指针 p。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 使用 static_cast 对指向的对象进行不同类型的转换。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 将任意指针类型转换为指向 [Object](../../system/object/) 的指针。无需 Pointee_ 类型完整。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | 获取 Pointee_ 类型的 [System::TypeInfo](../../system/typeinfo/) 对象的快捷方式。 |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | 空指针构造函数。 |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | 构造函数。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | 销毁 [SmartPtr](../../system/smartptr/) 对象。如有需要，降低指向对象的引用计数并删除对象。 |

## 参见

* 类 [SmartPtr](../../system/smartptr/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)