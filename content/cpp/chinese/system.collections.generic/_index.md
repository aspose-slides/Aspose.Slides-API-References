---
title: "System::Collections::Generic"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 326
url: /zh/system.collections.generic/
---
## 类

| 类 | 描述 |
| --- | --- |
| [_KeyCollection](./_keycollection/) | [Dictionary](./dictionary/)的键集合。引用集合，不复制任何内容。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [_KeyList](./_keylist/) | 实现字典键的列表。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [_ValueCollection](./_valuecollection/) | [Dictionary](./dictionary/)的值集合。引用集合，不复制任何内容。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [_ValueList](./_valuelist/) | 实现字典值的列表。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [BaseDictionary](./basedictionary/) | 实现各种类似字典的数据结构的通用代码（例如 [Dictionary](./dictionary/)、[SortedDictionary](./sorteddictionary/)）。除在定义容器时用于继承外，不应直接使用。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [BaseEnumerator](./baseenumerator/) | 为 C# 风格使用包装 STL 风格类型的枚举器定义。除检查顺序迭代器是否存在外不做其他断言。使用 begin() 和 end() 函数。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [BaseKVCollection](./basekvcollection/) | 保存键或值集合的通用代码。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | 为实现 [System.Collections.Generic.IComparer](./icomparer/) 泛型接口提供基类。 |
| [DefaultComparer](./defaultcomparer/) | 默认比较器类。使用 operator < 和 operator == 进行比较。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | [Dictionary](./dictionary/) 类的前向声明。 |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/) 迭代器，提供 [KeyValuePair](./keyvaluepair/) 表记法。 |
| [DictionaryPtr](./dictionaryptr/) | [Dictionary](./dictionary/) 指针类，带有运算符重载。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | 包装预创建枚举器并将所有调用重定向到其中的迭代器。 |
| [HashDictionary](./hashdictionary/) | [HashDictionary](./hashdictionary/) 类的存根（当前未实现）。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [HashSet](./hashset/) | [HashSet](./hashset/) 类的前向声明。 |
| [HashSetPtr](./hashsetptr/) | 用于保存 [HashSet](./hashset/) 引用的指针。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [ICollection](./icollection/) | 元素集合的接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IComparer](./icomparer/) | 以“大于-等于-小于”方式比较两个对象的接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IDictionary](./idictionary/) | 类似字典容器的接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IEnumerable](./ienumerable/) | 提供包含元素枚举器的对象接口。 |
| [IEnumerator](./ienumerator/) | 可用于遍历若干元素的枚举器接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IEqualityComparer](./iequalitycomparer/) | 提供比较两个对象是否相等手段的接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IKVCollection](./ikvcollection/) | 包含字典类容器键或值的容器接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [IList](./ilist/) | 索引元素容器的接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [ISet](./iset/) | 包含唯一元素集合的容器接口。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/) 迭代器，提供键访问。 |
| [KeyValuePair](./keyvaluepair/) | 键和值的对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [KVPairIterator](./kvpairiterator/) | 适配迭代器，将 std::pair 包装为 [Dictionary](./dictionary/) 所期望的 KVPair。 |
| [LinkedList](./linkedlist/) | [LinkedList](./linkedlist/) 前向声明。 |
| [LinkedListNode](./linkedlistnode/) | 链表节点。实现对 std::list 迭代器的包装，该迭代器被链表包装。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [List](./list/) | [List](./list/) 前向声明。 |
| [ListExt](./listext/) | 实现 [IListWrapper](../system.collections/ilistwrapper/) 接口的通用 [List](./list/) 类。 |
| [ListPtr](./listptr/) | [List](./list/) 指针，带有访问运算符。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [Queue](./queue/) | [Queue](./queue/) 类的前向声明。 |
| [QueuePtr](./queueptr/) | [Queue](./queue/) 指针。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [ReverseEnumerator](./reverseenumerator/) | 反向遍历容器的枚举器。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [SimpleEnumerator](./simpleenumerator/) | 使用 rbegin() 和 rend() 函数直接持有元素的简单容器的迭代器类。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [SortedDictionary](./sorteddictionary/) | 已排序字典类型的前向声明。 |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | 已排序字典指针，带有访问运算符。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [SortedList](./sortedlist/) | 包装 FlatMap 结构的已排序列表。此类的对象只能通过 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针作为参数传递给函数。 |
| [SortedListHelper](./sortedlisthelper/) | 此辅助类用于屏蔽来自 [IDictionary](./idictionary/) 接口的虚函数 get_Keys、get_Values，并将其替换为具有不同返回类型的函数。 |
| [SortedSet](./sortedset/) | [SortedSet](./sortedset/) 类的前向声明。 |
| [SortedSetPtr](./sortedsetptr/) | 用于保存 [SortedSet](./sortedset/) 引用的指针。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [Stack](./stack/) | [Stack](./stack/) 类的前向声明。 |
| [StackPtr](./stackptr/) | [Stack](./stack/) 指针。此类型是用于管理其他对象删除的指针。应在栈上分配，并通过值或 const 引用传递给函数。 |
| [ValueIterator](./valueiterator/) | [Dictionary](./dictionary/) 迭代器，提供值访问。 |

## 结构体

| 结构体 | 描述 |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | 在 STL 环境中使用 [IComparer](./icomparer/) 的适配器。如果设置了 [IComparer](./icomparer/) 则使用它；否则使用 operator <（如果可用），否则返回 false。 |
| [DictionaryHashSelector](./dictionaryhashselector/) | [Dictionary](./dictionary/) 类的哈希函数选择器。若未提供替代实现，则使用 STL 哈希。 |
| [EqualityComparerAdapter](./equalitycompareradapter/) | 使得可以在 STL 风格的集合和算法中使用 [IEqualityComparer](./iequalitycomparer/) 的适配器。若设置了 [IEqualityComparer](./iequalitycomparer/) 则使用它；未设置时使用 operator ==、[Object::Equals](../system/object/equals/) 或 T::Equals 中可用的任意一个。 |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | 用于哈希的 [IEqualityComparer](./iequalitycomparer/) 适配器。若设置了比较器对象则使用它；否则使用通过 [DictionaryHashSelector](./dictionaryhashselector/) 结构选择的可用哈希方法。 |

## 函数

| 函数 | 描述 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 使用“等于”语义比较两个键值对。对键和值均使用 operator == 或 EqualsTo 方法（取决于哪一个已定义）。 |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 使用相反的“等于”语义比较两个键值对。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | 将数据插入流中。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |