---
title: SortedDictionary
second_title: Aspose.Slides for C++ API 参考
description: 已排序字典类型前向声明。
type: docs
weight: 521
url: /zh/system.collections.generic/sorteddictionary/
---
## SortedDictionary 类

Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Template parameters

| 参数 | 描述 |
| --- | --- |
| TKey | 键的类型。 |
| TValue | 值的类型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | 向容器中添加键值对。 |
| virtual void [Add](../icollection/add/)(const T\&) | 向集合中添加元素。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | 获取指向集合中第一个元素（如果存在）的迭代器。由于 [GetEnumerator()](../ienumerable/getenumerator/) 返回 T 的副本对象，不能使用此迭代器修改引用的对象。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | 获取指向集合的 const 限定实例中第一个元素（如果存在）的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | 获取指向集合中第一个 const 限定元素（如果存在）的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | 获取指向集合中最后一个 const 限定元素之后的迭代器（如果存在）。 |
| virtual void [Clear](../icollection/clear/)() | 删除集合中的所有元素。 |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | 检查集合中是否存在该元素。 |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | 检查容器是否包含该键。 |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | 将字典内容复制到现有数组元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 获取指向集合中最后一个 const 限定元素的逆向迭代器（逆序中的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 获取指向集合开始之前的不存在的 const 限定元素的逆向迭代器。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | 获取指向集合中最后一个元素之后的迭代器（如果存在）。由于 [GetEnumerator()](../ienumerable/getenumerator/) 返回 T 的副本对象，不能使用此迭代器修改引用的对象。 |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | 获取指向 const 限定的集合实例中最后一个元素之后的迭代器（如果存在）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 方式比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989 NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管依据 IEC 60559:1989 NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() const | 获取用于对 SortedDictionary<TKey,TValue> 元素进行排序的 IComparer<TKey>。 |
| virtual int [get_Count](../icollection/get_count/)() const | 获取集合中的元素数量。 |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | 检查集合大小是否固定。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 检查集合是否只读。 |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | 检查容器是否线程安全。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | 访问键集合。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 获取用于同步集合的对象。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | 访问值集合。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| static [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | 单例访问函数。 |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 获取枚举器以遍历当前字典。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | 如果找到则返回值；否则返回 **Value()**。 |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | 如果找到则返回值；否则返回 **defaultValue**。 |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | 如果找到则返回值；否则返回 **null**（仅对引用类型有意义）。 |
| [ICollection](../icollection/icollection/)() | 默认构造函数。 |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 拷贝构造函数。 |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移动构造函数。 |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | 获取函数。 |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | 设置函数。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 对序列应用累加函数。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 确定序列的所有元素是否满足条件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 确定序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 确定序列中是否存在满足条件的任意元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 将元素强制转换为指定类型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 连接两个序列。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 确定序列是否包含指定值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 返回序列中元素的数量（通过直接计数计算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列中元素的数量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引处的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一个元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回满足指定条件的序列的第一个元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一个元素；如果序列为空则返回默认值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回满足条件的序列的第一个元素；如果未找到则返回默认值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 对序列的元素进行分组。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 对序列的元素进行分组。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最后一个元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最后一个元素；如果序列为空则返回默认值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回产生的最大值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 对通用序列的每个元素调用转换函数并返回产生的最小值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根据指定类型过滤序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选取的键值，以升序对序列的元素进行排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根据 keySelector 选取的键值，以降序对序列的元素进行排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 反转序列中元素的顺序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 转换序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 通过加入元素索引，将序列的每个元素转换为新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 对序列的每个元素进行投影，并将产生的序列合并为一个序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 返回序列开头指定数量的连续元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 从序列创建数组。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 从序列创建 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根据指定的谓词过滤序列。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移动赋值运算符。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移动赋值运算符。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 获取指向集合中最后一个元素的逆向迭代器（逆序中的第一个）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 获取指向 const 限定集合中最后一个元素的逆向迭代器（逆序中的第一个）。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | 从容器中移除键。 |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | 从集合中删除元素。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 获取指向集合开始之前的不存在元素的逆向迭代器。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 获取指向 const 限定集合开始之前的不存在元素的逆向迭代器。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [SortedDictionary](./sorteddictionary/)() | 构造空字典。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | 构造空字典。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | 拷贝构造函数。 |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | 拷贝构造函数。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | 查找值并在找到时返回。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | 获取当前容器的 const 起始迭代器实现。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | 获取当前容器的起始迭代器实现。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | 获取当前容器的 const 结束迭代器实现。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | 获取当前容器的结束迭代器实现。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [KeyCollection](./keycollection/) | 键集合类型。 |
| [ValueCollection](./valuecollection/) | 值集合类型。 |
| [map_t](./map_t/) | 底层数据类型。 |
| [this_t](./this_t/) | 自身类型。 |
| [Ptr](./ptr/) | 指针类型。 |
| [KVPair](./kvpair/) | 键值对类型。 |
| [IEnumerablePtr](./ienumerableptr/) | 相同元素的集合。 |
| [IEnumeratorPtr](./ienumeratorptr/) | **枚举器** 类型。 |
| [iterator](./iterator/) | 迭代器类型。 |
| [const_iterator](./const_iterator/) | 常量迭代器类型。 |
| [reverse_iterator](./reverse_iterator/) | 逆向迭代器类型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量逆向迭代器类型。 |

## 备注

SortedDictionary 类包装 STL map。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为会导致运行时错误或断言失败。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

## 另见

* 类 [BaseDictionary](../basedictionary/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)