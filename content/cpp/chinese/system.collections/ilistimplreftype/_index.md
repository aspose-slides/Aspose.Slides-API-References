---
title: IListImplRefType
second_title: "Aspose.Slides for C++ API 参考"
description: "存根实现了 System::Collections::IList 接口，针对 System::Collections::Generic::List 对象的引用类型实现。"
type: docs
weight: 131
url: /zh/system.collections/ilistimplreftype/
---
## IListImplRefType 类

存根实现了 [System::Collections::IList](../ilist/) 接口，针对 [System::Collections::Generic::List](../../system.collections.generic/list/) 对象的引用类型实现。

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## 方法

| 方法 | 描述 |
| --- | --- |
| int [Add](./add/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 在列表末尾添加元素。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [BoxValue](./boxvalue/)([System::SharedPtr](../../system/sharedptr/)\<T\>) | 将类型引用转换为对象值。 |
| void [Clear](./clear/)() override | 删除所有元素。 |
| **bool** [Contains](./contains/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | 检查列表中是否存在该项。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| int [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) 方法实现 获取集合中元素的数量。 |
| virtual **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() const | 获取指示列表是否具有固定大小的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::IEnumerator](../ienumerator/)\> [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) 实现 返回一个遍历集合的枚举器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类比。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。C# [System.Object.GetType()](../../system/object/gettype/) 调用的类比。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)(int, int) const override | 获取指定索引处的元素。 |
|  [IListImplRefType](./ilistimplreftype/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<T\>\>\>) | 创建新的对象实例。 |
| int [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | 获取项在容器中首次出现的索引。 |
| void [Insert](./insert/)(int, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 在指定位置插入元素，后移其他元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。C# 'is' 运算符的类比。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的类比。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| void [Remove](./remove/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 从列表中移除特定项的第一次实例。 |
| void [RemoveAt](./removeat/)(int) override | 移除指定位置的项。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的类比。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| static [System::SharedPtr](../../system/sharedptr/)\<T\> [UnboxValue](./unboxvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 将对象值转换为特定类型引用。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另请参见

* 类 [IList](../ilist/)
* 命名空间 [System::Collections](../)
* 库 [Aspose.Slides](../../)