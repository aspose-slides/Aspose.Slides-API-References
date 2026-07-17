---
title: ResultValueTask
second_title: Aspose.Slides C++ API 参考
description: 表示一种混合任务式类型，可包装直接结果值或 ResultTask<T>。
type: docs
weight: 53
url: /zh/system.threading.tasks/resultvaluetask/
---
## ResultValueTask 类


Represents a hybrid task-like type that can wrap either a direct result value or a ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 任务产生的结果的类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | 将此 [ResultValueTask](./) 转换为指向 ResultTask<T> 的共享指针。 |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | 为此任务配置 awaiter。 |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | 确定此实例是否等于另一个 [ResultValueTask](./) 实例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 确定此实例是否等于另一个对象。 |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | 确定当前对象和指定对象是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | 获取一个值，指示任务是否因取消而完成。 |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | 获取一个值，指示任务是否已完成。 |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | 获取一个值，指示任务是否成功完成。 |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | 获取一个值，指示任务是否因未处理的异常而完成。 |
| T [get_Result](./get_result/)() | 获取已完成任务的结果。 |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | 获取此任务的 awaiter，以支持 await 表达式。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | [ResultValueTask](./) 的不等运算符。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | [ResultValueTask](./) 的等号运算符。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 针对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| [ResultValueTask](./resultvaluetask/)() | 构造一个空的、未初始化的 [ResultValueTask](./)。 |
| [ResultValueTask](./resultvaluetask/)(const T\&) | 使用指定结果构造一个已完成的 [ResultValueTask](./)。 |
| [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | 从指向 ResultTask<T> 的共享指针构造一个 [ResultValueTask](./)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 备注


[ResultValueTask](./) 将 [ValueTask](../valuetask/)（针对同步结果的减少分配）的优势与包装现有 ResultTask<T> 对象的能力相结合。它提供可await的接口和各种任务状态检查方法。 
## 另见

* 类 [IEquatable](../../system/iequatable/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)