---
title: LinkedList
second_title: Aspose.Slides for C++ API 参考
description: LinkedList 前向声明。
type: docs
weight: 404
url: /zh/system.collections.generic/linkedlist/
---
## LinkedList 类


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 包含的值类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| void [Add](./add/)(const T\&) override | 向列表末尾添加 **元素**。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | 在列表的 **节点** 之后添加 **元素**。 |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 在列表的 **节点** 之后添加 **新节点**。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | 在列表的 **节点** 之前添加 **元素**。 |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 在列表的 **节点** 之前添加 **新节点**。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | 向列表开头添加 **元素**。 |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 向列表开头添加 **新节点**。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | 向列表末尾添加 **元素**。 |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 向列表末尾添加 **新节点**。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | 获取集合中第一个元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | 获取 const 限定集合中第一个元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | 获取集合中第一个 const 限定元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | 获取集合末尾之后的不存在的 const 限定元素的迭代器。 |
| void [Clear](./clear/)() override | 删除列表中的所有元素。 |
| **bool** [Contains](./contains/)(const T\&) const override | 检查列表中是否存在 **元素**。 |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | 将容器数据复制到已有的数组元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 获取集合中最后一个 const 限定元素的逆向迭代器（逆序的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 获取集合开始之前的不存在的 const 限定元素的逆向迭代器。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | 获取集合末尾之后的不存在的元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | 获取 const 限定集合末尾之后的不存在的元素的迭代器。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），但两个 NaN 被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），但两个 NaN 被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | 在列表中执行 **元素** 的正向查找。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | 在列表中执行 **元素** 的逆向查找。 |
| int [get_Count](./get_count/)() const override | 获取列表中元素的数量。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | 获取列表中第一个元素的指针。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 检查集合是否只读。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | 获取列表中最后一个元素的指针。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 获取用于同步集合的对象。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | 获取枚举器以遍历当前 [LinkedList](./)。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
|  [ICollection](../icollection/icollection/)() | 默认构造函数。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 拷贝构造函数。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移动构造函数。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
|  [LinkedList](./linkedlist/)() | 创建空的 [LinkedList](./)。 |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | 拷贝构造函数。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 对序列应用累加函数。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 确定序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 确定序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 确定序列中是否存在满足条件的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 将元素转换为指定类型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 连接两个序列。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 确定序列是否包含指定的值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列元素数量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列的第一个元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一个元素；如果序列为空，则返回默认值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列的第一个元素；如果未找到则返回默认值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素；如果序列为空，则返回默认值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数，并返回得到的最大值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数，并返回得到的最小值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选择的键值，对序列的元素进行升序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选择的键值，对序列的元素进行降序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 反转序列中元素的顺序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 通过加入元素索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 对序列的每个元素进行投影，并将得到的序列合并为一个序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 从序列开头返回指定数量的连续元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定的谓词过滤序列。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移动赋值运算符。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移动赋值运算符。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 获取集合中最后一个元素的逆向迭代器（逆序的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 获取 const 限定集合中最后一个元素的逆向迭代器（逆序的第一个）。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [Remove](./remove/)(const T\&) override | 从列表中删除指定 **元素** 的第一次出现。 |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 从列表中删除节点。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [RemoveFirst](./removefirst/)() | 删除列表的第一个节点。 |
| void [RemoveLast](./removelast/)() | 删除列表的最后一个节点。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 获取集合开始之前的不存在的元素的逆向迭代器。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 获取 const 限定集合开始之前的不存在的元素的逆向迭代器。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 获取当前容器的 begin const 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 获取当前容器的 begin 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 获取当前容器的 end const 迭代器的实现。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 获取当前容器的 end 迭代器的实现。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [list_t](./list_t/) | 底层数据类型。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | 常量迭代器类型。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器类型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器类型。 |
## 备注

链表容器。实现了对 std::list 的包装。该类的对象只能通过 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 创建 LinkedList 类的实例。
  auto list = MakeObject<LinkedList<int>>();

  // 填充链表。
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // 打印链表项。
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
此代码示例产生以下输出：
1 15 25 30
*/
```

## 另见

* 类 [Object](../../system/object/)
* 类 [ICollection](../icollection/)
* 类 [Invalidatable](../../system.collections/invalidatable/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)