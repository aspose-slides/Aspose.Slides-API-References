---
title: IAsyncResult
second_title: Aspose.Slides C++ API 参考
description: "表示异步操作的状态。此类的对象只能使用 System::MakeObject() 函数进行分配。永远不要在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 898
url: /zh/system/iasyncresult/
---
## IAsyncResult 类


表示异步操作的状态。此类的对象只能使用 [System::MakeObject()](../makeobject/) 函数进行分配。永远不要在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class IAsyncResult : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [get_AsyncState](./get_asyncstate/)() | 返回一个包含异步操作信息的对象。 |
| virtual [SharedPtr](../sharedptr/)\<[System::Threading::WaitHandle](../../system.threading/waithandle/)\> [get_AsyncWaitHandle](./get_asyncwaithandle/)() | 返回一个 WaitHandle 实例，可用于等待异步操作的完成。 |
| virtual **bool** [get_CompletedSynchronously](./get_completedsynchronously/)() | 返回一个指示异步操作是否同步完成的值。 |
| virtual **bool** [get_IsCompleted](./get_iscompleted/)() | 返回一个指示异步操作是否已完成的值。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类进行复制构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相当于 C# [Object.ToString()](../object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~IAsyncResult](./~iasyncresult/)() | 析构函数。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [smart_ptr](./smart_ptr/) | 指向 [IAsyncResult](./) 的共享指针。 |

## 另请参见

* 类 [Object](../object/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)